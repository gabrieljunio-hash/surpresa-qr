# Surpresa em um Envelope 💌

Aplicação estática, gratuita e sem cadastro, hospedada no GitHub Pages.

## Publicação

- URL: https://gabrieljunio-hash.github.io/surpresa/
- Arquivo principal: `surpresa/index.html`
- Não utiliza servidor, banco de dados ou login.

## Como funciona

1. A pessoa preenche destinatário, remetente e mensagem.
2. O navegador codifica os dados no fragmento (`#surpresa=...`) do próprio link.
3. O QR Code aponta para esse link.
4. Ao abrir, a página mostra o envelope; o toque abre a carta e inicia uma melodia sintetizada no navegador.

## Privacidade e limitações

- Não há envio de mensagens para um banco de dados.
- Quem tiver o link ou QR Code poderá ler a mensagem. Não use para dados confidenciais.
- A mensagem é carregada a partir do próprio link; apagar o histórico do navegador não apaga cópias que já foram compartilhadas.
- A geração do QR Code usa a biblioteca QRCode.js via CDN, portanto exige conexão com a internet.
- A música é gerada localmente pela Web Audio API e depende de interação do usuário para começar.
- O GitHub Pages hospeda apenas os arquivos estáticos. Não há painel para editar ou apagar links já distribuídos.

## Testes de código

A estrutura foi verificada no repositório: formulário, limite de mensagem, codificação/decodificação do link, QR Code, abertura por toque/teclado, controles de música e compartilhamento/download. A validação visual em aparelhos e a confirmação HTTP da publicação ainda precisam ser feitas.
