# Roteirização de OS — Amigos Soluções

Aplicação web para cadastro, gerenciamento e visualização geográfica de Ordens de Serviço (GLP) no mapa.

## Funcionalidades

- **Cadastro Individual e em Lote:** Lançamento manual de OSs ou importação rápida via lista JSON.
- **Mapa Interativo:** Visualização das rotas com marcadores coloridos conforme o status de atendimento.
- **Gestão de Ordens:** Filtros por número da OS, código do cliente, cidade e status, além de edição direta de status e data de atendimento.
- **Ações em Massa e Relatórios:** Seleção múltipla para exclusão e exportação da tabela completa em PDF (formato A4).
- **Armazenamento Local:** Os dados ficam salvos diretamente no navegador (`localStorage`), sem necessidade de servidor.

## Como usar

1. Baixe o arquivo `index.html`.
2. Abra o arquivo em qualquer navegador moderno (Chrome, Edge, Safari).

## Tecnologias

- HTML5, CSS3 e JavaScript
- [Leaflet](https://leafletjs.com/) (Mapa interativo)
- [jsPDF](https://github.com/parallax/jsPDF) (Geração de PDF)
- Nominatim / OpenStreetMap (Geocodificação de cidades)