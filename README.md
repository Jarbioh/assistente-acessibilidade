# Assistente Virtual para Acessibilidade Digital (Protótipo "Conecta Simples")

**Autor:** [Járbio Mulhovo]
**Projeto para:** Imersão IA Alura + Google Gemini (Maio 2025)

## Descrição do Projeto

Este projeto é um protótipo de um assistente virtual em português, chamado "Conecta Simples", desenvolvido com o objetivo de promover a inclusão digital e facilitar o acesso a tecnologias para pessoas com baixo letramento digital, idosos, ou qualquer indivíduo que enfrente dificuldades em utilizar interfaces digitais complexas.

O assistente utiliza o poder do Google Gemini para compreender linguagem natural simplificada e fornecer respostas e orientações de forma clara, paciente e empática. O foco é ser uma ponte entre o usuário e o mundo digital, tornando tarefas comuns mais acessíveis.

### Funcionalidades Implementadas (Protótipo Colab):

1.  **Comunicação Facilitada:** Permite ao usuário, através de comandos simples, simular o ato de ligar ou enviar mensagens para contatos. O Gemini interpreta a intenção e extrai as informações necessárias.
2.  **Acesso a Serviços Essenciais:** O usuário pode perguntar como realizar serviços comuns (ex: "Como tirar segunda via de conta?"), e o assistente usa o Gemini para fornecer uma explicação passo a passo em linguagem extremamente simples.
3.  **Alerta de Golpes:** O usuário pode colar mensagens suspeitas (SMS, WhatsApp, etc.), e o assistente utiliza o Gemini para analisar a mensagem, informar se parece um golpe, explicar o porquê de forma simples, e dar uma recomendação clara do que fazer.

## Como Executar este Protótipo no Google Colab

1.  **Pré-requisitos:**
    *   Uma conta Google para acessar o Google Colab.
    *   Uma Chave de API do Google Gemini (Google AI Studio).

2.  **Configuração:**
    *   Abra este notebook (`Assistente_Acessibilidade.ipynb`) no Google Colab.
    *   No menu à esquerda do Colab, clique no ícone de uma **chave (🔑) chamado "Secrets"**.
    *   Clique em "+ Adicionar novo secret".
    *   No campo "Nome", digite EXATAMENTE `GOOGLE_API_KEY`.
    *   No campo "Valor", cole a sua Chave de API do Google Gemini.
    *   Marque a caixinha "Acesso ao notebook".

3.  **Execução:**
    *   Execute as células do notebook na ordem, de 1 a 7.
    *   **Célula 1:** Instala a biblioteca do Gemini.
    *   **Célula 2:** Configura a API Key e carrega o modelo Gemini. Verifique se não há erros aqui.
    *   **Célula 3:** Define a função principal de interação com o Gemini.
    *   **Células 4, 5, 6:** Definem as funcionalidades específicas do assistente.
    *   **Célula 7:** Define e (após descomentar a linha `menu_principal()`) executa o menu principal interativo.
    *   Siga as instruções do menu para testar as funcionalidades.

## Tecnologias Utilizadas

*   Python
*   Google Gemini API (através da biblioteca `google-generativeai`)
*   Google Colab (para desenvolvimento e prototipagem)
```    *   **Não se esqueça de substituir `[Seu Nome Aqui - ou seu Nick da Imersão]` pelo seu nome ou identificação.**
