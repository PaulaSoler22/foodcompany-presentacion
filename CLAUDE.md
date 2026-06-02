# CompanyGame FoodCompany - Presentación Interactiva

## Descripción del Proyecto

Presentación interactiva HTML/CSS/JS para el simulador de negocios **FoodCompany** de la plataforma **CompanyGame**, distribuido por **Simuladores de Negocios Colombia** (Grupo Edutec).

**Público objetivo:** Estudiantes universitarios que van a participar en la simulación.

**Propósito:** Guía de bienvenida y orientación antes de iniciar la competencia en el simulador.

## Tecnología

- **Frontend**: HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- **Tipografía**: Google Fonts (Montserrat + Open Sans)
- **Arquitectura**: Single-page application con sistema de slides interactivo
- **Imágenes**: Usar URLs externas o placeholders SVG inline

## Paleta de Colores (Identidad FoodCompany)

Basada en el branding oficial del simulador FoodCompany de CompanyGame.

```css
:root {
  /* Colores principales FoodCompany */
  --primary: #F58220;          /* Naranja principal (logo FoodCompany) */
  --primary-dark: #E06D10;     /* Naranja oscuro (hover, acentos) */
  --primary-light: #FDEBD0;    /* Naranja muy claro (fondos suaves) */
  --secondary: #F9A825;        /* Ámbar/Amarillo (acentos cálidos) */
  --accent-green: #7BC143;     /* Verde del logo (feather verde) */
  --accent-teal: #00B4D8;      /* Azul/teal del logo (feather azul) */
  
  /* Fondos */
  --bg-warm: #FFF8F0;          /* Fondo cálido crema */
  --bg-white: #FFFFFF;         /* Fondo blanco */
  --bg-card: #FFFFFF;          /* Cards */
  --bg-section: #FFF3E6;       /* Secciones alternas */
  
  /* Texto */
  --text-dark: #2D2D2D;        /* Títulos */
  --text-body: #444444;        /* Cuerpo */
  --text-muted: #777777;       /* Secundario */
  --text-white: #FFFFFF;       /* Sobre fondos oscuros */
  
  /* CompanyGame corporativo */
  --cg-blue: #1A5276;          /* Azul CompanyGame */
  --cg-blue-light: #2E86C1;    /* Azul CompanyGame claro */
}
```

## Estructura del Proyecto

```
foodcompany-presentacion/
├── CLAUDE.md          # Este archivo - documentación del proyecto
├── README.md          # Documentación general
└── index.html         # Presentación completa (HTML/CSS/JS embebido)
```

## Estructura de la Presentación (12 Slides)

| # | Slide | Contenido | Tipo |
|---|-------|-----------|------|
| 1 | 🥛 Portada FoodCompany | Logo, título, subtítulo, branding | Específico |
| 2 | 🏭 ¿Qué es FoodCompany? | Descripción del simulador, sector lácteo, misión del participante | Específico |
| 3 | 🎮 Cartelera de Simuladores | Catálogo de simuladores disponibles (CompanyGame + otros) | General |
| 4 | 🔗 Cadena de Valor | Producción → Producto → Comercialización → Segmentos | Específico |
| 5 | 🐄 Producción y Proveedores | Proceso productivo, 3 proveedores de leche, ratios, inventarios | Específico |
| 6 | ⚙️ Áreas de Decisión | Las 12+ áreas de decisión del simulador | Específico |
| 7 | 🎯 Segmentos y Competitividad | 3 segmentos, 3 canales, 4 factores de competitividad con ponderación | Específico |
| 8 | 📊 Cuadro de Mando | Dashboard con KPIs clave, cuenta de resultados, balance | Específico |
| 9 | 🏆 Valor de la Compañía | Fórmula del ranking: 45% resultados + 12% marca + 12% producto + etc. | Específico |
| 10 | 📚 Métodos de Implementación | Presencial, virtual, híbrido, intensivo | General |
| 11 | ❓ Preguntas Frecuentes | FAQ para estudiantes | General |
| 12 | 🙏 Ingreso a Plataforma + Gracias | URL de acceso, contacto, cierre | General |

## Contenido Detallado por Slide

### Slide 1 - Portada
- Logo FoodCompany (naranja con feathers verde/azul)
- "Simulador de Gestión de una Empresa Productora del Sector Lácteo"
- Logo CompanyGame abajo
- Branding "Simuladores de Negocios Colombia"

### Slide 2 - ¿Qué es FoodCompany?
- Sector lácteo: sector maduro, competitivo, márgenes reducidos
- Simulador de gestión empresarial nivel 4
- Temáticas: Estrategia, Marketing, Operaciones, Finanzas
- Modalidad: Competitivo (varias empresas compiten entre sí)
- Tiempo: 16 a 32 horas
- 3 líneas de producto: Leche, Yogur, Queso Fresco
- Escenario macroeconómico: PIB, IPC, Tipo de Interés, Confianza Económica

### Slide 3 - Cartelera de Simuladores
Simuladores ofrecidos por Simuladores de Negocios Colombia:
- **CompanyGame**: FoodCompany, BusinessGlobal, MarkStrat, SimBrand, StartUp, GreenTech, entre otros
- **SimVenture**: SimVenture Classic, SimVenture Evolution
- **LABSAG**: Simpro, Marklog, Tenpomatic, Simdef, Brandestrat
- **SimProject / SimAgile**: Gestión de proyectos
- Mostrar como grid de tarjetas con logos/iconos

### Slide 4 - Cadena de Valor
Flujo visual: PRODUCCIÓN → PRODUCTO-PRECIO-PROMOCIÓN → COMERCIALIZACIÓN → SEGMENTOS
- **Producción**: Ganaderos → Recogida leche → Elaboración → Envasado → Almacenaje
- **Producto**: Precio, Gama, Marca, Packaging, Calidad
- **Comercialización**: Descuento al canal, Promoción PdV, Modalidad distribución
- **Segmentos**: Niños/Jóvenes, Adultos, Healthy
- **Financiación**: Préstamo LP, Préstamo CP, Plazo pago proveedores, Plazo cobro clientes

### Slide 5 - Producción y Proveedores
- **3 Proveedores de leche** (tipo de vaca):
  - Frisona: 0,32€/litro (menor calidad, menor costo)
  - Fleckviek: 0,38€/litro (calidad media)
  - Parda Alpina: 0,46€/litro (mayor calidad, mayor costo)
- **Ratios de producción**:
  - 1L leche = 1L materia prima
  - 1L yogur = 1,2L leche
  - 1kg queso = 5L leche
- **Gestión de inventarios**: Productos perecederos, caducan si no se venden en Q1 del año siguiente
- **Capacidad de fábrica**: Elaboración y Envasado tienen capacidades independientes, ampliables
- **Amplitud de gama**: Leche 1-3, Yogur 1-15, Queso 1-5

### Slide 6 - Áreas de Decisión
12 áreas organizadas en categorías:
- **Producción**: Compra materia prima, Planificar producción, Ampliación capacidad, Gasto mantenimiento
- **Producto**: Amplitud de gama, Calidad producto, Packaging, Selección proveedor
- **Precio y Ventas**: Precios por producto, Descuento por canal
- **Promoción/Marca**: Promoción de marca, Promoción punto de venta, Priorización segmentos
- **Distribución**: Modalidad de distribución (1 a 5)
- **Financiación**: Préstamo LP (hasta 4M), Préstamo CP (hasta 500K), Plazos cobro/pago

### Slide 7 - Segmentos y Factores de Competitividad
**3 Segmentos de demanda:**
- Niños y Jóvenes (hasta 18 años): Sabor, nutrición y calidad
- Adultos (18+): Calidad, salud y nutrición  
- Healthy: Dieta, salud y calidad

**3 Canales de distribución:**
- Tienda Tradicional: comercios de proximidad
- Gran Superficie: amplia oferta, grandes espacios
- Hostelería (HORECA): hoteles, restaurantes, hospitales, colegios

**4 Factores de competitividad** (tabla con ponderación por puntos):
|              | Niños/Jóvenes | Adultos | Healthy |
|--------------|:---:|:---:|:---:|
| PRECIO       | ●●●●● | ●●●● | ●●● |
| MARCA        | ●●● | ●●●●● | ●●●● |
| PRODUCTO     | ●●●● | ●●●● | ●●●●● |
| COBERTURA    | ●●●● | ●●● | ●●● |

### Slide 8 - Cuadro de Mando
KPIs principales del simulador:
- Unidades Vendidas (litros/kilos)
- Participación de Mercado (%)
- Ingresos Totales
- Utilidad Bruta y Neta
- Ratio Utilidad Bruta sobre Ingresos (%)
- Rentabilidad sobre Patrimonio (%)
- Endeudamiento
- Tasa Ocupación Fábrica (%)
- Inventario sobre Ventas (%)
- Nivel de Eficiencia (1-10)
- Valor de Marca (1-100)
- Valor de Producto (1-10)
- Cobertura Distribución (%)

Estructura Cuenta de Resultados: Ingresos → Costes Ventas → Margen → Gastos Operaciones → Resultado Bruto → Depreciación y Financieros → Resultado Neto → Impuestos → Resultado después Impuestos

### Slide 9 - Valor de la Compañía
Métrica principal de evaluación. Objetivo: incrementar al menos 7% cada periodo.

Composición del Valor de la Compañía:
- **45%** Resultados Económicos (beneficios, evolución últimos periodos)
- **12%** Participación de Mercado (cuota en diferentes productos)
- **12%** Valor de Producto (escala 1-10)
- **12%** Valor de Marca (escala 10-100)
- **7%** Cobertura de Distribución (% puntos de venta)
- **6%** Eficiencia Productiva (nivel de eficiencia producción)
- **6%** Rentabilidad y Solvencia (ratios financieros)

### Slide 10 - Métodos de Implementación (General)
- **Presencial**: Sesiones en aula con facilitador, ideal para debriefing grupal
- **Virtual sincrónico**: Sesiones por videollamada con facilitador en tiempo real
- **Virtual asincrónico**: Avance autónomo con plazos definidos por periodo
- **Intensivo (Business Game)**: Jornada completa de 8+ horas, competencia concentrada
- **Híbrido**: Combinación de sesiones presenciales y trabajo autónomo

### Slide 11 - Preguntas Frecuentes (General)
- ¿Cuántos periodos tiene la simulación? → Depende de la configuración del profesor (típicamente 6-10 periodos)
- ¿Cómo se forman los equipos? → El profesor asigna equipos de 3-5 personas
- ¿Puedo cambiar mis decisiones? → Sí, hasta que cierre el periodo
- ¿Qué pasa si no envío decisiones? → Se repiten las del periodo anterior
- ¿Cómo se evalúa? → Valor de Compañía es la métrica principal
- ¿Necesito conocimientos previos? → No, el simulador es intuitivo. El manual te guía.

### Slide 12 - Ingreso a Plataforma + Gracias
- URL de acceso: **app.companygame.com**
- Credenciales proporcionadas por el profesor
- Contacto: soporte@companygame.com
- Logo Simuladores de Negocios Colombia
- Logo CompanyGame
- "¡Buena suerte en la competencia!"

## Funcionalidades de la Presentación

### Navegación
- Flechas izquierda/derecha para avanzar/retroceder
- Indicadores de progreso (dots) clickeables
- Teclas de teclado (← →) para navegación
- Transiciones suaves entre slides

### Interactividad
- Cards con hover effects
- Elementos con animaciones de entrada (fade-in, slide-up)
- Tabla de factores de competitividad interactiva
- Indicador de slide actual / total

### Responsive
- Adaptable a pantallas grandes y proyectores
- Funcional en tablets para presentaciones individuales

## Instrucciones para Mejoras en Claude Code

Si necesitas modificar la presentación:

1. **Cambiar contenido**: Editar directamente el HTML dentro de cada `<section class="slide">`. Cada slide tiene un `id` único (slide-1, slide-2, etc.)
2. **Cambiar colores**: Modificar las variables CSS en `:root`
3. **Agregar slides**: Duplicar una `<section class="slide">`, cambiar el id, y actualizar el contador en JS
4. **Cambiar tipografías**: Modificar los imports de Google Fonts y las variables CSS
5. **Agregar imágenes**: Insertar `<img>` tags con URLs externas o convertir a base64 para embeber

## Contexto de Negocio

**Simuladores de Negocios Colombia** es el distribuidor autorizado de CompanyGame en Colombia. Comercializa simuladores de gestión empresarial a universidades colombianas. El contacto principal es Carlos González, Director Comercial de Grupo Edutec (empresa matriz), basado en Bogotá.

Los simuladores se implementan en programas de Administración de Empresas, Economía, Ingeniería Industrial, Comercio Internacional, y programas afines. FoodCompany es ideal para cursos de Marketing, Gerencia, Estrategia Empresarial y Gestión de Operaciones.
