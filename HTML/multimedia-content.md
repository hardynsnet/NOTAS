# Contenido multimedia en HTML

## Etiqueta VIDEO
<p>Es usada para reproducir clips de vídeo, es un elemento de bloque que contiene múltiples fuentes de vídeo para asegurar la compatibilidad entre navegadores, tiene controles como:</p>

- controls: Añade la interfaz de reproducción (reproducir, pausa, volumen)
- autoplay: Inicia el vídeo automáticamente (cuenta con un atributo muted para funcionar)
- loop: Repite el vídeo al finalizar
- poster: Define una imagen miniatura antes que inicie el vídeo

## Etiqueta AUDIOS
<p>Funciona como la etiqueta video, pero... es para archivos de sonido, tiene controles como:</p>

- controls: Indispensable para que el usuario vea el reproductos
- muted: Silencia el audio por defecto
- preload: Indica si el navegador debe descargar el archivo al cargar la página (auto, metadata, none)

## Etiquetas de Soporte (Source y Track)
<p>Son etiquetas que se anidan dentro de las etiquetas audio y video para expandir sus capacidades, siendo así:</p>

- source: Permite especificar mpultiples archivos de medios. El navegador por defecto elige el primero que sea capaz de reproducir
- track: Se usa para añadir subtitulos, descripciones o capitulos mediante archivos en formato '.vtt' (Web Video Text Tracks).

## Etiqueta IFRAME
<p>Generalmente es usada para muchas cosas, en multimedia es la forma estándar de insertar contenido de terceros, como videos de YouTube, o mapas de Google Maps. Lo que crea una ventana independiente dentro de la página.</p>

[Ver ejemplo](/HTML/multimedia-content-test.html)

