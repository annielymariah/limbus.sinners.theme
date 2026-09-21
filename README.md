# Limbus Company Sinners

Tema dark/light para TeamSpeak com efeito de vidro (glassmorphism) e variantes por Sinner, cada uma com o nome e a cor principal do personagem.

Baseado no [Neon Reaper Dark](https://github.com/AnthonyDac/neon-reaper-dark), de AnthonyDac (Valhalla).

## Sinners
- **01 Yi Sang** — Dreamy Grey (`#7b858d`) — dark
- **02 Faust** — Cerebral Pink (`#ebd7db`) — dark + light
- **03 Don Quixote** — Oblivion Yellow (`#ffef23`) — dark
- **04 Ryōshū** — Smoky Scarlet (`#cf0000`) — dark + light
- **05 Meursault** — Decay Blue (`#344152`) — dark
- **06 Hong Lu** — Naïve Cyan (`#5bffde`) — dark + light
- **07 Heathcliff** — Furious Violet (`#4e3076`) — dark + light
- **08 Ishmael** — Isolate Orange (`#ff9500`) — dark + light
- **09 Rodion** — Lusty Burgundy (`#9c1e34`) — dark + light
- **10 Dante** — Inferno Red (`#b01c37`) — dark + light
- **11 Sinclair** — Immature Green (`#8b9c15`) — dark
- **12 Outis** — Militant Olive (`#586940`) — dark
- **13 Gregor** — Verminous Brown (`#754e38`) — dark

> O TeamSpeak limita a **20 temas** por extensão. Por isso o light listado cobre 7 Sinners; os CSS light dos outros 6 (`YiSangLight.css`, etc.) já estão na pasta — basta trocar no `package.json` se quiser.

## Instalar / Usar
1. Baixe o .zip do tema (não clone o repositório direto na pasta de extensões).
2. TeamSpeak → Settings → Appearance → Themes → Importar (ou copie a pasta `limbus.sinners.theme` para `%appdata%\TeamSpeak\Default\extensions`).
3. Reinicie o TeamSpeak se necessário.
4. Na lista, escolha o Sinner (ex: `08 Ishmael` ou `08 Ishmael Light`).

O TeamSpeak recusa a extensão se **qualquer arquivo** passar de 2 MB — inclusive o pack do `.git`. Por isso o install precisa ser o zip/pasta do tema, sem o histórico Git.

## Personalizar
- Cor: abra a variante (ex: `Ishmael.css` / `IshmaelLight.css`) e ajuste `--custom-color-accent-light`, `--custom-color-accent-dark` (e as versões `-t`), `--custom-color-slider1/2`.
- Vidro dark: `Glassmorphism.css` — `--glass-blur`, `--glass-radius`, `--glass-bg`.
- Vidro light: `GlassmorphismLight.css` — mesmos knobs, paleta clara.
- Fonte: a UI usa **Pretendard** (a mesma do Limbus Company), empacotada em `fonts/`.

Notas:
- Se o desfoque (`backdrop-filter`) não for suportado, um fallback sem blur é aplicado automaticamente.
- Em máquinas mais modestas, diminua `--glass-blur` para melhor desempenho.

Licença: MIT.

---

# Limbus Company Sinners (EN)

Dark and light TeamSpeak theme with glassmorphism and one variant per Sinner, each using that character’s name and principal color.

Based on [Neon Reaper Dark](https://github.com/AnthonyDac/neon-reaper-dark) by AnthonyDac (Valhalla).

## Install / Use
1. Download the theme .zip (do not clone the git repo straight into the extensions folder).
2. TeamSpeak → Settings → Appearance → Themes → Import (or copy the `limbus.sinners.theme` folder into `%appdata%\TeamSpeak\Default\extensions`).
3. Restart TeamSpeak if needed.
4. In the list, pick the Sinner you want (e.g. `08 Ishmael` or `08 Ishmael Light`).

TeamSpeak rejects the extension if **any file** is larger than 2 MB — including the `.git` pack. Install the zip/theme folder, not the git history.

TeamSpeak allows **at most 20 themes** per extension, so the listed light set covers 7 Sinners; the other light CSS files are already in the folder if you want to swap them in `package.json`.

## Quick customize
- Color: open the chosen variant (e.g. `Ishmael.css` / `IshmaelLight.css`) and tweak `--custom-color-accent-light`, `--custom-color-accent-dark` (plus `-t` versions), `--custom-color-slider1/2`.
- Glass (dark): `Glassmorphism.css` — `--glass-blur`, `--glass-radius`, `--glass-bg`.
- Glass (light): `GlassmorphismLight.css` — same knobs, light surfaces.
- Font: UI text uses **Pretendard** (Limbus Company’s UI typeface), bundled in `fonts/`.

Notes:
- If `backdrop-filter` isn’t supported, a no-blur fallback is applied automatically.
- On lower-end machines, reduce `--glass-blur` for better performance.

License: MIT.
