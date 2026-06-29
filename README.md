# Catálogo de Meias

Site de catálogo online para revenda de meias com pedidos via WhatsApp, desenvolvido em PHP, HTML5 e CSS3.

## Arquivos principais

| Arquivo | Função |
|---|---|
| `index.php` | HTML da página |
| `dados.php` | Lê os CSVs e monta os produtos |
| `style.css` | Visual e cores |
| `filtros.js` | Filtros e busca |
| `estoque.csv` | Exportado da aba Estoque |
| `base_nf.csv` | Exportado da aba Base NF (preços) |
| `img/` | Fotos das meias |

## Como atualizar

- **Estoque/produtos** → subir novo `estoque.csv`
- **Preços** → subir novo `base_nf.csv`
- **Fotos** → subir `.png` na pasta `img/`

## Nome das imagens

Minúsculas, sem acentos, hífens no lugar de espaços.
Ex: `Meia Time Brasil` → `meia-time-brasil.png`

## Coleção Copa

Detectada automaticamente por palavras no nome: `brasil`, `time`, `golaco`, `torcida`, `hexa`, `futebol`, `copa`, `selecao`.
