# Pagos de mi auto: generar el APK

1. Crea un repositorio nuevo en GitHub (privado está bien) y sube todo el contenido de esta carpeta, incluida la carpeta oculta .github.
2. En el repositorio, entra a la pestaña Actions. El flujo "Build APK" corre solo al subir los archivos (o con "Run workflow").
3. Cuando termine (unos 5 a 8 minutos), abre la ejecución y descarga el archivo "pagos-de-mi-auto-apk" de la sección Artifacts. Dentro viene app-debug.apk.
4. Pásalo al teléfono, ábrelo y permite "instalar apps de fuentes desconocidas" si Android lo pide.

Los datos de la app se guardan en el teléfono. Son independientes de los de la versión web.
