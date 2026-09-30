MI IA CREADORA V5 — MÓVIL
==========================
V5 elimina el server.js de la V4.

IMPORTANTE: Pollinations documenta que las claves sk_ son para servidor. Para una app de navegador recomienda BYOP / Connect User Wallets: una App Key pk_ identifica la app y el usuario autoriza su propia cuenta. La V5 implementa OAuth + PKCE y guarda el token solo en sessionStorage.

USO:
1. Publica index.html en cualquier alojamiento web estático HTTPS.
2. Abre la URL en tu celular.
3. En enter.pollinations.ai/keys crea una App Key (pk_...) y registra como Redirect URI EXACTAMENTE la URL de V5.
4. Copia pk_ en V5 y pulsa CONECTAR MI POLLINATIONS.
5. Autoriza tu cuenta.
6. Pulsa GENERAR VIDEO COMPLETO.

No abras index.html como file:// porque OAuth necesita una URL web.
OpenRouter es opcional.
El video se genera localmente en el navegador y se descarga como WEBM.

Docs oficiales:
https://gen.pollinations.ai/docs
https://openrouter.ai/developers
