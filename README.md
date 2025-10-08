# Sistema de Flowbite
Página experimental realizada con HTML, JS y Tailwind CSS con Flowbite de negocios informáticos. <br>
Este proyecto ha sido desplegado en Netlify con la siguiente dirección. https://variado-css-flowbite-course.netlify.app/

<hr>
<img src="preview/miniaturas.jpg">
<hr>

# Requerimientos
- Node.js (Utilizado: 20.17.0, recomendado: 18.x o superior)
- pnpm (Utilizado: 8.12.1, compatible con 10.x)

<hr>

# Recomendado
- VSCode con extensión Tailwind CSS IntelliSense para autocompletado y sugerencias.
- Live Preview o servidor local para visualizar correctamente las rutas.

<hr>

# Dependencias
- Este proyecto utiliza únicamente HTML, JS y Tailwind CSS.
- Se incluye la utilización de la librería Flowbite.
- Las dependencias instaladas vía pnpm son:
  - tailwindcss
  - @tailwindcss/cli
  - flowbite

<hr>

# Instalación
### 1. Clona el repositorio
Utiliza tu gestor git de preferencia (ej: GitHub Desktop) o clona desde la terminal.
```bash
git clone https://github.com/tu-usuario/variado-css-flowbite-course.git
cd variado-css-flowbite-course
```

### 2. Instala las dependencias
```bash
pnpm install
```

### 3. Script personalizado en `package.json`
Utilizado para poder compilar estilos con Tailwind en tiempo real y visualizar (ej: con Live Server)
```bash
"scripts": {
	"build:styles": "pnpx @tailwindcss/cli -i ./css/input.css -o ./css/output.css --watch"
}
```
```bash
pnpm --run build:styles
```
# Observaciones y comentarios
###  Estilos
- Se guardó en assets una copia de flowbite.min.js para el deploy a la plataforma Netlify.<br>
- Los estilos se compilan desde input.css usando Tailwind CLI.
