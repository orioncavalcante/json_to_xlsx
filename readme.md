# JSON para Excel - Conversor Online

Uma ferramenta simples, rápida e poderosa para converter arquivos **JSON** em **Excel (.xlsx)** diretamente no navegador.

Não precisa instalar nada. Basta abrir a página, arrastar o arquivo ou selecionar, e o Excel é baixado automaticamente.

## ✨ Funcionalidades

- Suporta **JSONs simples e muito complexos**
- Detecta automaticamente arrays principais (`resultado`, `data`, `items`, etc.)
- Expande arrays de objetos em colunas separadas
- Funciona offline após o primeiro carregamento
- Interface limpa e intuitiva com suporte a drag & drop

## 🚀 Como usar

1. Acesse a ferramenta: **[https://orioncavalcante.github.io/json_to_xlsx/](https://seuusuario.github.io/nome-do-repositorio/)**
2. Arraste seu arquivo `.json` para a área pontilhada **ou** clique no botão para selecionar.
3. O arquivo `.xlsx` será baixado automaticamente com o nome `seuarquivo_convertido.xlsx`.

### Exemplos de JSONs suportados

- Lista de objetos
- `{ "sucesso": true, "resultado": [ ... ] }`
- Objetos com arrays aninhados (`clientes`, `parteContrarias`)
- Objetos profundamente aninhados (`camposDinamicos`)

## 🛠️ Tecnologias utilizadas

- HTML5 + CSS3
- Vanilla JavaScript
- [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs) — via CDN

## 📥 Como rodar localmente

1. Faça o download ou clone o repositório:

   ```bash
   git clone https://github.com/orioncavalcante/nome-do-repositorio.git
   ```

## 📝 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo LICENSE para mais detalhes.
