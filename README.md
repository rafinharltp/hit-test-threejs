# hit-test-threejs

Projeto de exemplo para Hit Test (WebXR) com fallback Raycasting (Three.js).
Usuário sugerido: rafinharltp — Repositório recomendado: hit-test-threejs

## Como usar localmente

1. Sirva via servidor local (recomendado):
   - `python -m http.server 8000`
   - ou `npx serve`

2. Abra `http://localhost:8000/` no navegador.

## Publicar no GitHub Pages

1. Crie repositório público `hit-test-threejs`.
2. Coloque os arquivos (index.html, ar.html, nonar.html, rato_triangle.gltf, README.md, .nojekyll).
3. Push para `main`.
4. Habilite Pages em Settings → Pages → Source: `main` / root.

URL: `https://rafinharltp.github.io/hit-test-threejs/`

## Notas

- WebXR AR funciona apenas em dispositivos compatíveis (Android + Chrome com ARCore).
- Em desktop, use o fallback (nonar.html).
