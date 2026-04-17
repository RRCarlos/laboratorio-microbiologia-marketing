# Diseño Landing Page - VeriTest.LAB

## Resumen

Diseño conceptual de la landing page para VeriTest.LAB.

---

## 1. ESTRUCTURA DE LA LANDING

### 1.1 Secciones

```
┌─────────────────────────────────────────────────────┐
│                    HEADER                         │
│  Logo  |  Nav: Servicios |Nosotros|Cliente | Contacto  │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│                    HERO SECTION                   │
│  [Imagen: Laboratorio moderno]                     │
│  "Resultados confiables en 24-48 horas"          │
│  [Botón: Solicitar presupuesto]                   │
│  "Certificación ISO 15189"                    │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│                 SERVICIOS (3 columnas)             │
│  [Análisis] [Molecular] [Consultoría]          │
│   iconos + texto + botón "Más info"              │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│               CERTIFICACIONES                    │
│  ISO 15189  |  BSL-2  |  Mais logos          │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│                 POR QUÉ ELEGIRNOS                │
│  • Tecnología última generación                  │
│  • Resultados en 24-48h                        │
│  • Equipo certificado                           │
│  • Precio competitivo                        │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│              TESTIMONIALES                       │
│  [Foto] "Excelente servicio" - Dr. García       │
│  [Foto] "Rápidos y precisos" - Clínica Norte   │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│                   CTA FINAL                      │
│  "¿Necesita un análisis?"                      │
│  [Botón: Contactar ahora]                        │
└─────────────────────────────────────────────────────┘
┌─────────────────────────────────────────────────────┐
│                    FOOTER                       │
│  Logo | Enlaces | Legal | Contacto | Redes       │
└─────────────────────────────────────────────────────┘
```

---

## 2. DISEÑO VISUAL

### 2.1 Paleta de Colores

| Element | Color | HEX |
|---------|-------|-----|
| **Fondo principal** | Blanco | #FFFFFF |
| **Fondo secundario** | Gris claro | #F8F9FA |
| **Texto principal** | Gris oscuro | #2D3436 |
| **Color primario** | Azul ciencia | #0066CC |
| **Color acento** | Verde vida | #00A36C |
| **Botón CTA** | Azul ciencia | #0066CC |

### 2.2 Tipografía

| Elemento | Fuente | Tamaño |
|----------|--------|--------|
| **H1** | Montserrat Bold | 48px |
| **H2** | Montserrat Bold | 36px |
| **H3** | Montserrat SemiBold | 24px |
| **Cuerpo** | Inter | 16px |
| **Botones** | Inter SemiBold | 16px |

### 2.3 Espaciado

- Sección padding: 80px vertical
- Columnas gap: 32px
- Contenedor max-width: 1200px

---

## 3. CONTenido POR SECCIÓN

### 3.1 Header

```
Logo: VeriTest.LAB (azul #0066CC)
Nav: Servicios | El laboratorio | Nosotros | Cliente | Contacto
```

### 3.2 Hero

```
Título: "Laboratorio de Microbiología de Confianza"
Subtítulo: "Resultados precisos en 24-48 horas. Certificación ISO 15189."
CTA Botón: "Solicitar presupuesto" (#0066CC)
Trust: [ISO 15189] [BSL-2] [Última tecnología]
```

### 3.3 Servicios

| Servicio | Icono | Descripción |
|----------|------|-------------|
| **Análisis clínicos** | 🧫 | Cultivos, identificación, antibiograma |
| **Biología molecular** | 🧬 | PCR, detección de patógenos |
| **Asesoría técnica** | 📋 | Consultoría en bioseguridad |

### 3.4 Por qué elegirnos

| Beneficio | Icono | Descripción |
|-----------|------|-------------|
| **Rapidez** | ⏱️ | Resultados en 24-48 horas |
| **Precisión** | 🎯 | Tecnología de última generación |
| **Certificación** | ✅ | ISO 15189 certificada |
| **Precio** | 💰 | Precios competitivos |

### 3.5 Formulario de Contacto

```
Campos:
- Nombre (req)
- Empresa (opt)
- Email (req)
- Teléfono (req)
- Servicio interés (dropdown)
- Mensaje (textarea)
Botón: "Enviar solicitud"
```

---

## 4. FUNCIONALIDAD

### 4.1 SEO On-Page

| Elemento | Contenido |
|----------|----------|
| **Title** | VeriTest.LAB - Laboratorio Microbiología BSL-2 Certificado |
| **Description** | Laboratorio de microbiología con certificación ISO 15189. Análisis clínicos, biología molecular y consultoría. Resultados en 24-48 horas. |
| **H1** | Laboratorio de Microbiología VeriTest.LAB |

### 4.2 Tracking

- Google Analytics 4
- Google Ads conversion
- LinkedIn Insight Tag

### 4.3 Optimizaciones

- Lazy load imágenes
- Minify CSS/JS
- WebP imágenes
- CDN estática

---

## 5. TECHNICAL Stack

| Componente | Tecnología |
|-----------|-------------|
| **Framework** | Astro o Next.js |
| **Hosting** | Vercel / Netlify |
| **CDN** | Cloudflare |
| **Formularios** | Formspree |
| **Chat** | Tawk.to (opt) |

---

## 6. PRESUPUESTO ESTIMADO

| Componente | Estimación |
|-----------|-------------|
| **Diseño UI** | 2.000-4.000€ |
| **Desarrollo** | 3.000-6.000€ |
| **Hosting año 1** | 300-500€ |
| **Dominio** | 15€/año |
| **Total** | **5.315-10.515€** |

---

## 7. PLAZO DEentrega

| Fase | Duración | Entregable |
|------|----------|-----------|
| Diseño | 1 semana | Mockup Figma |
| Desarrolloo | 2 semanas | Web live |
| Testing | 1 semana | Lanzamiento |

**Total: 4 semanas**

---

*Documento de diseño conceptual para Proyecto VeriTest.LAB*
*Versión 1.0 — Abril 2026*