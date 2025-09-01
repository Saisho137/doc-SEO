# Guía Completa de SEO 2025

## Tabla de Contenidos

### I Fundamentos Teóricos

- [¿Qué es SEO?](#qué-es-seo)
- [Importancia del SEO en 2025](#importancia-del-seo-en-2025)
- [Tipos de SEO](#tipos-de-seo)

### II Cómo Funciona Google

- [El Proceso de Tres Etapas](#el-proceso-de-tres-etapas)
  - [Crawling (Rastreo)](#1-crawling-rastreo-️)
  - [Indexing (Indexación)](#2-indexing-indexación-)
  - [Ranking (Clasificación)](#3-ranking-clasificación-)
- [Conceptos Clave para SEO](#conceptos-clave-para-seo)
- [Implicaciones para SEO](#implicaciones-para-seo)

### III Core Web Vitals

- [¿Qué Son las Core Web Vitals?](#qué-son-las-core-web-vitals)
- [Métricas Actuales (2025)](#métricas-actuales-2025)
  - [LCP - Largest Contentful Paint](#1-lcp---largest-contentful-paint-)
  - [INP - Interaction to Next Paint](#2-inp---interaction-to-next-paint-️)
  - [CLS - Cumulative Layout Shift](#3-cls---cumulative-layout-shift-)
- [Cómo Mejorar Cada Métrica](#cómo-mejorar-cada-métrica)
- [Medición de Core Web Vitals](#medición-de-core-web-vitals)

### IV Elementos Técnicos SEO

- [robots.txt - Control de Rastreo](#robotstxt---control-de-rastreo)
- [manifest.json - Progressive Web App](#manifestjson---progressive-web-app)
- [Sitemap XML - Indexación Eficiente](#sitemap-xml---indexación-eficiente)
- [noIndex y noFollow - Control de Indexación](#noindex-y-nofollow---control-de-indexación)
- [URLs Canónicas - Contenido Duplicado](#urls-canónicas---contenido-duplicado)
- [Schema.org / JSON-LD - Datos Estructurados](#schemaorg--json-ld---datos-estructurados)
- [Open Graph - Redes Sociales](#open-graph---redes-sociales)
- [Meta Tags Esenciales](#meta-tags-esenciales)
- [HTML Semántico](#html-semántico)

### V Checklist SEO

- [Core Web Vitals Optimizados](#core-web-vitals-optimizados)
- [HTTPS y Seguridad](#https-implementado-correctamente)
- [Mobile-First Design](#mobile-first-design-responsive)
- [Elementos Técnicos Verificados](#sitemap-xml-generado-y-actualizado)

### VI Conclusión

- [Factores Clave 2025](#vi-conclusión)
- [Recursos y Referencias](#recursos-y-referencias)

---

## I. Fundamentos Teóricos

> **📚 Conceptos Fundamentales** - Comprende los pilares básicos del SEO moderno antes de adentrarte en técnicas específicas.

### ¿Qué es SEO?

**SEO (Search Engine Optimization)** es el proceso de optimizar un sitio web para aumentar su visibilidad en los resultados orgánicos de los motores de búsqueda. Su objetivo principal es atraer tráfico relevante y de calidad mejorando el posicionamiento en las SERPs (Search Engine Results Pages).

> **Fuente oficial**: [Google Search Documentation](https://developers.google.com/search/docs)

Según Google, SEO es "el proceso de aumentar la visibilidad de las páginas de un sitio web en los motores de búsqueda para atraer tráfico más relevante". No se trata solo de posicionamiento, sino de **relevancia** y **experiencia del usuario**.

### Importancia del SEO en 2025

En 2025, Google ha evolucionado significativamente hacia:

- **Búsqueda Semántica**: El enfoque en keywords exactas ha disminuido en favor de la comprensión del contexto e intención
- **Inteligencia Artificial**: Algoritmos como RankBrain y MUM priorizan la relevancia contextual
- **E-A-T ampliado**: Experience, Expertise, Authoritativeness, Trustworthiness como factores críticos
- **Core Web Vitals**: Métricas de experiencia del usuario como factor de ranking

**Realidad actual**: Google ha reducido significativamente el peso de las keywords exactas. En su lugar, se enfoca en:

- **Intención de búsqueda** (Search Intent)
- **Contexto semántico** del contenido
- **Entidades** y relaciones conceptuales
- **Relevancia topical** del sitio

### Tipos de SEO

El SEO moderno se divide en cuatro categorías principales:

#### 1. SEO On-Page

Optimizaciones realizadas directamente en el contenido y código del sitio web.

**Elementos clave**:

- Contenido y relevancia temática
- Optimización de meta tags (title, description)
- Estructura de URLs amigables
- Headers jerárquicos (H1-H6)
- Optimización de imágenes y multimedia
- Enlazado interno estratégico

#### 2. SEO Off-Page

Factores externos que influyen en la autoridad y relevancia del sitio.

**Elementos clave**:

- Link building de calidad
- Menciones de marca
- Señales sociales
- E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness)
- Domain Authority
- Reputación online

#### 3. SEO Técnico

Optimizaciones de infraestructura, rendimiento y accesibilidad técnica.

**Elementos clave**:

- Core Web Vitals
- Crawlability e indexabilidad
- Sitemap y robots.txt
- Estructura de datos (Schema.org)
- Rendimiento y velocidad
- Mobile-first indexing
- HTTPS y seguridad

#### 4. SEO Local

Optimizaciones específicas para búsquedas geográficas y negocios locales.

**Elementos clave**:

- Google Business Profile
- NAP consistency (Name, Address, Phone)
- Reviews y reputación local
- Contenido geo-específico
- Local citations
- Map pack optimization

---

## II. Cómo Funciona Google

> **🔍 Fundamentos Esenciales** - Entender cómo Google descubre, procesa y rankea tu contenido es fundamental para cualquier estrategia SEO efectiva.

Antes de profundizar en técnicas específicas de SEO, es crucial entender **cómo funciona realmente Google**. Este proceso se divide en tres etapas fundamentales que determinan si tu contenido aparecerá en los resultados de búsqueda y en qué posición.

### El Proceso de Tres Etapas

#### 1. Crawling (Rastreo) 🕷️

**¿Qué es?** El proceso mediante el cual Google descubre páginas web nuevas y actualizadas.

**¿Cómo funciona?**

- **Googlebot** (el robot de Google) sigue enlaces de página en página
- Comienza desde páginas conocidas y sigue los enlaces internos y externos
- También consulta sitemaps XML para descubrir URLs
- Prioriza páginas según su importancia percibida

**Factores que afectan el crawling:**

- **Crawl Budget**: Google asigna un "presupuesto" de rastreo a cada sitio
- **Velocidad del sitio**: Sitios más rápidos son rastreados más frecuentemente
- **Estructura de enlaces**: Páginas bien enlazadas son encontradas más fácilmente
- **robots.txt**: Puede bloquear o permitir el rastreo de ciertas áreas
- **Errores 404/5xx**: Demasiados errores pueden reducir el crawl budget

**¿Qué puede impedir el crawling?**

- Páginas bloqueadas en robots.txt
- Enlaces rotos o páginas sin enlaces entrantes
- JavaScript complejo que impide la navegación
- Sitios extremadamente lentos
- Demasiados parámetros en URLs

#### 2. Indexing (Indexación) 📚

**¿Qué es?** El proceso donde Google analiza y almacena el contenido de las páginas rastreadas.

**¿Cómo funciona?**

- Google analiza el contenido textual, imágenes y videos
- Procesa meta tags, datos estructurados y elementos HTML
- Identifica el tema principal y keywords relevantes
- Determina la calidad y relevancia del contenido
- Almacena esta información en su índice masivo

**Factores que afectan la indexación:**

- **Calidad del contenido**: Contenido original y valioso es preferido
- **Estructura HTML**: HTML semántico ayuda a entender el contenido
- **Meta robots**: Tags como `noindex` previenen la indexación
- **Contenido duplicado**: Google puede elegir no indexar duplicados
- **Canonical URLs**: Ayudan a consolidar señales de páginas similares

**¿Qué puede impedir la indexación?**

- Meta tag `noindex`
- Contenido de muy baja calidad o spam
- Contenido duplicado idéntico
- Páginas que requieren login para ver contenido
- Contenido generado dinámicamente que Google no puede procesar

#### 3. Ranking (Clasificación) 🏆

**¿Qué es?** El proceso donde Google determina el orden de los resultados para cada búsqueda.

**¿Cómo funciona?**

- Google usa **más de 200 factores de ranking**
- Analiza la **intención de búsqueda** del usuario
- Evalúa la **relevancia** del contenido para la query
- Considera la **autoridad** de la página y el dominio
- Factoriza la **experiencia del usuario** (Core Web Vitals)

**Factores principales de ranking 2025:**

**Contenido y Relevancia:**

- Coincidencia con la intención de búsqueda
- Calidad y profundidad del contenido
- Autoridad temática (E-A-T)
- Frescura del contenido (para temas sensibles al tiempo)

**Experiencia del Usuario:**

- Core Web Vitals (LCP, INP, CLS)
- Mobile-friendliness
- Seguridad HTTPS
- Ausencia de intersticiales intrusivos

**Autoridad y Confianza:**

- Calidad y cantidad de backlinks
- Autoridad del dominio
- Menciones de marca
- Señales de E-A-T

**Factores Técnicos:**

- Estructura de URLs
- HTML semántico
- Datos estructurados
- Optimización móvil

### Conceptos Clave para SEO

#### Crawl Budget

**¿Qué es?** La cantidad de páginas que Google está dispuesto a rastrear en tu sitio en un período determinado.

**¿Por qué importa?**

- Sitios grandes pueden no ser completamente rastreados
- Páginas importantes pueden quedarse sin indexar
- Optimizar el crawl budget es crucial para sitios de e-commerce

**Cómo optimizar:**

- Mejorar la velocidad del sitio
- Evitar contenido duplicado
- Optimizar la estructura de enlaces internos
- Usar robots.txt para bloquear páginas irrelevantes
- Mantener sitemaps XML actualizados

#### Search Intent (Intención de Búsqueda)

**¿Qué es?** El objetivo real del usuario al realizar una búsqueda.

**Tipos de intención:**

1. **Informacional**: Buscar información
   - "qué es SEO"
   - "cómo funciona Google"

2. **Navegacional**: Encontrar un sitio específico
   - "Facebook login"
   - "YouTube"

3. **Transaccional**: Realizar una compra
   - "comprar iPhone 15"
   - "mejor precio MacBook"

4. **Comercial**: Investigar antes de comprar
   - "mejor teléfono 2025"
   - "iPhone vs Samsung"

**Por qué es crucial:** Google prioriza contenido que mejor satisface la intención del usuario, no solo páginas con keywords exactas.

#### E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness)

**¿Qué es?** Los criterios que Google usa para evaluar la calidad del contenido.

**Experience (Experiencia):** ¿El autor tiene experiencia directa con el tema?
**Expertise (Especialización):** ¿El autor es experto en el tema?
**Authoritativeness (Autoridad):** ¿El sitio/autor es reconocido como autoridad?
**Trustworthiness (Confiabilidad):** ¿La información es precisa y confiable?

**Especialmente importante para:** YMYL (Your Money or Your Life) - temas de salud, finanzas, seguridad, etc.

### Implicaciones para SEO

**Para Crawling:**

- Crear una arquitectura de sitio clara con enlaces internos lógicos
- Mantener velocidad de carga óptima
- Usar sitemaps XML para sitios grandes
- Optimizar robots.txt para guiar el rastreo

**Para Indexing:**

- Crear contenido original y valioso
- Usar HTML semántico
- Implementar datos estructurados
- Evitar contenido duplicado

**Para Ranking:**

- Enfocarse en satisfacer la intención de búsqueda
- Construir autoridad temática
- Optimizar Core Web Vitals
- Obtener backlinks de calidad

---

## III. Core Web Vitals

> **📊 Métricas Fundamentales** - Las Core Web Vitals son métricas específicas que Google considera esenciales para medir la experiencia del usuario. Desde 2021, son un factor oficial de ranking.
> **Fuente oficial**: [Google Web Vitals](https://web.dev/vitals/) | [Core Web Vitals en Search](https://developers.google.com/search/docs/appearance/core-web-vitals)

### ¿Qué Son las Core Web Vitals?

Las **Core Web Vitals** representan un subconjunto de métricas de experiencia web que Google ha identificado como **esenciales para todos los sitios**. Se centran en tres aspectos fundamentales de la experiencia del usuario:

1. **Velocidad de carga** (LCP)
2. **Interactividad** (INP)
3. **Estabilidad visual** (CLS)

### Métricas Actuales (2025)

#### 1. LCP - Largest Contentful Paint ⚡

**Qué mide**: Tiempo que tarda en cargar el elemento de contenido más grande visible en el viewport.

**Umbral objetivo**: < 2.5 segundos

**Por qué importa**: Los usuarios abandonan sitios que tardan más de 3 segundos en cargar. LCP mide la **percepción real de velocidad** del usuario.

**Elementos que cuenta como LCP**:

- Imágenes
- Videos
- Elementos con imágenes de fondo
- Bloques de texto

**Factores que lo afectan**:

- Tiempo de respuesta del servidor
- CSS y JavaScript que bloquean el renderizado
- Tiempo de carga de recursos (imágenes, videos)
- Renderizado del lado del cliente

#### 2. INP - Interaction to Next Paint 🖱️

**Qué mide**: Tiempo entre la interacción del usuario (click, tap, teclado) y la siguiente actualización visual.

**Umbral objetivo**: < 200 milisegundos

**Por qué importa**: Mide la **responsividad real** del sitio. Reemplazó a FID en 2024 porque evalúa toda la interacción, no solo el inicio.

**Interacciones que evalúa**:

- Clicks y taps
- Presionar teclas
- Cualquier interacción que cause un repaint

**Factores que lo afectan**:

- JavaScript de larga duración
- Tareas principales del thread principal
- Tamaño y complejidad del DOM
- Renderizado excesivo

#### 3. CLS - Cumulative Layout Shift 📐

**Qué mide**: Cantidad de cambios inesperados en el diseño durante la carga de la página.

**Umbral objetivo**: < 0.1

**Por qué importa**: Los elementos que se mueven inesperadamente crean **frustración** y pueden causar clicks accidentales.

**Elementos que causan CLS**:

- Imágenes sin dimensiones
- Anuncios que se cargan tarde
- Fuentes que cambian el tamaño del texto
- Contenido dinámico que empuja otros elementos

**Factores que lo afectan**:

- Imágenes sin dimensiones definidas
- Anuncios, embeds e iframes dinámicos
- Fuentes web que causan FOIT/FOUT
- Acciones que modifican el DOM

### Cómo Mejorar Cada Métrica

#### Optimizar LCP

**Estrategias principales**:

1. **Optimizar servidor**: Usar CDN, caché, y hosting rápido
2. **Priorizar recursos críticos**: Preload de imágenes hero
3. **Optimizar imágenes**: WebP, tamaños apropiados, lazy loading inteligente
4. **Eliminar render-blocking**: CSS crítico inline, defer JS no crítico

#### Optimizar INP

**Estrategias principales**:

1. **Reducir JavaScript**: Code splitting, eliminar código no usado
2. **Optimizar el main thread**: Evitar tareas largas (>50ms)
3. **Usar web workers**: Para operaciones pesadas
4. **Debounce eventos**: Para inputs frecuentes

#### Optimizar CLS

**Estrategias principales**:

1. **Reservar espacio**: Definir width/height en imágenes
2. **Fuentes estables**: font-display: swap, fallbacks similares
3. **Contenido estático**: Evitar insertar contenido dinámico
4. **Anuncios controlados**: Reservar espacios fijos

### Medición de Core Web Vitals

Las Core Web Vitals se pueden medir de dos formas:

#### Datos de Laboratorio (Lab Data)

- **Herramientas**: Lighthouse, PageSpeed Insights
- **Ventaja**: Reproducible y debuggeable
- **Limitación**: No refleja experiencia real del usuario

#### Datos de Campo (Field Data)

- **Fuente**: Chrome User Experience Report (CrUX)
- **Ventaja**: Datos reales de usuarios
- **Limitación**: Requiere suficiente tráfico

**Implementación de medición básica**:

```javascript
// Medición con web-vitals library
import { onLCP, onINP, onCLS } from 'web-vitals';

function sendToAnalytics(metric) {
  // Enviar métricas a tu servicio de analytics
  console.log(metric.name, metric.value);
}

onLCP(sendToAnalytics);
onINP(sendToAnalytics);
onCLS(sendToAnalytics);
```

---

## IV. Elementos Técnicos SEO

> **🛠️ Elementos Fundamentales** - Componentes técnicos esenciales que todo sitio web debe implementar correctamente

### robots.txt - Control de Rastreo

**¿Qué es?** El archivo `robots.txt` es un protocolo que indica a los motores de búsqueda qué páginas de tu sitio pueden o no rastrear.

**¿Para qué sirve?**

- **Eficiencia de crawl budget**: Evita que Google gaste tiempo en páginas irrelevantes
- **Protección de contenido sensible**: Bloquea acceso a directorios administrativos
- **Control de indexación**: Aunque no garantiza que no se indexe, ayuda a gestionar el rastreo

> **Importante**: robots.txt **NO impide la indexación**. Para eso usa meta robots o noindex.
> **Fuente oficial**: [Google Robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/robots-txt)

**Casos de uso comunes**:

- Bloquear directorios administrativos (`/admin/`, `/dashboard/`)
- Evitar rastreo de APIs internas (`/api/`)
- Excluir archivos temporales o de sistema
- Dirigir a bots específicos a diferentes políticas

```txt
# Ejemplo básico de robots.txt
User-agent: *
Allow: /

# Bloquear contenido administrativo
Disallow: /admin/
Disallow: /api/private/
Disallow: /_next/

# Permitir APIs públicas
Allow: /api/public/

# Ubicación del sitemap
Sitemap: https://ejemplo.com/sitemap.xml

# Configuraciones específicas por bot
User-agent: Googlebot
Allow: /

# Bloquear bots de IA si es necesario
User-agent: GPTBot
Disallow: /
```

### manifest.json - Progressive Web App

**¿Qué es?** El Web App Manifest es un archivo JSON que proporciona información sobre tu aplicación web para que el navegador sepa cómo comportarse cuando se "instala" en el dispositivo del usuario.

**¿Para qué sirve?**

- **Experiencia nativa**: Permite que tu web se sienta como una app
- **Instalación**: Los usuarios pueden "instalar" tu sitio en su pantalla de inicio
- **SEO móvil**: Google considera PWA como factor positivo para mobile-first indexing
- **Engagement**: Mayor retención de usuarios con experiencia app-like

**Elementos clave del manifest**:

- **name/short_name**: Nombres que aparecen al instalar
- **start_url**: URL inicial al abrir la app
- **display**: Cómo se muestra (standalone, fullscreen, etc.)
- **theme_color/background_color**: Colores de la interfaz
- **icons**: Iconos para diferentes tamaños y dispositivos

```json
{
  "name": "Mi Sitio Web SEO",
  "short_name": "MiSitio",
  "description": "Sitio web optimizado para SEO y experiencia de usuario",
  "start_url": "/",
  "display": "standalone",
  "background_color": "#ffffff",
  "theme_color": "#000000",
  "icons": [
    {
      "src": "/icons/icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "/icons/icon-512x512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
```

### Sitemap XML - Indexación Eficiente

**¿Qué es?** Un sitemap es un archivo que proporciona información sobre las páginas, videos y otros archivos de tu sitio, y las relaciones entre ellos.

**¿Para qué sirve?**

- **Descubrimiento**: Ayuda a Google a encontrar páginas que podrían no descubrir al rastrear
- **Priorización**: Indica la importancia relativa de tus páginas
- **Metadatos**: Proporciona información sobre última modificación, frecuencia de cambio
- **Sitios grandes**: Especialmente útil para sitios con muchas páginas o poca vinculación interna
- **Contenido especializado**: Crucial para imágenes, videos y noticias

> **Fuente oficial**: [Google Sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)

**Casos donde es esencial**:

- Sitios con más de 500 páginas
- Sitios con poco enlazado interno
- Contenido multimedia (imágenes, videos)
- Sitios nuevos con pocos backlinks
- Sitios con contenido actualizado frecuentemente
- E-commerce con catálogos grandes

### Límites y Restricciones Importantes

**Límites por sitemap:**

- **Máximo 50,000 URLs** por archivo sitemap
- **Máximo 50 MB** de tamaño (sin comprimir)
- Si excedes estos límites, debes dividir en múltiples sitemaps

**Sitemap Index (Sitemap de Sitemaps):**

Cuando tienes un sitio grande (como e-commerce con miles de productos), necesitas usar un **Sitemap Index** que funciona como un "índice de sitemaps".

```xml
<?xml version="1.0" encoding="UTF-8"?>
<sitemapindex xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <sitemap>
    <loc>https://tienda.com/sitemap-productos.xml</loc>
    <lastmod>2025-08-31</lastmod>
  </sitemap>
  <sitemap>
    <loc>https://tienda.com/sitemap-categorias.xml</loc>
    <lastmod>2025-08-31</lastmod>
  </sitemap>
  <sitemap>
    <loc>https://tienda.com/sitemap-blog.xml</loc>
    <lastmod>2025-08-31</lastmod>
  </sitemap>
  <sitemap>
    <loc>https://tienda.com/sitemap-imagenes.xml</loc>
    <lastmod>2025-08-31</lastmod>
  </sitemap>
</sitemapindex>
```

**Estrategia para E-commerce Grandes:**

```text
Sitemap Principal (sitemap.xml)
├── sitemap-productos-1.xml (50,000 URLs)
├── sitemap-productos-2.xml (50,000 URLs)
├── sitemap-productos-3.xml (45,000 URLs)
├── sitemap-categorias.xml (500 URLs)
├── sitemap-marcas.xml (200 URLs)
├── sitemap-blog.xml (1,500 URLs)
├── sitemap-imagenes-1.xml (50,000 URLs)
└── sitemap-imagenes-2.xml (30,000 URLs)
```

**Elementos importantes del sitemap:**

- `<loc>`: URL de la página (obligatorio)
- `<lastmod>`: Fecha de última modificación (recomendado)
- `<changefreq>`: Frecuencia de cambio (opcional, Google lo ignora)
- `<priority>`: Prioridad relativa (0.0 a 1.0, opcional, Google lo ignora)

**Generación dinámica en Next.js**:

```typescript
// app/sitemap.ts - Sitemap dinámico para sitios grandes
import { MetadataRoute } from 'next'

export default async function sitemap(): MetadataRoute.Sitemap {
  const baseUrl = 'https://ejemplo.com'
  
  // URLs estáticas (siempre incluir)
  const staticUrls: MetadataRoute.Sitemap = [
    {
      url: baseUrl,
      lastModified: new Date(),
      changeFrequency: 'daily',
      priority: 1,
    },
    {
      url: `${baseUrl}/about`,
      lastModified: new Date(),
      changeFrequency: 'monthly',
      priority: 0.8,
    }
  ]
  
  // URLs dinámicas - aquí es donde Next.js aporta valor real
  const posts = await getBlogPosts()
  const postUrls: MetadataRoute.Sitemap = posts.map((post) => ({
    url: `${baseUrl}/blog/${post.slug}`,
    lastModified: post.updatedAt,
    changeFrequency: 'weekly' as const,
    priority: 0.6,
  }))
  
  // Para sitios grandes, considera crear múltiples sitemaps
  // Este ejemplo asume menos de 50,000 URLs totales
  return [...staticUrls, ...postUrls]
}

// Para sitios muy grandes, considera dividir por tipo:
// app/sitemap-productos.ts, app/sitemap-blog.ts, etc.
```

**Mejores prácticas para sitios grandes:**

1. **Dividir por tipo de contenido**: productos, categorías, blog, páginas estáticas
2. **Actualización automatizada**: Regenerar sitemaps cuando el contenido cambie
3. **Compresión**: Usar gzip para reducir el tamaño de transferencia
4. **Monitoreo**: Verificar regularmente en Search Console que Google está procesando los sitemaps
5. **URLs absolutas**: Siempre usar URLs completas, nunca relativas

### noIndex y noFollow - Control de Indexación

**¿Qué son?** Directivas que controlan cómo los motores de búsqueda interactúan con tu contenido.

#### noIndex

**¿Para qué sirve?**

- **Impedir indexación**: Evita que la página aparezca en resultados de búsqueda
- **Contenido duplicado**: Previene problemas de contenido duplicado
- **Páginas administrativas**: Oculta dashboards, formularios de login
- **Contenido temporal**: Páginas de agradecimiento, confirmaciones

**Casos de uso**:

- Páginas de thank you
- Páginas de confirmación de registro
- Páginas de error personalizadas
- Versiones de impresión de páginas
- Páginas de búsqueda interna con resultados

```html
<!-- Impedir indexación pero permitir seguimiento de enlaces -->
<meta name="robots" content="noindex, follow">

<!-- Para Googlebot específicamente -->
<meta name="googlebot" content="noindex, follow">
```

#### noFollow

**¿Qué es?** Una directiva que indica a los motores de búsqueda que **no sigan** un enlace específico o todos los enlaces de una página, y que **no transfieran autoridad** (link juice) a través de esos enlaces.

**¿Para qué sirve?**

El atributo `nofollow` cumple dos funciones principales:

1. **Cumplimiento de directrices**: Google requiere que enlaces pagados, patrocinados o de intercambio usen `nofollow` para evitar manipulación del ranking
2. **Control de autoridad**: Evita que tu sitio "vote" por páginas en las que no confías o que no quieres respaldar
3. **Gestión de crawl budget**: En sitios grandes, previene que Google desperdicie tiempo rastreando páginas irrelevantes

**Casos de uso específicos**:

- **Enlaces de comentarios de usuarios**: Contenido no moderado donde no puedes controlar la calidad de los destinos
- **Enlaces en formularios de registro/login**: Páginas que no aportan valor SEO y pueden confundir a los bots
- **Enlaces a documentos legales en footers**: Términos de servicio, políticas de privacidad
- **Enlaces internos a páginas de proceso**: Checkout, carrito de compras, páginas de confirmación

**Tipos de nofollow en 2025**:

```html
<!-- nofollow tradicional (funciona para todos los casos) -->
<a href="https://sitio-no-confiable.com" rel="nofollow">Enlace no seguido</a>

<!-- sponsored: para enlaces patrocinados -->
<a href="https://sitio-patrocinado.com" rel="sponsored">Enlace patrocinado</a>

<!-- ugc: para contenido generado por usuarios -->
<a href="https://contenido-usuario.com" rel="ugc">Enlace de usuario</a>

<!-- Combinación múltiple -->
<a href="https://ejemplo.com" rel="nofollow sponsored">Enlace patrocinado no seguido</a>
```

### URLs Canónicas - Contenido Duplicado

**¿Qué son?** Una URL canónica le dice a los motores de búsqueda cuál es la versión "oficial" de una página cuando existen múltiples URLs con contenido similar o idéntico.

**¿Para qué sirven?**

Las URLs canónicas resuelven uno de los problemas más comunes del SEO: el contenido duplicado. Cuando el mismo contenido es accesible desde múltiples URLs, Google puede confundirse sobre cuál versión rankear, diluyendo las señales de ranking.

**Problemas que resuelven:**

- **Evitar contenido duplicado**: Consolidar señales de ranking en una URL
- **Parámetros de URL**: Unificar versiones con diferentes parámetros (utm, filtros, sesiones)
- **Protocolo inconsistente**: Especificar HTTP vs HTTPS
- **Subdominios**: Definir www vs no-www
- **Trailing slashes**: Unificar URLs con y sin "/" al final

**Ejemplos prácticos de problemas comunes:**

#### Problema 1: Protocolo y Subdominios

```text
❌ Múltiples versiones del mismo contenido:
http://misitio.com
https://misitio.com  
http://www.misitio.com
https://www.misitio.com

✅ Solución con canónica:
Todas apuntan a: https://www.misitio.com
```

#### Problema 2: Parámetros de Tracking y Filtros

```text
❌ Múltiples URLs para el mismo contenido:
https://misitio.com/articulo
https://misitio.com/articulo?utm_source=facebook
https://misitio.com/articulo?utm_source=twitter&utm_campaign=verano
https://misitio.com/articulo?page=0
https://misitio.com/articulo?page=0&sort=date

✅ Canónica apunta a la versión limpia:
<link rel="canonical" href="https://misitio.com/articulo">
```

#### Problema 3: E-commerce con Múltiples Rutas

```text
❌ Producto accesible por múltiples categorías:
https://tienda.com/productos/smartphones/iphone-15
https://tienda.com/marca/apple/iphone-15  
https://tienda.com/ofertas/iphone-15
https://tienda.com/buscar?q=iphone-15

✅ Canónica apunta a la URL principal:
<link rel="canonical" href="https://tienda.com/productos/smartphones/iphone-15">
```

#### Problema 4: Paginación y URLs de Listados

```text
❌ Confusión entre páginas de listado:
https://blog.com/categoria/seo
https://blog.com/categoria/seo?page=1
https://blog.com/categoria/seo/?page=1&per_page=10

✅ Primera página como canónica:
<link rel="canonical" href="https://blog.com/categoria/seo">
```

**Implementación correcta:**

```html
<!-- En el <head> de cada página afectada -->
<link rel="canonical" href="https://ejemplo.com/pagina-principal">

<!-- Auto-canónica (la página apunta a sí misma) -->
<link rel="canonical" href="https://ejemplo.com/esta-misma-pagina">

<!-- Para páginas paginadas -->
<link rel="canonical" href="https://ejemplo.com/blog"> <!-- Solo en page=1 -->
```

**Errores comunes a evitar:**

❌ **Canónica a página diferente**: No uses canonical para redireccionar
❌ **Múltiples canónicas**: Solo una canonical por página
❌ **Canonical a página 404**: Asegúrate que la URL canónica funcione
❌ **Canonical relativa**: Usa URLs absolutas siempre

**¿Cuándo NO usar canonical?**

- Páginas genuinamente únicas (aunque sean similares)
- Cuando quieres que ambas versiones se indexen
- Para redirects permanentes (usa 301 en su lugar)

### Schema.org / JSON-LD - Datos Estructurados

**¿Qué son?** Los datos estructurados son un formato estandarizado para proporcionar información sobre una página y clasificar su contenido.

**¿Para qué sirven?**

- **Rich Snippets**: Aparición mejorada en resultados de búsqueda
- **Comprensión del contenido**: Ayuda a Google a entender mejor tu contenido
- **Featured Snippets**: Mayor posibilidad de aparecer en la posición 0
- **Voice Search**: Optimización para búsquedas por voz

> **Fuente oficial**: [Schema.org](https://schema.org/) | [Google Structured Data](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data)

**Tipos más importantes**:

#### Article Schema

**Cuándo usar**: Posts de blog, noticias, artículos

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Guía Completa de SEO 2025",
  "description": "Todo lo que necesitas saber sobre SEO",
  "author": {
    "@type": "Person",
    "name": "Santiago Betancur"
  },
  "datePublished": "2025-08-31",
  "dateModified": "2025-08-31",
  "publisher": {
    "@type": "Organization",
    "name": "Mi Sitio Web",
    "logo": "https://ejemplo.com/logo.png"
  }
}
</script>
```

#### Organization Schema

**Cuándo usar**: Páginas de inicio, páginas "Sobre nosotros"

#### Product Schema

**Cuándo usar**: Páginas de productos en e-commerce

#### FAQ Schema

**Cuándo usar**: Páginas con preguntas frecuentes

#### LocalBusiness Schema

**Cuándo usar**: Negocios locales, páginas de contacto

### Open Graph - Redes Sociales

**¿Qué es?** Open Graph es un protocolo que permite que cualquier página web se convierta en un objeto enriquecido en redes sociales.

**¿Para qué sirve?**

- **Compartir optimizado**: Control sobre cómo se ve tu contenido al compartir
- **CTR mejorado**: Previsualizaciones atractivas aumentan clicks
- **Branding**: Consistencia visual de tu marca en redes sociales
- **SEO indirecto**: Más compartidos pueden llevar a más tráfico y enlaces

**Elementos esenciales**:

- `og:title`: Título que aparecerá al compartir
- `og:description`: Descripción del contenido
- `og:image`: Imagen de preview (1200x630px recomendado)
- `og:url`: URL canónica de la página
- `og:type`: Tipo de contenido (website, article, product)

```html
<!-- Open Graph básico -->
<meta property="og:title" content="Guía Completa de SEO 2025">
<meta property="og:description" content="Todo lo que necesitas saber sobre SEO actualizado para 2025">
<meta property="og:image" content="https://ejemplo.com/seo-guide-preview.jpg">
<meta property="og:url" content="https://ejemplo.com/guia-seo-2025">
<meta property="og:type" content="article">
<meta property="og:site_name" content="Mi Sitio Web">

<!-- Twitter Card (complementa Open Graph) -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@misitio">
<meta name="twitter:creator" content="@autor">
```

**Dimensiones de imagen recomendadas**:

- **Facebook**: 1200 x 630 pixels
- **Twitter**: 1024 x 512 pixels (summary_large_image)
- **LinkedIn**: 1200 x 627 pixels

### Meta Tags Esenciales

**¿Qué son?** Elementos HTML que proporcionan metadatos sobre tu página web.

#### Title Tag

**Características principales:**

- **Límite**: 50-60 caracteres
- **Único por página**: Cada página debe tener un title diferente
- **Descriptivo**: Debe reflejar el contenido principal
- **Incluir marca**: Generalmente al final

```html
<!-- ✅ Correcto -->
<title>Guía Completa de React Hooks 2025 | DevBlog</title>

<!-- ❌ Incorrecto -->
<title>React, Hooks, Tutorial, Guía, JavaScript, Frontend</title>
```

#### Meta Description

**Características principales:**

- **Límite**: 150-160 caracteres
- **Persuasiva**: Debe motivar el click
- **Incluir valor**: Qué obtendrá el usuario
- **Call-to-action implícito**: "Aprende", "Descubre", "Guía"

```html
<meta name="description" content="Aprende React Hooks desde cero con ejemplos prácticos. Guía actualizada 2025 con useState, useEffect y hooks personalizados.">
```

#### Viewport Meta Tag

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### HTML Semántico

**¿Qué es?** HTML semántico utiliza elementos HTML que tienen significado específico, no solo presentación.

**¿Por qué es importante para SEO?**

- **Comprensión del contenido**: Ayuda a Google a entender la estructura
- **Accesibilidad**: Mejora la experiencia para usuarios con discapacidades
- **Featured Snippets**: Estructura clara ayuda a ser seleccionado
- **Jerarquía clara**: Facilita el crawling y la indexación

**Elementos semánticos clave**:

#### Estructura de headings

```html
<!-- ✅ Correcto - Un H1 por página, jerarquía lógica -->
<h1>Título Principal</h1>
  <h2>Sección Principal</h2>
    <h3>Subsección</h3>
    <h3>Otra Subsección</h3>
  <h2>Segunda Sección Principal</h2>

<!-- ❌ Incorrecto - Múltiples H1, jerarquía rota -->
<h1>Título Principal</h1>
<h1>Otro Título Principal</h1>
<h4>Subtítulo</h4> <!-- Salta de H1 a H4 -->
```

#### Elementos estructurales

```html
<header>
  <nav><!-- Navegación principal --></nav>
</header>

<main>
  <article>
    <header>
      <h1>Título del Artículo</h1>
    </header>
    <section>
      <h2>Primera Sección</h2>
    </section>
  </article>
  
  <aside>
    <!-- Contenido relacionado -->
  </aside>
</main>

<footer>
  <!-- Información del sitio -->
</footer>
```

---

---

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título Descriptivo | Marca</title>
    <meta name="description" content="Descripción clara y atractiva que resuma el contenido">
</head>
<body>
    <header>
        <h1>Título Principal - Tema Central</h1>
    </header>
    
    <main>
        <section>
            <h2>Subtema Principal</h2>
            <h3>Detalle Específico</h3>
            <p>Contenido rico y contextual que responde a la intención del usuario</p>
        </section>
    </main>
</body>
</html>
```

#### Optimización de Titles y Meta Descriptions

**Title Tags**:

- Longitud: 50-60 caracteres
- Incluir marca al final
- Descriptivo y único por página
- Reflejar la intención de búsqueda

```html
<!-- ✅ Correcto -->
<title>Guía Completa de React Hooks 2025 | DevBlog</title>

<!-- ❌ Incorrecto -->
<title>React, Hooks, Tutorial, Guía, JavaScript, Frontend</title>
```

**Meta Descriptions**:

- Longitud: 150-160 caracteres
- Call-to-action implícito
- Resumen atractivo del contenido

```html
<meta name="description" content="Aprende React Hooks desde cero con ejemplos prácticos. Guía actualizada 2025 con useState, useEffect y hooks personalizados.">
```

### Estructura de URLs

#### Mejores Prácticas

```text
✅ Correctas:
/guia-react-hooks-2025
/productos/smartphones/iphone-15
/blog/seo-tecnico-core-web-vitals

❌ Incorrectas:
/p?id=123&cat=456
/página-con-tildes-y-espacios
/very-long-url-with-too-many-words-that-makes-no-sense
```

### Optimización de Imágenes

```html
<!-- Implementación completa -->
<picture>
  <source 
    media="(min-width: 768px)" 
    srcset="imagen-desktop.webp 1200w, imagen-desktop-2x.webp 2400w"
    type="image/webp">
  <source 
    media="(max-width: 767px)" 
    srcset="imagen-mobile.webp 400w, imagen-mobile-2x.webp 800w"
    type="image/webp">
  <img 
    src="imagen-fallback.jpg" 
    alt="Descripción específica y contextual de la imagen"
    width="1200" 
    height="600"
    loading="lazy"
    decoding="async">
</picture>
```

---

#### Meta Etiquetas Útiles

Las meta etiquetas proporcionan información importante tanto para buscadores como para navegadores.

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <!-- Meta básicas -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- SEO fundamentales -->
  <title>Título Optimizado para SEO - Marca</title>
  <meta name="description" content="Descripción clara y atractiva de 150-160 caracteres">
  <meta name="keywords" content="palabra1, palabra2, palabra3"> <!-- Opcional en 2025 -->
  
  <!-- Autoría y derechos -->
  <meta name="author" content="Nombre del Autor">
  <meta name="copyright" content="© 2025 Mi Empresa">
  <meta name="robots" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
  
  <!-- Geo-localización (para SEO local) -->
  <meta name="geo.region" content="CO-CUN"> <!-- Colombia - Cundinamarca -->
  <meta name="geo.placename" content="Bogotá">
  <meta name="geo.position" content="4.7110;-74.0721">
  <meta name="ICBM" content="4.7110, -74.0721">
  
  <!-- Cache control -->
  <meta http-equiv="Cache-Control" content="public, max-age=31536000">
  <meta http-equiv="Expires" content="Wed, 31 Dec 2025 23:59:59 GMT">
  
  <!-- Seguridad -->
  <meta http-equiv="X-Content-Type-Options" content="nosniff">
  <meta http-equiv="X-Frame-Options" content="DENY">
  <meta http-equiv="X-XSS-Protection" content="1; mode=block">
  <meta http-equiv="Referrer-Policy" content="strict-origin-when-cross-origin">
  
  <!-- PWA -->
  <meta name="theme-color" content="#000000">
  <meta name="msapplication-TileColor" content="#000000">
  <meta name="application-name" content="Mi App">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <meta name="apple-mobile-web-app-title" content="Mi App">
  
  <!-- Canonical URL -->
  <link rel="canonical" href="https://ejemplo.com/pagina-actual">
  
  <!-- Idiomas alternativos -->
  <link rel="alternate" hreflang="es" href="https://ejemplo.com/es/pagina">
  <link rel="alternate" hreflang="en" href="https://ejemplo.com/en/page">
  <link rel="alternate" hreflang="x-default" href="https://ejemplo.com/es/pagina">
  
  <!-- Feeds -->
  <link rel="alternate" type="application/rss+xml" title="RSS Feed" href="/rss.xml">
  <link rel="alternate" type="application/atom+xml" title="Atom Feed" href="/atom.xml">
  
  <!-- Preconnect y DNS Prefetch -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link rel="dns-prefetch" href="//www.google-analytics.com">
  
  <!-- Manifest -->
  <link rel="manifest" href="/manifest.json">
  
  <!-- Favicons -->
  <link rel="icon" type="image/x-icon" href="/favicon.ico">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
</head>
</html>
```

---

## V. Checklist SEO

### Core Web Vitals Optimizados

#### LCP (Largest Contentful Paint) < 2.5s

- [ ] Optimizar imágenes hero (WebP/AVIF)
- [ ] Implementar preloading de recursos críticos
- [ ] Minimizar CSS/JS que bloquea renderizado
- [ ] Configurar CDN para recursos estáticos
- [ ] Optimizar tiempo de respuesta del servidor

#### INP (Interaction to Next Paint) < 200ms

- [ ] Implementar debouncing en eventos frecuentes
- [ ] Optimizar JavaScript con code splitting
- [ ] Usar Web Workers para tareas pesadas
- [ ] Implementar time slicing
- [ ] Minimizar re-renders innecesarios

#### CLS (Cumulative Layout Shift) < 0.1

- [ ] Definir dimensiones de imágenes
- [ ] Reservar espacio para ads y embeds
- [ ] Usar font-display: swap
- [ ] Implementar skeleton screens
- [ ] Evitar inserción dinámica de contenido

### HTTPS Implementado Correctamente

- [ ] Certificado SSL válido y actualizado
- [ ] Redirección automática HTTP → HTTPS
- [ ] Configurar HSTS headers
- [ ] Verificar mixed content warnings
- [ ] Actualizar enlaces internos a HTTPS

### Mobile-First Design Responsive

- [ ] Viewport meta tag configurado
- [ ] Touch targets mínimo 44px
- [ ] Texto legible sin zoom (16px mínimo)
- [ ] Contenido accesible sin scroll horizontal
- [ ] Navegación optimizada para móvil

### Sitemap XML Generado y Actualizado

- [ ] Sitemap incluye todas las páginas importantes
- [ ] URLs correctas y accesibles
- [ ] Fechas de modificación actualizadas
- [ ] Prioridades configuradas apropiadamente
- [ ] Enviado a Google Search Console

### Robots.txt Configurado Apropiadamente

- [ ] Archivo robots.txt accesible en /robots.txt
- [ ] Permite acceso a páginas importantes
- [ ] Bloquea contenido sensible o innecesario
- [ ] Incluye sitemap URL
- [ ] Configuración específica por user-agent

### Canonical URLs Implementadas

- [ ] URL canónica en cada página
- [ ] URLs consistentes (con/sin www, trailing slash)
- [ ] Canonical self-referencing en páginas únicas
- [ ] Canonical cruzado en contenido duplicado
- [ ] Verificar en paginación y filtros

### Schema Markup Validado

- [ ] JSON-LD implementado correctamente
- [ ] Schemas apropiados por tipo de página
- [ ] Validado con Google Rich Results Test
- [ ] Sin errores en datos estructurados
- [ ] Información completa y precisa

### 404 Errors Minimizados

- [ ] Página 404 personalizada y útil
- [ ] Enlaces internos funcionando
- [ ] Redirects 301 para URLs obsoletas
- [ ] Monitoreo de errores 404
- [ ] Navegación clara desde página 404

### Page Speed < 3 Segundos

- [ ] Optimización de imágenes (WebP/AVIF)
- [ ] Minificación CSS/JS
- [ ] Compresión gzip/brotli habilitada
- [ ] Cache headers configurados
- [ ] CDN implementado

### Images Optimizadas (WebP/AVIF)

- [ ] Formatos modernos implementados
- [ ] Responsive images con srcset
- [ ] Lazy loading habilitado
- [ ] Alt text descriptivo
- [ ] Dimensiones definidas

### Internal Linking Estratégico

- [ ] Enlaces internos relevantes
- [ ] Anchor text descriptivo
- [ ] Estructura de enlazado lógica
- [ ] Sin enlaces rotos
- [ ] Distribución de PageRank interna

### Meta Tags Únicos por Página

- [ ] Title único y descriptivo
- [ ] Meta description atractiva
- [ ] Open Graph completo
- [ ] Twitter Cards configurados
- [ ] Meta robots apropiados

### Heading Structure Jerárquica (H1-H6)

- [ ] Solo un H1 por página
- [ ] Jerarquía lógica sin saltos
- [ ] Headings descriptivos
- [ ] Palabras clave relevantes
- [ ] Estructura semánticamente correcta

### Alt Text Descriptivo en Imágenes

- [ ] Alt text en todas las imágenes
- [ ] Descripciones precisas y contextuales
- [ ] Alt vacío para imágenes decorativas
- [ ] Keywords naturales cuando apropiado
- [ ] Longitud apropiada (125 caracteres máx)

---

## VI. Conclusión

El SEO en 2025 ha evolucionado hacia un enfoque más holístico que prioriza la **experiencia del usuario** sobre optimizaciones técnicas superficiales. Los factores clave incluyen:

- **Performance**: Core Web Vitals como ranking factor crítico
- **Content Quality**: E-A-T como base de autoridad temática  
- **Technical Excellence**: Infraestructura sólida para crawling e indexing
- **User Experience**: Design móvil-first y accesibilidad
- **Semantic Understanding**: Contenido contextual sobre keyword stuffing

El éxito en SEO moderno requiere un enfoque multidisciplinario que combine expertise técnico, estrategia de contenido y comprensión profunda del comportamiento del usuario.

### Recursos y Referencias

- **[Google Search Documentation](https://developers.google.com/search/docs)** - Documentación oficial
- **[Core Web Vitals](https://web.dev/vitals/)** - Métricas de rendimiento  
- **[Schema.org](https://schema.org/)** - Datos estructurados
- **[Google Search Console](https://search.google.com/search-console)** - Herramienta oficial de monitoreo
- **[Next.js SEO Guide](https://nextjs.org/learn/seo)** - Implementación en Next.js
