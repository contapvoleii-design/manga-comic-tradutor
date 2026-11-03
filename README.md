# Manga & Comic Tradutor

Aplicativo web para importar páginas de mangá, reconhecer texto com OCR, traduzir para português do Brasil e exportar imagens.

## Recursos
- Importar várias imagens PNG, JPG ou WEBP.
- Tentar carregar imagens de um capítulo por URL.
- OCR no navegador com Tesseract.js.
- Tradução automática por serviço público de demonstração.
- Processar páginas em sequência e baixar resultados em ZIP.
- Botão de próximo capítulo quando o leitor externo expõe um link identificável.

## Publicar no GitHub Pages
1. Abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch **main** e a pasta **/(root)** e salve.
4. Aguarde a publicação e abra a URL do GitHub Pages.

## Limitações importantes
- Um site externo pode bloquear a leitura automática por CORS, proteção anti-bot, login ou regras próprias. Por isso, a busca por URL é uma tentativa e não funciona em todos os leitores.
- O aplicativo é estático (GitHub Pages), então não consegue contornar essas proteções. Se o link falhar, baixe as páginas legalmente e importe várias imagens de uma vez.
- OCR e tradução dependem de bibliotecas e serviços externos; a tradução pública pode ficar indisponível ou limitar requisições.
- A tradução é apresentada como legenda sobre a imagem exportada; ela não apaga nem substitui automaticamente as letras originais dentro dos balões.
- Revise o texto reconhecido e a tradução antes de compartilhar.

## Privacidade
As imagens selecionadas são processadas no navegador. Ao usar tradução ou importação por URL, partes do conteúdo são enviadas aos serviços externos correspondentes.

Projeto independente para leitura e estudo de mangás e quadrinhos.
