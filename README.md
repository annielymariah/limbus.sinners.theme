# Limbus Company Sinners

Tema escuro para TeamSpeak com efeito de vidro (glassmorphism) e uma variante por Sinner, cada uma com o nome e a cor principal do personagem.

Baseado no [Neon Reaper Dark](https://github.com/AnthonyDac/neon-reaper-dark), de AnthonyDac (Valhalla).

## Sinners
- **01 Yi Sang** — Dreamy Grey (`#7b858d`)
- **02 Faust** — Cerebral Pink (`#ebd7db`)
- **03 Don Quixote** — Oblivion Yellow (`#ffef23`)
- **04 Ryōshū** — Smoky Scarlet (`#cf0000`)
- **05 Meursault** — Decay Blue (`#344152`)
- **06 Hong Lu** — Naïve Cyan (`#5bffde`)
- **07 Heathcliff** — Furious Violet (`#4e3076`)
- **08 Ishmael** — Isolate Orange (`#ff9500`)
- **09 Rodion** — Lusty Burgundy (`#9c1e34`)
- **10 Dante** — Inferno Red (`#b01c37`)
- **11 Sinclair** — Immature Green (`#8b9c15`)
- **12 Outis** — Militant Olive (`#586940`)
- **13 Gregor** — Verminous Brown (`#754e38`)

## Instalar / Usar
1. Baixe o .zip do tema (não clone o repositório direto na pasta de extensões).
2. TeamSpeak → Settings → Appearance → Themes → Importar (ou copie a pasta `limbus.sinners.theme` para `%appdata%\TeamSpeak\Default\extensions`).
3. Reinicie o TeamSpeak se necessário.
4. Na lista, escolha o Sinner desejado (ex: "08 Ishmael").

O TeamSpeak recusa a extensão se **qualquer arquivo** passar de 2 MB — inclusive o pack do `.git`. Por isso o install precisa ser o zip/pasta do tema, sem o histórico Git.

## Personalizar
- Cor: abra a variante (ex: `Ishmael.css`) e ajuste `--custom-color-accent-light`, `--custom-color-accent-dark` (e as versões `-t`), `--custom-color-slider1/2`.
- Vidro: em `Glassmorphism.css`, ajuste `--glass-blur` (desfoque), `--glass-radius` (arredondamento), `--glass-bg` (transparência).
- Fonte: a UI usa **Pretendard** (a mesma do Limbus Company), empacotada em `fonts/`.

Notas:
- Se o desfoque (`backdrop-filter`) não for suportado, um fallback sem blur é aplicado automaticamente.
- Em máquinas mais modestas, diminua `--glass-blur` para melhor desempenho.

Licença: MIT.

---

# Limbus Company Sinners (EN)

Dark TeamSpeak theme with a glassmorphism effect and one variant per Sinner, each using that character’s name and principal color.

Based on [Neon Reaper Dark](https://github.com/AnthonyDac/neon-reaper-dark) by AnthonyDac (Valhalla).

## Install / Use
1. Download the theme .zip (do not clone the git repo straight into the extensions folder).
2. TeamSpeak → Settings → Appearance → Themes → Import (or copy the `limbus.sinners.theme` folder into `%appdata%\TeamSpeak\Default\extensions`).
3. Restart TeamSpeak if needed.
4. In the list, pick the Sinner you want (e.g. "08 Ishmael").

TeamSpeak rejects the extension if **any file** is larger than 2 MB — including the `.git` pack. Install the zip/theme folder, not the git history.

## Quick customize
- Color: open the chosen variant (e.g. `Ishmael.css`) and tweak `--custom-color-accent-light`, `--custom-color-accent-dark` (plus `-t` versions), `--custom-color-slider1/2`.
- Glass: in `Glassmorphism.css`, adjust `--glass-blur` (blur), `--glass-radius` (roundness), `--glass-bg` (transparency).
- Font: UI text uses **Pretendard** (Limbus Company’s UI typeface), bundled in `fonts/`.

Notes:
- If `backdrop-filter` isn’t supported, a no-blur fallback is applied automatically.
- On lower-end machines, reduce `--glass-blur` for better performance.

License: MIT.
