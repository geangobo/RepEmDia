# RepEmDia Bot (ou o nome que você escolheu)

> 🤖 Um bot para automatizar e organizar o pagamento de aluguel e despesas da República Gato Preto. Chega de "cadê o pix?".

## 🎯 O Problema

Gerenciar os pagamentos de aluguel e da caixinha em uma república pode ser um processo manual e estressante. É fácil perder o controle de quem já pagou, esquecer de cobrar ou ter que conferir comprovante por comprovante no grupo.

## ✨ A Solução

Este projeto utiliza o **Telegram** como interface para que os moradores enviem seus comprovantes de pagamento. Um fluxo de trabalho no **N8N** (ferramenta de automação de código aberto) é ativado, utilizando **IA para ler e validar o comprovante**, registrar o pagamento em uma planilha e notificar a todos que o pagamento foi recebido.

### Principais Funcionalidades
* 📲 **Envio de Comprovantes**: Moradores enviam a foto do comprovante diretamente para o bot no Telegram.
* 🧠 **Validação com IA**: O sistema extrai informações como valor e data para confirmar o pagamento.
* 📊 **Registro Automático**: Atualiza automaticamente uma planilha ou banco de dados com os status dos pagamentos.
* 🔔 **Notificações e Lembretes**: Envia lembretes para quem ainda não pagou e confirmações para quem já acertou as contas.

### 🛠️ Tecnologias Utilizadas
* **Telegram**: Interface com os usuários.
* **N8N**: Orquestração e automação do fluxo de trabalho.
* **[Nome da Ferramenta de IA]**: Para o reconhecimento de texto/imagem (OCR).
* **[Nome do MCP]**: [Explicação do que é e para que serve o MCP].
* **Google Sheets / Notion / Airtable**: Como banco de dados para os pagamentos.
