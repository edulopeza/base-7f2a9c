# Cómo cargar este paquete en GitHub

## 1. Preparar el repositorio

1. En GitHub, crea un repositorio nuevo.
2. Para mantener el identificador neutro previsto por el proyecto, evita nombres como `CAE`, `prevencion`, el título del libro o palabras clave comerciales. Puedes escoger un identificador opaco, por ejemplo `r-7f2a9c`, si está disponible.
3. Decide si será público o privado. Si la promesa del libro es proporcionar descargas a cualquier lector, un repositorio público facilita el acceso, pero cualquier persona podrá compartir la URL. Un repositorio público no permite restringir el acceso solo a compradores.
4. Antes de publicar, revisa `DERECHOS_Y_USO_PENDIENTE.md` y decide las condiciones de uso. No selecciones automáticamente una licencia abierta si no deseas conceder esos derechos.

## 2. Subir los archivos desde la web de GitHub

1. Descomprime el ZIP en tu ordenador.
2. Abre el repositorio vacío en GitHub.
3. Selecciona **Add file → Upload files**.
4. Arrastra el contenido de la carpeta (no hace falta subir la carpeta contenedora con el ZIP dentro).
5. Comprueba que `README.md`, `plantillas_word/` y `registros_excel/` aparecen en la raíz.
6. Escribe un mensaje de confirmación, por ejemplo `Añade paquete inicial de herramientas editables` y confirma la carga.
7. Descarga desde GitHub uno de los DOCX y el XLSX para comprobar que se abren correctamente.

## 3. Antes de publicar el libro

- Sustituye el marcador de la última página del manuscrito por la URL real del repositorio, cuando esté creado y comprobado.
- Comprueba la URL en una ventana privada y desde un dispositivo distinto.
- Verifica que el repositorio contiene únicamente plantillas vacías, nunca expedientes reales ni datos personales.
- Revisa que los nombres y códigos R01–R20 coincidan con los del manuscrito.
- Anota la fecha y el número de versión del paquete.

## 4. Actualizaciones

Mantén un `CHANGELOG.md` sencillo con versión, fecha y archivos modificados. Cuando actualices una plantilla, verifica que las instrucciones del libro siguen siendo correctas. Si una modificación deriva de un cambio legal, cita la fuente oficial y solicita revisión profesional en caso de duda.

## 5. Aviso

Este documento explica la carga manual. No he creado, publicado ni verificado un repositorio remoto en tu cuenta. Debes hacerlo tú desde tu cuenta de GitHub.
