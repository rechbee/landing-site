# Fontes — Wordmark RechBee

O wordmark "RECHBEE" usa a fonte **TAN Meringue** (peso 400, regular).

## Como instalar

1. Coloque o arquivo original da fonte nesta pasta:
   - `/fonts/TAN-Meringue.woff2`
2. O `@font-face` já está declarado em `css/style.css`:

```css
@font-face {
  font-family: "TAN Meringue";
  src: url("/fonts/TAN-Meringue.woff2") format("woff2");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```

3. Recarregue a página (se preciso, limpe o cache).

## Enquanto a fonte não for adicionada

Sem o arquivo, o wordmark cai no fallback genérico `Georgia, serif`.
Nenhuma substituta serifada (Fraunces, Cormorant, Playfair etc.) é usada
no lugar da TAN Meringue.

## Observações

- Não aplicar peso artificial na fonte.
- Não usar `text-transform` sobre o desenho.
- Letter-spacing limitado a `0.01em`.