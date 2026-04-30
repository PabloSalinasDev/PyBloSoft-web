# Landing Page — Shanbit

Página de marketing de **Shanbit**, el generador de contraseñas offline de PyBloSoft. Existe en dos versiones:

| Versión | URL canónica | Búsquedas objetivo |
|---|---|---|
| Español | `https://pyblosoft.com/es/` | *"generador de contraseñas seguras"*, *"generador de claves"* |
| Inglés | `https://pyblosoft.com/` | *"random password generator"*, *"strong password generator"*, *"passphrase generator"*, *"offline password generator"* |

<p align="center">
    <a href="https://pyblosoft.com/" target="_blank">
    <img src="https://img.shields.io/badge/Ver%20sitio-pyblosoft.com-0ea5e9?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Ver sitio">
    </a>
</p>

---

## Estructura de la página

La página está dividida en 3 zonas con objetivos distintos:

**Zona 1 — Conversión (30%)**  
Para usuarios ya convencidos. CTA directo a Microsoft Store, bloque AEO de respuesta rápida (¿Qué es Shanbit?) y tabla comparativa Shanbit vs. herramientas online gratuitas.

**Zona 2 — Autoridad (50%)**  
Para escépticos. Explicación técnica de entropía de Shannon con fórmula y tabla, detalle de cada feature (CSPRNG, Diceware, QR offline, RAM-only), capturas de pantalla de la app y sección FAQ.

**Zona 3 — Cierre persuasivo (20%)**  
Para indecisos. Bloque de diferenciación con cita, segundo CTA a Microsoft Store.

---

## Decisiones SEO

- **Keywords principales:**
  - ES: `generador de contraseñas seguras`, `generador de claves` — repetidas en H1, H2, H3, meta description, alt texts y schema.
  - EN: `random password generator`, `strong password generator`, `passphrase generator`, `offline password generator` — misma estrategia de repetición.
- **Schema markup:** `SoftwareApplication`, `Organization`, `HowTo`, `FAQPage`, `BreadcrumbList`.
- **AEO (Answer Engine Optimization):** bloque "¿Qué es Shanbit?" y FAQ diseñados para respuestas directas en buscadores con IA.
- **Hreflang:** `en` / `es` / `x-default` configurados para versión bilingüe.
- **GTM:** se carga al primer `scroll` del usuario para no bloquear LCP.
- **Canonical:** apunta a `/es/` para evitar duplicados.

---

## Stack

- HTML + Tailwind CSS (clases estáticas via `style.css` externo)
- Sin JS propio en la página — solo GTM y JSON-LD
- Sin framework

---

## Archivos relacionados

```
/index.html          ← versión EN
/es/index.html       ← versión ES
/assets/style.css    ← estilos compartidos (variables CSS custom)
/assets/*.png        ← capturas de la app y logo
/privacy.html        ← política de privacidad
```

---

## Contacto

support@pyblosoft.com