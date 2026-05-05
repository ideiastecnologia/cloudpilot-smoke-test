# Inventário GeneXus — Bruto

Contagens por tipo extraídas da KB durante a análise estrutural.

| Tipo | Quantidade | Observações |
|------|-----------|-------------|
| FOLDER | 1 |  |
| MODULE | 1 |  |
| DOMAIN | 1 | tipos reutilizáveis |
| TRANSACTION | 1 | entidades de domínio (Levels + Items) |
| TABLE | 1 | objetos físicos derivados de Transactions |
| INDEX | 1 | índices de banco |
| SUBTYPE_GROUP | 1 |  |
| STRUCTURED_DATA_TYPE | 1 |  |
| EXTERNAL_OBJECT | 1 |  |
| PROCEDURE | 1 | lógica de negócio (Source DSL preservado) |
| WEB_PANEL | 1 | telas web (form layout em Source CDATA) |
| THEME_CLASS | 1 | estilos de UI (geralmente derivados de WorkWithPlus) |
| IMAGE | 1 | ícones e imagens embutidas |
| WORK_WITH_PLUS_PATTERN | 1 | patterns generativos |

## Warnings do analyzer

- KB name absent from <KnowledgeBase> header
