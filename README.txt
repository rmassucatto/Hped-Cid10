HPed CID10 — Pacote PWA Completo
==================================

Este pacote contém tudo pronto para publicar no GitHub Pages e instalar no celular:

- index.html  (SEU arquivo ajustado com PWA)
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

Como usar
---------
1) No repositório, clique em: Add file → Upload files
2) Envie TODOS estes arquivos para a RAIZ do repositório.
3) Em Settings → Pages, confirme: Branch = main, Folder = / (root)
4) Abra o link do GitHub Pages no celular e instale o app (menu ⋮ → Adicionar à tela inicial).

Observações
-----------
- Se tiver arquivos essenciais extras (ex.: CSV com a base CID), adicione o caminho na lista OFFLINE do service-worker.js.
- Caso mude o nome do repositório (portanto a URL), os dados locais não migram automaticamente: exporte/importa a base para transferir.
