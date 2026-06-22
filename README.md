# 🌐 Loom Framing — Landing Oficial

Cara pública del producto **Loom Framing** — la app del framero, pa' frameros.
Servida en **[loomframing.com](https://loomframing.com)** vía GitHub Pages.

## Qué es esto

Repo dedicado **solo** a la landing de marketing (español, mobile-first, voz canon).
Separado a propósito de:

- 🔒 `Loom-Framing-App` (privado) — la app Flutter + todo el dev.
- 🌍 `jezblade.github.io` (público) — portafolio / cara del Ultimate Plan.

Un producto con dominio propio merece su propia casa: historial, deploy y dominio
aislados. Sigue el patrón polyrepo del Ultimate Plan (cada concern, su repo).

## Estructura

```
index.html        # la landing
assets/           # imágenes (feature graphic, screenshots, founder, icon)
blog/             # blog del framero
CNAME             # loomframing.com (GitHub Pages custom domain)
```

## Deploy

GitHub Pages sirve la rama `main` (raíz). El dominio `loomframing.com` apunta acá
vía DNS en Cloudflare. Editar la landing = commit + push → deploy automático.

---

_Brotherhood Seal: 015cb320 · Part of Ultimate Plan_
