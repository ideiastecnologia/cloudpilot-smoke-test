# Inventário GeneXus — Bruto

Contagens por tipo extraídas da KB durante a análise estrutural.

| Tipo | Quantidade | Observações |
|------|-----------|-------------|
| FOLDER | 10 |  |
| MODULE | 128 |  |
| DOMAIN | 376 | tipos reutilizáveis |
| TRANSACTION | 159 | entidades de domínio (Levels + Items) |
| TABLE | 158 | objetos físicos derivados de Transactions |
| INDEX | 168 | índices de banco |
| SUBTYPE_GROUP | 112 |  |
| STRUCTURED_DATA_TYPE | 263 |  |
| EXTERNAL_OBJECT | 238 |  |
| PROCEDURE | 844 | lógica de negócio (Source DSL preservado) |
| WEB_PANEL | 589 | telas web (form layout em Source CDATA) |
| THEME_CLASS | 1446 | estilos de UI (geralmente derivados de WorkWithPlus) |
| IMAGE | 250 | ícones e imagens embutidas |
| WORK_WITH_PLUS_PATTERN | 281 | patterns generativos |
| UNKNOWN | 495 |  |
| UNKNOWN | 1 | guid prefix `c84ec0ea` |
| UNKNOWN | 82 | guid prefix `083f1b21` |
| UNKNOWN | 10 | guid prefix `78b3fa0e` |
| UNKNOWN | 21 | guid prefix `2a9e9aba` |
| UNKNOWN | 2 | guid prefix `bf08dfb1` |
| UNKNOWN | 78 | guid prefix `ffd44be7` |
| UNKNOWN | 4 | guid prefix `624a8b31` |
| UNKNOWN | 4 | guid prefix `ecececec` |
| UNKNOWN | 1 | guid prefix `faeb588c` |
| UNKNOWN | 21 | guid prefix `19abc6ff` |
| UNKNOWN | 135 | guid prefix `5592de59` |
| UNKNOWN | 3 | guid prefix `88313f43` |
| UNKNOWN | 3 | guid prefix `dcdcdcdc` |
| UNKNOWN | 21 | guid prefix `562f4793` |
| UNKNOWN | 3 | guid prefix `83476c1e` |
| UNKNOWN | 51 | guid prefix `c88fffcd` |
| UNKNOWN | 7 | guid prefix `c804fdbd` |
| UNKNOWN | 6 | guid prefix `78cecefe` |
| UNKNOWN | 1 | guid prefix `36e32e2d` |
| UNKNOWN | 4 | guid prefix `3affc0b3` |
| UNKNOWN | 37 | guid prefix `1132ac08` |

## Warnings do analyzer

- High UNKNOWN guid count: 5592de59 → 135 objects (consider mapping)
