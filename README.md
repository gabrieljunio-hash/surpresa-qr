# Meu Presente 💝

Criador gratuito de páginas especiais compartilhadas por link e QR Code. Projeto estático, sem cadastro, login ou pagamento.

## Modelos
- **Nossa história:** contador de relacionamento, fotos e linha do tempo.
- **Aniversário:** cartão com bolo, botão para apagar as velinhas e confetes.
- **Poster de filme:** composição cinematográfica com sinopse.
- **Playlist:** lista de faixas com player para links diretos de áudio.
- **Pedido de namoro:** pergunta especial com interação.
- **Pedido de casamento:** modelo próprio para o pedido.
- **Declaração:** carta personalizada.
- **Convite digital:** data, horário e local.

## Editor e recursos
- Pré-visualização que acompanha as alterações.
- Temas de cores, fontes e animações.
- Até quatro fotos por links públicos.
- Link direto para vídeo e áudio.
- Linha do tempo e mensagem surpresa revelável.
- QR Code com cor personalizável, compartilhamento e download PNG.
- Layout adaptado para celular e computador.

## Publicação
Repositório: https://github.com/gabrieljunio-hash/surpresa-qr

Configuração do GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root).

URL esperada: https://gabrieljunio-hash.github.io/surpresa-qr/

## Como os dados funcionam
O conteúdo textual e os links são codificados no fragmento da URL (`#presente=...`). Não são enviados a um servidor. Qualquer pessoa com o link pode visualizar o presente.

**Limitação de arquivos:** fotos, vídeos e áudios selecionados diretamente do aparelho são usados apenas na prévia local. Para que a outra pessoa veja/ouça, use URLs públicas diretas. O site não hospeda arquivos e não possui banco de dados. Links de plataformas como YouTube e Spotify não funcionam como arquivos de áudio no player direto.

## Verificações realizadas
- JavaScript analisado sem erro de sintaxe.
- Verificação estrutural dos oito modelos, editor, uploads locais para prévia, mídia, linha do tempo, surpresa, QR personalizado, responsividade e compartilhamento.
- Ainda é necessário testar em navegador real (celular e computador) e confirmar o endereço público do GitHub Pages.