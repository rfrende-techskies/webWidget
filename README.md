# Test de Micrófono

Una simple aplicación web para probar la grabación de audio usando el micrófono del dispositivo.

## Características

- Grabación de audio usando el micrófono
- Reproducción del audio grabado
- Interfaz simple y fácil de usar

## Despliegue en Netlify

Para desplegar esta aplicación en Netlify:

1. Crea una cuenta en [Netlify](https://www.netlify.com/) si aún no tienes una
2. Desde el dashboard de Netlify, haz clic en "Add new site" > "Import an existing project"
3. Conecta con tu repositorio de GitHub
4. Selecciona este repositorio
5. La configuración de despliegue ya está incluida en el archivo `netlify.toml`
6. Haz clic en "Deploy site"

## Uso Local

Para probar localmente, simplemente abre el archivo `index.html` en tu navegador web.

**Nota**: Para usar el micrófono, el sitio debe servirse a través de HTTPS (lo cual Netlify proporciona automáticamente) o desde `localhost`. 