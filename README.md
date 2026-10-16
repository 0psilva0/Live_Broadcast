# Separador Futebol V6 — PRISM Android / GitHub Pages

## Correções V6
- Título e faixa superior com prioridade de camada explícita para impedir que efeitos gráficos os ocultem.
- Removidas animações de brilho/piscar, de emblemas e de efeitos 3D pesados para maior estabilidade no WebView Android.
- Movimento de câmara suave de 8 segundos apenas no fundo; informações e emblemas ficam estáveis.
- Relógio digital centrado, sem caixa, acima da mensagem inferior; atualiza a cada segundo.
- Ajustada a posição da barra de estádio/data para dar espaço ao relógio.

## Atualizar o GitHub Pages
1. Substitui `index.html` e `editor.html` na raiz do repositório pelos ficheiros V6.
2. Mantém `config.json` e `logos/` já existentes, se tiveres personalizado os dados.
3. Aguarda a publicação em Settings > Pages.
4. Recarrega o widget Web no PRISM Android para evitar usar a versão antiga em cache. Se necessário, remove e volta a adicionar o widget.

## Utilização
- O URL do GitHub Pages continua igual.
- `editor.html` permite alterar dados e descarregar `config.json` e emblemas para substituir no repositório.
- O site verifica atualizações de `config.json` a cada 15 segundos, mas a cache pode atrasá-las.
- O relógio utiliza a hora local do dispositivo Android.
- Para testar em computador, abre `index.html` com servidor local (por exemplo `python3 -m http.server 8000`).

Nota: o vídeo fornecido mostra a ausência do título e faixa superior e o relógio junto à marca de água PRISM; esta revisão aborda estes problemas no código. O comportamento final no WebView específico do PRISM deve ser confirmado no dispositivo.
