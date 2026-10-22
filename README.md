# Display Demo · veřejný náhled HTML GUI

Toto je **veřejný repozitář určený pouze k publikaci bezpečné demonstrační verze** domácího HTML panelu.

- Soukromý zdrojový projekt: `kudykam/home-panel-esp32`, pracovní větev `feat/smart-home-panel-ui`.
- Veřejně publikovat výhradně **sestavený statický demo build** bez skutečných domácích dat, půdorysů, IP adres, přihlašovacích údajů, tokenů, fotografií domu, kamerových streamů a možnosti reálného ovládání Loxone.
- Publikování má probíhat do větve `gh-pages` z GitHub Actions soukromého zdrojového projektu; nikdy nepublikovat celý zdrojový repozitář.
- GitHub Pages nastavit na **Settings → Pages → Deploy from a branch → gh-pages → / (root)** až poté, co vznikne publikační větev.
- Budoucí adresa po úspěšném nasazení: `https://kudykam.github.io/Display-demo-/` (zatím není ověřená jako živá).

## Propojení repozitářů

Ve **zdrojovém soukromém repozitáři** se použije GitHub Actions secret `DISPLAY_DEMO_TOKEN`. Obsahuje fine-grained personal access token s oprávněním **Contents: Read and write** pouze pro `kudykam/Display-demo-`, bez přístupu k dalším repozitářům. **Token nikdy neposílat do chatu** a nevkládat do souborů.

Publikační workflow je samostatný návrh v privátním projektu a musí se před spuštěním schválit / sloučit do pracovní větve UI.

**Stav:** cílový veřejný repozitář připraven, skutečné HTML GUI dosud nezveřejněné.
