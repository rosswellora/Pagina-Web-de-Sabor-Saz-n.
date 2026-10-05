# Sabor & Sazon — Landing Page Gastronomica

Landing page moderna y responsiva para **Sabor & Sazon**, un restaurante de cocina artesanal que destaca por su ambiente acogedor, ingredientes frescos y opciones gourmet. 

El sitio cuenta con una arquitectura optimizada para la conversion, facilitando la visualizacion de los platos mas populares y la reserva inmediata de mesas.

---

## Caracteristicas del Sitio

- **Soporte de Modo Oscuro Nativo:** Implementado mediante variables CSS dinamicas asignadas a la clase `.theme-dark`, permitiendo una transicion fluida entre interfaces claras y oscuras.
- **Diseño Adaptable (Responsive):** Estructura fluida basada en CSS Grid y Media Queries que reorganiza los elementos en una sola columna para pantallas de smartphones y tablets.
- **Arquitectura Semantica:** Uso correcto de etiquetas HTML5 para garantizar un mejor rendimiento en SEO y una navegacion accesible.
- **Estetica Gastronomica Calida:** Paleta cromatica fundamentada en tonos tierra, maderas y acentos naranjas (`--accent`), ideal para negocios de restauracion.

---

## Paleta de Colores y Temas (Variables CSS)

El proyecto gestiona dos esquemas de color independientes mediante `:root` y la clase `.theme-dark`:

| Variable CSS | Modo Claro (Por defecto) | Modo Oscuro (`.theme-dark`) | Aplicacion Principal |
| :--- | :--- | :--- | :--- |
| `--bg-color` | `#f7f2eb` (Crema) | `#171513` (Carbon) | Fondo general de la pagina. |
| `--panel-color` | `#fffdf9` (Blanco calido) | `#221d1a` (Marron oscuro) | Tarjetas de menu y bloques de contenido. |
| `--panel-alt` | `#f3e4d5` (Arena) | `#2d2724` (Marron medio) | Botones secundarios y fondos promocionales. |
| `--text-color` | `#1d1d1d` (Negro suave) | `#f4efe9` (Hueso) | Textos principales y titulos. |
| `--accent` | `#d9772f` (Naranja siena) | `#f0b15c` (Ocre) | Boton de cambio de tema y llamadas a la accion. |
| `--accent-dark` | `#b75d1c` (Terracota) | `#d68c32` (Dorado oscuro) | Precios, subtitulos e interacciones hover. |

---

## Estructura de Secciones (HTML)

1. **Header:** Logotipo de la marca, menu de navegacion principal (`Inicio`, `Menu`, `Nosotros`, `Reservas`) y el boton interactivo para alternar el modo oscuro.
2. **Hero Section:** Mensaje introductorio destacado ("Sabores que hacen que cada comida se recuerde"), botones de accion rapida y una tarjeta visual que promociona el especial del dia (Pasta al estilo de la casa).
3. **Features (Pilares del Servicio):** Tres bloques independientes que comunican los valores de la marca: Platos frescos, Chef experto y Atencion rapida.
4. **Menu Section (Lo mas pedido):** Rejilla de productos con imagenes y precios para los platos estrella: Risotto de hongos, Filete a la parrilla y Ensalada de la temporada.
5. **Promo / CTA Section:** Bloque de reserva directa para invitar al usuario a asegurar su mesa.
6. **Footer:** Espacio dedicado a los derechos reservados e informacion de cierre.

---

## Tecnologias Utilizadas

- **HTML5:** Estructura limpia y semantica para la correcta indexacion en buscadores.
- **CSS3 Avanzado:** Uso de variables customizadas (`var(--css)`), CSS Grid para distribucion asimetrica, Flexbox para alineaciones y transiciones de color optimizadas.
- **Tipografia:** Uso de fuentes de sistema sin serifa (Arial, sans-serif) para asegurar tiempos de carga minimos.

---

## Configuracion y Despliegue Local

Para clonar y visualizar esta landing page de forma local en tu equipo, ejecuta los siguientes comandos en tu terminal:

1. **Clonar el proyecto:**
   ```bash
   git clone https://github.com
   ```

2. **Acceder a la carpeta:**
   ```bash
   cd sabor-sazon-landing
   ```

3. **Ejecutar el archivo principal:**
   Abre el archivo `index.html` directamente en tu navegador web de preferencia o inicializalo con un servidor local de desarrollo.
