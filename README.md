# Separador Futebol — PRISM Android / GitHub Pages

## Publicação inicial
1. Cria um repositório GitHub público, por exemplo `futebol-live`.
2. Carrega **o conteúdo desta pasta** para a raiz do repositório: `index.html`, `config.json`, `editor.html` e a pasta `logos/`.
3. Em Settings → Pages, seleciona Deploy from a branch, `main`, pasta `/ (root)` e guarda.
4. Aguarda a publicação. O endereço será semelhante a `https://UTILIZADOR.github.io/futebol-live/`.
5. No PRISM Live Studio Android, adiciona um widget Web com esse endereço, se essa opção estiver disponível na tua versão.

## Atualizar para o próximo jogo
1. Abre `editor.html` no teu navegador, altera os campos e carrega novos emblemas.
2. Clica **Descarregar config.json** e **Descarregar emblema casa.png / visitante.png**.
3. No GitHub, substitui `config.json`, `logos/casa.png` e `logos/visitante.png` pelos novos ficheiros (mantém exatamente estes nomes).
4. Após a publicação, o separador tenta obter novas configurações a cada 15 segundos. A cache do GitHub Pages ou do PRISM pode atrasar a atualização; nesse caso recarrega o widget.

## Notas
- Os emblemas usam uma caixa responsiva e `object-fit: contain`, sem distorção.
- O relógio usa a hora do dispositivo Android, em formato 24h. Confirma o fuso horário no dispositivo.
- O loop visual continua a ser feito em CSS, com período de 8 segundos. O relógio avança independentemente.
- O editor é local: não envia ficheiros para o GitHub automaticamente.
- GitHub Pages publica ficheiros publicamente; não coloques dados privados no repositório.
- É necessária ligação à Internet para carregar o site no PRISM Android.
