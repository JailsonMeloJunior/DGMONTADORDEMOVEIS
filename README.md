# DG Montador de Móveis - Landing Page Oficial

Projeto importado diretamente do **Google Stitch** para o **Antigravity**.

## 📁 Estrutura de Arquivos

- **[`index.html`](index.html)**: Landing page oficial completa, estilizada com Tailwind CSS, responsiva e com as imagens apontando para os arquivos locais na pasta `assets/`.
- **[`index.stitch.html`](index.stitch.html)**: Cópia original exportada do Stitch (com URLs remotas originais).
- **[`assets/`](assets/)**: Todos os recursos visuais baixados do projeto:
  - `logo.png` / `logo_badge.png`: Logotipos oficiais da marca.
  - `mascot_thumbs_up.png`: Mascote 3D (polegar positivo com fita métrica).
  - `mascot_cabinet.png`: Mascote 3D apoiado no móvel montado.
  - `mascot_drill.png`: Mascote 3D com parafusadeira.
  - `mascot_portrait.png`: Mascote 3D pose de apresentação.
  - `design_vector.svg`: Vetor original do design.
  - `landing_preview.png`: Screenshot completo do projeto gerado no Stitch.
- **[`.agents/mcp_config.json`](.agents/mcp_config.json)**: Configuração de conexão do MCP do Stitch para este workspace.
- **[`.agents/skills/`](.agents/skills/)**: 16 habilidades do Stitch instaladas para o agente.
- **[`.agents/plugins/`](.agents/plugins/)**: Plugins `stitch-design`, `stitch-build` e `stitch-utilities`.

## 🧠 Habilidades do Stitch Instaladas

O repositório oficial [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) foi integrado diretamente ao workspace:

### 🎨 Design (`stitch-design`)
- **`generate-design`**: Criação de novas telas a partir de prompts ou imagens, edição de telas existentes e geração de variantes.
- **`code-to-design`**: Converte código frontend em designs no Stitch.
- **`manage-design-system`**: Gerencia temas e tokens de design no Stitch.
- **`extract-design-md`**: Extrai o arquivo `DESIGN.md` a partir de código-fonte.
- **`extract-static-html`**: Extrai snapshots estáticos e autocontidos de HTML.
- **`upload-to-stitch`**: Envia arquivos locais (HTML, imagens, mockups) para projetos no Stitch.

### 🏗️ Build (`stitch-build`)
- **`react-components`**: Converte telas do Stitch em componentes React modulares com Tailwind.
- **`react-native`**: Converte designs em componentes nativos para React Native.
- **`react-vite-dashboard`**: Transforma telas em dashboards completos com TanStack Query e Vite.
- **`remotion`**: Gera vídeos dinâmicos de apresentação das telas do projeto.
- **`shadcn-ui`**: Integração e customização de componentes shadcn/ui.

### 🛠️ Utilities (`stitch-utilities`)
- **`enhance-prompt`**: Otimiza prompts vagos para geração de alta fidelidade no Stitch.
- **`design-md`**: Analisa projetos do Stitch e gera especificações semânticas em `DESIGN.md`.
- **`taste-design`**: Aplica padrões de design premium e tipografia calibrada.
- **`site-md`**: Cria a constituição do projeto em `SITE.md`.
- **`stitch-loop`**: Loop autônomo para criação iterativa de websites completos.

## 🚀 Como Visualizar

Abra o arquivo [`index.html`](index.html) diretamente no seu navegador, ou inicie um servidor local simples:

```bash
python3 -m http.server 8000
```
Depois acesse `http://localhost:8000` no seu navegador.

