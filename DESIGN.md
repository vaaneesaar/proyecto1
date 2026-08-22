---
version: alpha
name: VLRC Design System
description: Sistema de diseño de VLRC — estética moderna, colorida y contemporánea para creadores y creativos.
colors:
  primary: "#D43200"
  primary-hover: "#B82A00"
  secondary: "#2B4871"
  interactive: "#05BADD"
  support: "#658FC5"
  emphasis: "#FF8007"
  accent: "#FFB404"
  warm-support: "#FF6B4A"
  editorial: "#B49CD8"
  background: "#FAFAF8"
  background-alt: "#C7D5EB"
  background-muted: "#D9E3F2"
  text: "#1F2D45"
  on-primary: "#FFFFFF"
typography:
  display:
    fontFamily: Hypop-Heavy
    fontSize: 64px
    fontWeight: 700
    lineHeight: 72px
  h1:
    fontFamily: Hypop-Heavy
    fontSize: 48px
    fontWeight: 700
    lineHeight: 56px
  h2:
    fontFamily: Hypop-Heavy
    fontSize: 36px
    fontWeight: 700
    lineHeight: 44px
  h3:
    fontFamily: NewYork
    fontSize: 28px
    fontWeight: 400
    lineHeight: 36px
  h4:
    fontFamily: NewYork
    fontSize: 22px
    fontWeight: 400
    lineHeight: 30px
  body-lg:
    fontFamily: Avenir
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
  body-md:
    fontFamily: Avenir
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  label-md:
    fontFamily: Avenir
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  caption:
    fontFamily: Avenir
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
spacing:
  3xs: 4px
  2xs: 8px
  xs: 12px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 40px
  2xl: 48px
  3xl: 64px
  4xl: 80px
  5xl: 96px
rounded:
  sm: 8px
  md: 16px
  full: 9999px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 14px 24px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 14px 24px
  button-ghost:
    backgroundColor: "{colors.background}"
    textColor: "{colors.secondary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 14px 24px
  card:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm} {spacing.md}"
  card-featured:
    backgroundColor: "{colors.background-alt}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm} {spacing.md}"
  card-muted:
    backgroundColor: "{colors.background-muted}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm} {spacing.md}"
  input:
    backgroundColor: "{colors.on-primary}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    typography: "{typography.body-lg}"
    height: 48px
  input-focus:
    backgroundColor: "{colors.on-primary}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    typography: "{typography.body-lg}"
  label:
    typography: "{typography.label-md}"
  nav-link:
    typography: "{typography.label-md}"
    textColor: "{colors.text}"
  nav-link-hover:
    textColor: "{colors.primary}"
  badge:
    backgroundColor: "{colors.emphasis}"
    textColor: "{colors.text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
  tag:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
  warm-card:
    backgroundColor: "{colors.warm-support}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm} {spacing.md}"
  editorial-card:
    backgroundColor: "{colors.editorial}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm} {spacing.md}"
  interactive-highlight:
    backgroundColor: "{colors.interactive}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    typography: "{typography.body-md}"
---

## Overview

VLRC encarna una estética moderna, contemporánea y muy colorida, centrada en el diseño gráfico y el disfrute de la vida. Siempre conserva la unión entre cariño, diversión y cercanía con los demás. Se apoya en tonos brillantes y colores complementarios para generar contraste, principalmente azules de toda la gama, rojos y pocos naranjas.

Transmite confianza, creatividad y diversión, mucho color y vida por el diseño gráfico y la vida en general. Prioriza la claridad y la legibilidad con una filosofía poco maximalista: layouts limpios, tipografía con propósito y la cantidad justa de espacio en blanco. Está pensada para creadores y creativos; respeta el tiempo y la carga cognitiva del usuario, pero también lo invita al dinamismo y al disfrute.

Un acento audaz pero sin abrumar, alto contraste, y componentes con detalles y decoración que forman parte de la composición.

## Colors

La paleta se construye sobre colores complementarios — azul y naranja como ejes principales, con tonos de rojo que refuerzan la energía y amarillo que aporta calidez decorativa. Cada color cumple un rol específico dentro del sistema.

### Paleta primaria

| Token | Hex | Uso |
|:------|:----|:----|
| `{colors.primary}` | `#D43200` | Color principal de marca. Botones principales (CTA), acentos, destacados y elementos clave de identidad. |
| `{colors.primary-hover}` | `#B82A00` | Estado hover del color primario. Versión más oscura para retroalimentación de interacción. |
| `{colors.secondary}` | `#2B4871` | Color principal secundario. Encabezados, navegación, texto destacado y elementos de alto contraste. |
| `{colors.interactive}` | `#05BADD` | Color interactivo. Enlaces, botones secundarios, iconografía y elementos que requieren atención visual. |

### Paleta de apoyo

| Token | Hex | Uso |
|:------|:----|:----|
| `{colors.support}` | `#658FC5` | Color de apoyo. Tarjetas, componentes secundarios y bloques de contenido. |
| `{colors.emphasis}` | `#FF8007` | Color de énfasis. Resaltar información importante, indicadores y elementos promocionales. |
| `{colors.accent}` | `#FFB404` | Color complementario. Detalles gráficos, etiquetas, indicadores y elementos decorativos. |
| `{colors.warm-support}` | `#FF6B4A` | Color de apoyo cálido. Ilustraciones, recursos gráficos y elementos complementarios. |
| `{colors.editorial}` | `#B49CD8` | Color complementario alternativo. Aplicaciones editoriales, composiciones especiales y recursos gráficos secundarios. |

### Superficies y fondos

| Token | Hex | Uso |
|:------|:----|:----|
| `{colors.background}` | `#FAFAF8` | Color de fondo principal. Base para maximizar la legibilidad y el contraste. |
| `{colors.background-alt}` | `#C7D5EB` | Color de fondo alternativo. Diferenciar secciones, tarjetas y áreas de contenido. |
| `{colors.background-muted}` | `#D9E3F2` | Color de fondo secundario. Contenedores, secciones diferenciadas y áreas de apoyo visual. |
| `{colors.text}` | `#1F2D45` | Color de texto principal. Cuerpos de texto, encabezados y elementos de máxima legibilidad. |
| `{colors.on-primary}` | `#FFFFFF` | Color sobre el primario. Texto blanco sobre fondos de color intenso. |

## Typography

El sistema tipográfico se compone de tres familias con funciones específicas que permiten equilibrar creatividad, personalidad y legibilidad dentro de la experiencia web.

- **Hypop-Heavy** es la tipografía principal de la marca y se utiliza para los encabezados de mayor jerarquía, aportando carácter, energía y reconocimiento visual.
- **NewYork** funciona como tipografía de apoyo para subtítulos, frases destacadas y elementos de énfasis, añadiendo dinamismo y contraste visual a la composición.
- **Avenir** es la tipografía base del sistema y se utiliza para el contenido general, navegación, botones y textos de lectura continua, garantizando claridad y comodidad para el usuario.

### Jerarquía

| Nivel | Token | Tamaño | Interlineado | Uso |
|:------|:------|:-------|:-------------|:----|
| Display | `{typography.display}` | 64 px | 72 px | Secciones más importantes y mensajes principales. |
| H1 | `{typography.h1}` | 48 px | 56 px | Encabezados de primer nivel. |
| H2 | `{typography.h2}` | 36 px | 44 px | Encabezados de segundo nivel. |
| H3 | `{typography.h3}` | 28 px | 36 px | Encabezados de tercer nivel. |
| H4 | `{typography.h4}` | 22 px | 30 px | Encabezados de cuarto nivel. |
| Body Large | `{typography.body-lg}` | 18 px | 28 px | Cuerpo principal de texto para lectura cómoda en dispositivos digitales. |
| Body Medium | `{typography.body-md}` | 16 px | 24 px | Texto secundario y contenido general. |
| Label | `{typography.label-md}` | 16 px | 24 px | Etiquetas de botones, elementos de navegación. |
| Caption | `{typography.caption}` | 14 px | 20 px | Etiquetas informativas y texto auxiliar. |

La jerarquía visual se construye principalmente mediante el tamaño, el peso y el color, evitando depender de cambios de opacidad para comunicar importancia. El cuerpo de texto nunca se presenta por debajo de 16 px, asegurando una lectura clara y cómoda en cualquier dispositivo.

## Layout

El sistema de layout se basa en una **unidad de 8 px**, lo que permite mantener consistencia entre todos los elementos de la interfaz.

### Escala de espaciado

Los valores de `{spacing.*}` siguen una progresión que respeta la unidad base:

| Token | Valor |
|:------|:------|
| `{spacing.3xs}` | 4 px |
| `{spacing.2xs}` | 8 px |
| `{spacing.xs}` | 12 px |
| `{spacing.sm}` | 16 px |
| `{spacing.md}` | 24 px |
| `{spacing.lg}` | 32 px |
| `{spacing.xl}` | 40 px |
| `{spacing.2xl}` | 48 px |
| `{spacing.3xl}` | 64 px |
| `{spacing.4xl}` | 80 px |
| `{spacing.5xl}` | 96 px |

Los botones y campos utilizan entre `{spacing.xs}` y `{spacing.sm}` de espacio interno. Las tarjetas y contenedores entre `{spacing.sm}` y `{spacing.md}`. Las secciones principales se separan entre `{spacing.3xl}` y `{spacing.5xl}` para mantener una composición clara sin generar espacios vacíos excesivos.

### Rejilla

El ancho máximo del contenido es de **1440 px**.

| Dispositivo | Columnas | Márgenes | Gutter |
|:------------|:---------|:---------|:-------|
| Escritorio (≥ 1024 px) | 12 | 64 px | 24 px |
| Tableta (600–1023 px) | 8 | 32 px | 24 px |
| Móvil (320–599 px) | 4 | 16 px | 16 px |

El espacio se utiliza de manera intencional para mantener equilibrio entre claridad y dinamismo. Los elementos relacionados se mantienen próximos entre sí, mientras que las distintas secciones cuentan con una separación mayor para establecer jerarquías visuales claras y facilitar la navegación.

## Elevation & Depth

La profundidad de la interfaz se mantiene sutil y controlada para priorizar el contenido, el color y la tipografía sobre los efectos visuales. La jerarquía se construye principalmente mediante color, tamaño y composición. Las sombras se utilizan únicamente para reforzar la interacción, indicar elevación o diferenciar capas dentro de la interfaz.

| Nivel | Sombra | Uso |
|:------|:-------|:----|
| Base | `none` | Elementos en estado base: secciones, campos de formulario, navegación, tarjetas estáticas. |
| Hover | `0 2px 8px rgba(0,0,0,0.08)` | Estados hover. Elevación ligera que aporta retroalimentación visual sin distraer. |
| Medium | `0 6px 16px rgba(0,0,0,0.12)` | Tarjetas destacadas, paneles de contenido y componentes interactivos. |
| High | `0 10px 24px rgba(0,0,0,0.16)` | Menús desplegables, ventanas emergentes y componentes flotantes. |
| Overlay | velo `40%–50%` opacidad | Modales y superposiciones. Genera enfoque sobre el contenido activo sin perder el contexto. |

El sistema evita sombras excesivamente profundas o efectos tridimensionales marcados; la intención es mantener una apariencia moderna, dinámica y profesional donde la profundidad complemente la experiencia visual sin competir con los elementos gráficos y la paleta de color.

## Shapes

Las formas de la interfaz combinan estructura y dinamismo para reflejar el carácter creativo de la marca.

| Token | Valor | Uso |
|:------|:------|:----|
| `{rounded.sm}` | 8 px | Componentes estándar: campos de formulario, contenedores generales. Aporta cercanía visual sin perder claridad ni modernidad. |
| `{rounded.md}` | 16 px | Elementos con mayor protagonismo: tarjetas destacadas, imágenes, contenedores especiales y llamados a la acción. Genera una apariencia más amigable y expresiva. |
| `{rounded.full}` | 9999 px | Elementos circulares: íconos, fotografías de perfil, indicadores y recursos gráficos específicos. Crea contraste dentro de la composición y aporta ritmo visual. |

La identidad incorpora formas orgánicas, curvas suaves y elementos decorativos inspirados en el movimiento y la creatividad. Estos motivos se inspiran en las curvas presentes en el monograma y en los recursos gráficos de la identidad visual. Se utilizan como elementos de apoyo en fondos, separadores, ilustraciones y detalles decorativos, reforzando una estética contemporánea, colorida y cercana. La combinación entre estructuras limpias y curvas orgánicas permite mantener una experiencia visual dinámica sin perder orden ni claridad.

## Components

### Botones

Los botones son un componente clave del sistema. Todos comparten estructura base pero varían en jerarquía visual.

**Botón principal** (`button-primary`): Utiliza `{colors.primary}` como fondo y `{colors.on-primary}` como texto. Tipografía `{typography.label-md}`, esquinas `{rounded.md}` y espaciado interno `14 px 24 px`. Al pasar el cursor, cambia a `{colors.primary-hover}` y adquiere la sombra `{shadow.hover}`. Al presionarlo, reduce ligeramente su escala. En estado deshabilitado, utiliza fondo gris claro y texto gris medio.

**Botón secundario** (`button-secondary`): Utiliza `{colors.secondary}` o `{colors.interactive}` como color principal según la jerarquía de la acción. Mantiene la misma estructura que el botón principal pero con menor protagonismo visual.

**Botón fantasma** (`button-ghost`): Fondo transparente, borde de 2 px en `{colors.secondary}` y texto del mismo color. Al pasar el cursor, el fondo adopta un tono azul muy claro y el borde adquiere mayor contraste.

### Tarjetas y contenedores

Las tarjetas de contenido utilizan fondos `{colors.background}` o `{colors.background-alt}`, con texto en `{colors.text}`. Incorporan esquinas `{rounded.md}` y espacios internos entre `{spacing.sm}` y `{spacing.md}`.

Las tarjetas pueden incluir bloques de color, formas decorativas, ilustraciones, stickers gráficos o elementos visuales complementarios inspirados en la identidad de la marca. Al pasar el cursor adquieren la elevación `card-hover` (`{shadow.medium}`).

### Campos y formularios

Los campos de texto utilizan fondo `{colors.on-primary}`, texto `{colors.text}` y tipografía `{typography.body-lg}`. Incorporan borde de 2 px en `{colors.background-alt}` y esquinas `{rounded.sm}`. Al enfocarlos, el borde cambia a `{colors.interactive}` y aparece la sombra de enfoque `input-focus`. Los placeholders utilizan un tono gris azulado de menor contraste. Las etiquetas utilizan tipografía `{typography.label-md}` con una separación clara respecto al campo.

### Navegación y enlaces

Los enlaces principales de navegación utilizan tipografía `{typography.label-md}` en `{colors.text}`. Al pasar el cursor cambian a `{colors.primary}` y pueden incorporar un subrayado o indicador visual de color. Los enlaces dentro del contenido utilizan `{colors.interactive}` para facilitar su identificación; en estado hover cambian a `{colors.primary}`.

### Elementos gráficos y destacados

La identidad incorpora etiquetas, stickers, badges y elementos decorativos inspirados en recursos editoriales y composiciones de diseño gráfico contemporáneo. Estos componentes utilizan colores vibrantes — `{colors.primary}`, `{colors.accent}` e `{colors.interactive}` — con esquinas `{rounded.full}`, tipografía `{typography.label-md}` y tamaños compactos para categorizar proyectos, habilidades, disciplinas o áreas de trabajo.

Los elementos destacados pueden combinar color, tipografía y formas orgánicas para crear puntos focales dentro de la interfaz, reforzando la personalidad creativa de la marca.

### Portafolio y proyectos

Las tarjetas de proyecto constituyen uno de los componentes principales de la interfaz. Utilizan imágenes amplias, bloques de color, títulos destacados en `{typography.display}` y subtítulos en `{typography.h3}`. Cada proyecto puede incorporar elementos gráficos complementarios como ilustraciones, formas orgánicas, líneas, stickers o etiquetas informativas. Al pasar el cursor, las tarjetas aumentan ligeramente su elevación y resaltan los elementos interactivos.

### Fotografía y avatar

Las imágenes de perfil utilizan formatos circulares (`{rounded.full}`) o formas orgánicas suavemente redondeadas. Las fotografías de proyectos ocupan un papel protagonista dentro de la composición y se combinan con bloques de color, recortes dinámicos y elementos gráficos complementarios para construir una experiencia visual expresiva y memorable.

## Do's and Don'ts

### Sí

- Utiliza `{colors.primary}` para los llamados a la acción principales, elementos destacados y momentos clave de interacción.
- Mantén `{colors.secondary}` como color de soporte para navegación, encabezados y contenido de alta jerarquía.
- Utiliza `{colors.interactive}` para enlaces, detalles interactivos y elementos de apoyo visual.
- Mantén un tamaño mínimo de 16 px para cualquier texto de lectura continua.
- Utiliza Avenir para todo el contenido funcional, navegación, botones y textos extensos.
- Reserva Hypop-Heavy para encabezados principales y mensajes de alto impacto.
- Utiliza NewYork únicamente para subtítulos, frases destacadas y elementos de énfasis.
- Mantén una separación mínima de `{spacing.3xl}` (64 px) entre secciones principales.
- Utiliza imágenes, ilustraciones y bloques de color como parte activa de la composición.
- Combina colores complementarios para generar contraste visual y dirigir la atención del usuario.
- Utiliza esquinas `{rounded.sm}` (8 px) y `{rounded.md}` (16 px) para mantener una apariencia amigable y contemporánea.
- Incorpora elementos gráficos decorativos como stickers, formas orgánicas, líneas, etiquetas o acentos visuales cuando aporten valor a la composición.
- Utiliza animaciones y efectos de interacción sutiles para reforzar la experiencia sin distraer del contenido.
- Prioriza siempre la legibilidad y la claridad antes que la decoración.

### No

- No utilices más de dos colores de énfasis principales dentro de un mismo componente.
- No emplees toda la paleta al mismo tiempo en una sola sección; permite que los colores respiren y mantengan jerarquía.
- No utilices Hypop-Heavy para párrafos, navegación o bloques extensos de texto.
- No abuses de NewYork en elementos funcionales o textos largos.
- No reduzcas el cuerpo de texto por debajo de 16 px.
- No utilices sombras excesivamente profundas ni efectos tridimensionales agresivos.
- No utilices degradados complejos o efectos visuales que compitan con el contenido principal.
- No satures la interfaz con elementos decorativos innecesarios.
- No coloques texto sobre imágenes o fondos de bajo contraste que afecten la legibilidad.
- No utilices más de tres niveles de énfasis visual dentro de una misma sección.
- No centres bloques largos de texto; utiliza alineación izquierda para favorecer la lectura.
- No utilices fotografías, ilustraciones o recursos visuales que no mantengan la estética colorida, creativa y contemporánea de la marca.
- No dependas únicamente del color para comunicar estados, jerarquías o interacciones.
- No sacrifiques la experiencia de usuario por priorizar únicamente la estética visual.

## Profundidad

El diseño mantiene una apariencia limpia y contemporánea, utilizando la profundidad únicamente para reforzar jerarquías e interacciones. La mayoría de los elementos permanecen en un plano visual ligero, permitiendo que el color, la tipografía y la composación sean los protagonistas.

Las tarjetas, galerías de proyectos y contenedores utilizan sombras suaves y difusas para separarse del fondo sin generar un efecto excesivamente tridimensional. Los estados hover incrementan ligeramente la elevación para comunicar interactividad.

Los niveles de profundidad son:

- **Plano (sin sombra):** textos, navegación y elementos gráficos decorativos.
- **Elevación sutil:** tarjetas de contenido y miniaturas de proyectos.
- **Elevación media:** botones activos, galerías destacadas y contenedores interactivos.
- **Elevación alta:** modales, menús desplegables y elementos superpuestos.

Las sombras siempre deben ser suaves, amplias y con baja opacidad. Se evita el uso de sombras duras, biseles, efectos glossy o estilos skeuomórficos. La sensación general debe ser moderna y enfocada en el contenido visual.

## Formas

Las formas de la interfaz combinan estructura y fluidez. Los contenedores principales utilizan esquinas redondeadas de 16px para generar una apariencia amigable y contemporánea, mientras que algunos elementos destacados pueden aumentar hasta 24px o 32px para reforzar el carácter dinámico de la marca.

Los círculos tienen un papel importante dentro del sistema visual y aparecen en fotografías de perfil, imágenes destacadas, botones de ícono, etiquetas visuales y elementos decorativos distribuidos a lo largo de la página. Estos elementos ayudan a suavizar la composición y aportan movimiento sin perder claridad.

Los botones utilizan esquinas redondeadas tipo píldora para reforzar la sensación de cercanía e interacción. Las tarjetas de proyectos mantienen radios moderados que equilibran profesionalismo y creatividad.

Como recurso gráfico complementario, se utilizan formas circulares, ondas, curvas suaves y elementos geométricos simples inspirados en la exploración visual del diseño gráfico contemporáneo. Estas formas funcionan como acentos decorativos y ayudan a dirigir la atención dentro de la composición.

Se evitan las formas excesivamente rígidas, los bordes agresivos y los elementos visuales demasiado técnicos. El objetivo es mantener una estética expresiva, colorida y accesible que refleje una personalidad creativa sin comprometer la legibilidad ni la experiencia de usuario.

La identidad debe sentirse creativa, vibrante, cercana y dinámica, pero siempre organizada. El color, la tipografía y los elementos gráficos funcionan como protagonistas de la experiencia, mientras que la estructura y la legibilidad mantienen el equilibrio para evitar una composición caótica o sobrecargada.
