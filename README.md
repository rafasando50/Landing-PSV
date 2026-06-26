# PSV Industrial - Landing Page & Catálogo

Sitio web corporativo y catálogo profesional para **PSV Industrial S.A. de C.V.**, desarrollado con **Astro**. El sitio destaca por un diseño moderno y fluido (Vanilla CSS), optimización SEO, y un sistema interactivo de filtrado de productos y servicios industriales.

---

## 🚀 Tecnologías Principales

- **Framework**: [Astro](https://astro.build/) (v7.x) para un rendimiento web estático ultra veloz.
- **Estilos**: Vanilla CSS con un sistema de diseño premium, variables globales de temas de color, diseño responsivo y micro-animaciones fluidas.
- **Scripting**: Vanilla JavaScript para interacciones ligeras (filtros dinámicos de catálogo, menú móvil responsivo y navegación interactiva).

---

## 📂 Estructura del Proyecto

El código fuente principal está organizado de la siguiente manera:

```text
PSV/
├── public/                 # Archivos estáticos (favicons, logotipos, fondos)
│   ├── favicon.ico
│   ├── favicon.svg
│   └── logo.png            # Logotipo principal de la empresa
├── src/
│   ├── components/         # Componentes modulares de Astro
│   │   ├── Header.astro    # Menú de navegación móvil y desktop con logo dinámico
│   │   ├── Intro.astro     # Sección Hero principal
│   │   ├── About.astro     # Sobre la empresa, historia y compromiso
│   │   ├── Catalog.astro   # Catálogo dinámico y filtrable de productos/servicios
│   │   ├── Partners.astro  # Sección de marcas aliadas (Destacado ICOSO)
│   │   ├── Contact.astro   # Formulario de contacto e información de ubicación
│   │   └── Footer.astro    # Pie de página con marcas registradas y aviso legal
│   ├── pages/
│   │   └── index.astro     # Página de inicio principal y metatags SEO
│   └── styles/
│       └── global.css      # Variables de diseño, fuentes y estilos comunes
├── package.json
└── README.md
```

---

## 🛠️ Comandos de Desarrollo

Todos los comandos se deben ejecutar en la raíz del proyecto desde la terminal:

### 1. Instalación de Dependencias
```bash
npm install
```

### 2. Iniciar Servidor de Desarrollo Local
Para trabajar de forma estándar en local (`http://localhost:4321`):
```bash
npm run dev
```

Si deseas ejecutar el servidor en segundo plano (background mode) según las pautas del proyecto:
```bash
# Iniciar en segundo plano
npx astro dev --background

# Consultar estado, logs o detener
npx astro dev status
npx astro dev logs
npx astro dev stop
```

### 3. Compilación para Producción
Genera la carpeta `dist/` con el sitio estático optimizado y listo para desplegar en hosting web tradicional (como cPanel o Apache):
```bash
npm run build
```

### 4. Previsualización del Build
Prueba el resultado compilado localmente antes de subirlo al servidor de producción:
```bash
npm run preview
```

---

## 🏷️ Marcas y Especialidades Destacadas

El catálogo está optimizado para enfocar y filtrar soluciones de marcas industriales líderes:
- **ICOSO** (Socio Autorizado): Sección enriquecida con tres tarjetas específicas para *Válvulas de Seguridad y Alivio*, *Válvulas Reguladoras de Presión*, y *Sistemas Fire Protection y Agua*, todas respaldadas por la certificación **ISO 9001:2015** (Perry Johnson Registrars).
- **Stafsjö / EBRO ARMATUREN**: Válvulas de guillotina y mariposa especializadas.
- **OleumTech**: Soluciones de instrumentación y medición tanto cableada como inalámbrica (Wireless/Wired).
- **AMSLATAM**: Medidores de flujo y actuadores de control.
- **ARI ARMATUREN**: Válvulas especiales e ingeniería térmica/trampas de vapor.
- **Mantenimiento Especializado**: Calibración y certificación oficial bajo norma **NOM-093-SCFI-2020** para válvulas de seguridad.

---

## 📄 Notas de Edición y Mantenimiento

- **Favicons y Logo**: Los recursos gráficos se gestionan en la carpeta `/public` (`/public/logo.png`, `/public/favicon.svg`, `/public/favicon.ico`).
- **SEO**: Los títulos, descripciones y palabras clave del sitio se configuran en el `<head>` del archivo [src/pages/index.astro](file:///c:/Users/LAP011/Documents/PSV/src/pages/index.astro).
