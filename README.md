# Meu Presente 💝

Criador gratuito de páginas personalizadas com inspiração em produtos de presentes por QR Code.

## Repositório
https://github.com/gabrieljunio-hash/surpresa-qr

## Modelos disponíveis
- Nossa história: contador de relacionamento, mensagem e fotos.
- Aniversário: cartão com título e mensagem.
- Poster de filme: título, sinopse e fotos.
- Playlist: fotos organizadas como faixas.

## Recursos
- QR Code para cada página.
- Link compartilhável e compartilhamento nativo do celular.
- Download do QR Code em PNG.
- Temas de cores.
- Melodia instrumental sintetizada no navegador.
- Layout responsivo para celular e computador.
- Sem cadastro, login, pagamento ou banco de dados.

## Publicação GitHub Pages
Configurar em Settings → Pages → Deploy from a branch → main → /(root).
URL esperada: https://gabrieljunio-hash.github.io/surpresa-qr/

## Como os dados são compartilhados
Os dados textuais são codificados no fragmento da URL (#presente=...). Não são enviados a um servidor. Qualquer pessoa com o link pode visualizar o presente.

As fotos precisam ser links públicos de imagens. Upload permanente de fotos e armazenamento de páginas exigem backend/armazenamento, não incluídos nesta versão. O campo de música é reservado para evolução; a melodia integrada funciona sem arquivos externos.

## Testes e limitações conhecidas
- Validar mensagem obrigatória e data obrigatória para o modelo de relacionamento.
- Codificação/decodificação JSON em UTF-8 via Base64 URL-safe.
- Verificação de limite de texto (1.800 caracteres).
- Gerar QR Code e baixar PNG.
- Copiar link e compartilhar via Web Share API com fallback.
- Renderizar os quatro modelos e aplicar tema escolhido.
- Contador calculado a partir da data informada.
- Carregar fotos por URLs públicas; imagens inválidas são removidas.
- Melodia Web Audio iniciada por toque do usuário.
- A validação automatizada em navegador real e a publicação HTTP ainda precisam ser confirmadas.
