# DG Montador de Móveis — Design System

## 1. Brand Identity & Personality
- **Voice**: Confiável, ágil, técnico, amigável e focado em excelência ("Sem peças sobrando, sem riscos no chão").
- **Mascote 3D**: DG em estilo Pixar/Disney 3D, vestindo camisa laranja, boné azul e fita métrica/parafusadeira.

## 2. Color Palette
- **Background**: `#00161f` (Dark Petrol / Deep Navy)
- **Surface**: `#00161f`
- **Surface Container**: `#08222d`
- **Surface Container High**: `#142d38`
- **Surface Container Highest**: `#203843`
- **Surface Container Low**: `#041e29`
- **Surface Container Lowest**: `#001018`
- **Surface Bright**: `#243c48`
- **Primary (Accent)**: `#ffb693`
- **Primary Container (Hero CTA)**: `#ff6b00` (Laranja Vibrante)
- **Secondary**: `#b6cad3`
- **Tertiary (Highlights / Badges)**: `#00daf3` / `#00a8bb` (Ciano Elétrico)
- **Text On Surface**: `#cde6f5` (Branco azulado de alto contraste)
- **Text On Surface Variant**: `#e2bfb0`

## 3. Typography
- **Headings & Hero**: `Syne`, sans-serif (Weights: 700, 800)
- **Body, UI & Buttons**: `Plus Jakarta Sans`, sans-serif (Weights: 400, 500, 700, 800)
- **Icons**: Google Material Symbols Outlined

## 4. UI Components & Surfaces
- **Radius**: `rounded-full` para botões e pílulas de navegação, `rounded-3xl` (24px - 32px) para cards e contêineres principais.
- **Glassmorphism**: `backdrop-blur-xl bg-surface-container/90 border border-surface-container-highest/60`
- **Shadows**: Elevadas com tonalidade fria `shadow-[0_12px_36px_rgba(0,16,24,0.6)]`

## 5. Design System Notes for Stitch Generation (Required for Prompts)
```markdown
**DESIGN SYSTEM (REQUIRED):**
- Platform: Web, Mobile-friendly & Desktop-ready
- Theme: Dark Theme with High-Contrast Accents
- Background: Dark Petrol Navy (#00161f)
- Surface Cards: Deep Navy Blue (#08222d, #142d38) with subtle border (#203843)
- Primary CTA: Safety Orange (#ff6b00) with bold white/dark typography
- Accent Highlights: Electric Cyan (#00daf3) for badges and verified indicators
- Typography: 'Syne' for bold titles and display headlines; 'Plus Jakarta Sans' for clean, readable body copy and buttons
- Mascot: Friendly Brazilian 3D cartoon assembler with orange shirt and blue cap
```
