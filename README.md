# Rede Brasileira de Telessaúde

Mapa interativo Leaflet para visualização dos Núcleos de Telessaúde e dos municípios atendidos.

## Como publicar no GitHub Pages

1. Faça upload de todos os arquivos desta pasta para o repositório.
2. No GitHub, acesse **Settings → Pages**.
3. Em **Build and deployment**, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Clique em **Save**.
5. O mapa ficará disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Arquivo principal

O GitHub Pages abrirá automaticamente:

```text
index.html
```

## Estrutura

```text
index.html
css/style.css
js/mapa.js
data/estados.geojson
data/municipios.geojson
data/nucleos.json
data/vinculos.json
img/sus.svg
```

Elaboração: DESD/SEIDIGI/MS.
