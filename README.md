# Creador de Perfil Claude · Trinitas Studio

Herramienta pública para armar el texto del perfil de Claude (claude.ai → Configuración → Perfil) a partir de un formulario guiado.

- **URL:** https://creaperfil.trinitasstudio.com
- **Tipo:** página estática (un solo `index.html`, sin backend ni dependencias).
- **Datos:** lo que escribe el usuario se guarda solo en su navegador (`localStorage`); nada se envía a ningún servidor.
- **Deploy:** Vercel, desde la rama `main`. Cada push publica una versión nueva.
- **Dominio:** CNAME `creaperfil` → `cname.vercel-dns.com` en Cloudflare (DNS only).

## Estructura del perfil generado

1. Sobre mí
2. Mi asistente de IA (tono, formato, longitud, idioma)
3. Cómo trabajar conmigo (reglas duras)
4. Cuando trabajes con mis archivos (daños, orden, versiones, ritmo)

## Marca

Paleta y tipografía del brand book v2 de Trinitas Studio: Fortnum green `#0B3B2E`, gold `#C9A227`, parchment `#F4F1E8`, near black green `#0C1512`; Archivo, Hanken Grotesk y JetBrains Mono.

---
Trinitas Studio · trinitasstudio.com
