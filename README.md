# Separador Futebol V7 — TV Broadcast / PRISM Android

## Melhorias
- Emblemas maiores, elevados e distribuídos horizontalmente na zona central-superior.
- Título ligeiramente reduzido para melhorar a hierarquia visual.
- Cenário com mais profundidade por camadas e movimento de câmara muito suave (8 segundos); os textos, emblemas e relógio não piscam nem se deslocam.
- Barra informativa e relógio mantidos em baixo; relógio centrado, sem caixa, acima da mensagem.
- Área inferior direita com menos elementos gráficos, para evitar conflito com a marca de água PRISM Live (que pertence à aplicação e não pode ser removida pelo HTML).

## Publicação
1. Substituir apenas `index.html` e `editor.html` no repositório GitHub Pages.
2. **Não substituir** o `config.json` nem a pasta `logos/` se já tiveres personalizado as equipas.
3. Esperar que GitHub Actions conclua o Pages deployment.
4. Testar `https://0psilva0.github.io/Live_Broadcast/?v=7` no navegador.
5. No PRISM Android, atualizar o URL do widget Web para esse endereço ou recriar o widget.

O editor continua a permitir descarregar `config.json` e os emblemas. O relógio mostra a hora local do dispositivo.

Nota: a apresentação final e a fluidez no WebView do PRISM devem ser confirmadas com uma gravação do dispositivo.
