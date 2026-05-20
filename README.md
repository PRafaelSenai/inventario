# 📦 Inventário de Equipamentos — SENAI DR-SP

Sistema de inventário de equipamentos e mobiliário, com leitura de QR code por câmera, importação de planilhas e sincronização com Google Sheets.

## Funcionalidades

- 📷 **Leitura QR Code** — câmera do celular/webcam com parser inteligente
- 🧠 **Auto-preenchimento** — extrai patrimônio, descrição, sala, tipo direto do QR
- 📊 **Importar planilha** — CSV e Excel (.xlsx) com detecção automática de colunas
- ☁️ **Google Sheets** — armazenamento permanente via Apps Script
- 📄 **Relatório PDF** — exportação formatada com logo SENAI
- 🔍 **Busca e filtros** — pesquisa por patrimônio, sala, responsável
- ✏️ **Edição inline** — editar e remover itens sem recarregar

## Como usar

1. Acesse via GitHub Pages: `https://SEU-USUARIO.github.io/Inventario/`
2. Ative a câmera e aponte para as etiquetas QR
3. Confirme os dados e salve

## Google Sheets (opcional)

1. Crie uma planilha no Google Sheets
2. Vá em **Extensões > Apps Script**
3. Cole o código (disponível dentro do app, ícone ☁️)
4. Implante como **App da Web** com acesso **Qualquer pessoa**
5. Cole a URL no app

## Tecnologias

- HTML5 + CSS3 + JavaScript (arquivo único, sem build)
- [jsQR](https://github.com/niceness/jsqr) — decodificação QR
- [jsPDF](https://github.com/parallax/jsPDF) — geração de PDF
- [SheetJS](https://sheetjs.com/) — leitura de Excel
- Google Apps Script — backend para Google Sheets
