# Vectrex-quoi-de-neuf
## Intro

Présentation des nouveautés Hardware et Software autour de la console Vectrex

- Première présentation réalisée au festival http://www.replay-festival.com/ #Re-Play #2021
- Deuxième présentation réalisée à la Code Room chez Orange Sophia-Antipolis

## Création de la présentation

``` Shell
# If not present, install Node.js and npm
sudo pacman -S nodejs npm
```

``` Shell
# Install marp command as global
sudo npm install -g @marp-team/marp-cli@latest
```

``` Shell
# Generate the presentation in HTML
npx @marp-team/marp-cli@latest slideshow.md -o slideshow.html
# or
marp slideshow.md

# Generate the presentation in PDF
# Note : Google Chrome, Chromium or Edge MUST be installed first to get advantage of their included PDF support.
npx @marp-team/marp-cli@latest slideshow.md -o slideshow.pdf --allow-local-files
# or
marp slideshow.md --pdf --allow-local-files
```
