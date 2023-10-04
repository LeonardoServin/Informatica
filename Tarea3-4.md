# PARTICIONES Y SISTEMAS DE ARCHIVOS

**Para revisar qué es una particion física y lógica de arranque, y qués es GPT Y MBR, revisar [3.2, Conceptos Involucrados](Tarea3-2.md)**

## Fromatear un dispositivo de almacenamiento

1. **Copia los datos importantes**: Antes de formatear, asegúrate de hacer copias de seguridad de todos los datos importantes en el dispositivo, ya que el proceso de formateo borrará todos los archivos.

2. **Conecta el dispositivo**: Asegúrate de que el dispositivo de almacenamiento esté conectado correctamente a tu computadora, ya sea a través de USB, SATA u otro medio.

3. **Abre la herramienta de administración de discos**: En sistemas Windows, puedes abrir la "Administración de discos" desde el Panel de control o haciendo clic con el botón derecho en el menú "Este equipo" y seleccionando "Administrar". En sistemas macOS, utiliza la "Utilidad de Discos" que se encuentra en "Aplicaciones" > "Utilidades".

4. **Selecciona el dispositivo**: En la herramienta de administración de discos, selecciona el dispositivo de almacenamiento que deseas formatear. Asegúrate de seleccionar el dispositivo correcto, ya que el formateo borrará todos los datos en él.

5. **Inicia el proceso de formateo**: Busca la opción para formatear o borrar el dispositivo. Dependiendo del sistema operativo y la herramienta de administración de discos, esto podría llamarse "Formatear", "Borrar", "Crear nueva partición" o algo similar.

6. **Selecciona el sistema de archivos**: Durante el proceso de formateo, se te pedirá que elijas un sistema de archivos. Los sistemas más comunes son NTFS (Windows), HFS+ (macOS) y FAT32 (compatible con múltiples sistemas operativos). Selecciona el sistema de archivos apropiado para tus necesidades.

7. **Confirma y comienza el formateo**: Una vez que hayas seleccionado el sistema de archivos y confirmado que deseas formatear el dispositivo, inicia el proceso. Dependiendo del tamaño del dispositivo y la velocidad de tu computadora, esto puede llevar algún tiempo.

8. **Finaliza el formateo**: Una vez que se complete el proceso de formateo, recibirás una notificación de que el dispositivo ha sido formateado con éxito. Puedes cerrar la herramienta de administración de discos.

## Sistema de archivos

Un sistema de archivos es una estructura y conjunto de reglas que un sistema operativo utiliza para organizar, almacenar y acceder a archivos y datos en un dispositivo de almacenamiento, como un disco duro o una unidad USB. Define cómo se almacenan los datos, cómo se nombran los archivos, cómo se accede a ellos y cómo se gestionan los permisos de acceso. Los sistemas de archivos son esenciales para el funcionamiento de cualquier sistema de almacenamiento de datos en una computadora.

## Archivo

Un archivo es un conjunto organizado de datos o información almacenada en un medio de almacenamiento, como un disco duro, una memoria USB o una unidad de almacenamiento en la nube. Los archivos pueden contener diferentes tipos de información, como texto, imágenes, videos, programas informáticos u otros tipos de datos, y se utilizan para almacenar y gestionar información de manera ordenada y accesible para su posterior uso o referencia.

## Tipos de archivos

Existen varios tipos de archivos, y se pueden clasificar en categorías amplias según su contenido y uso principal:

1. Archivos de texto: Contienen texto legible, como documentos, notas, código fuente y hojas de cálculo en formatos como TXT, DOCX, PDF o CSV.

2. Archivos de imagen: Almacenan datos de imágenes, como fotografías y gráficos, en formatos como JPG, PNG, GIF o BMP.

3. Archivos de audio: Contienen datos de audio, como música o grabaciones, en formatos como MP3, WAV, FLAC o AAC.

4. Archivos de video: Guardan contenido de video, como películas o clips, en formatos como MP4, AVI, MKV o MOV.

5. Archivos ejecutables: Son programas informáticos que se pueden ejecutar en una computadora. Los archivos .exe en Windows son ejemplos comunes.

6. Archivos comprimidos: Contienen datos comprimidos para ahorrar espacio de almacenamiento y facilitar la transferencia. Ejemplos incluyen archivos ZIP, RAR o 7Z.

7. Archivos de sistema: Estos archivos son esenciales para el funcionamiento de un sistema operativo y programas. Los usuarios normales generalmente no deben modificarlos.

8. Archivos de configuración: Almacenan configuraciones y preferencias de aplicaciones y sistemas, como archivos .ini o .config.

9. Archivos de archivo: Son contenedores que agrupan varios archivos en uno solo. Ejemplos incluyen archivos TAR, ZIP o ISO.

Estos son solo algunos ejemplos de tipos de archivos, y existen muchos otros formatos especializados según las necesidades de almacenamiento y procesamiento de datos.

## Como se guarda un archivo

1. Abre la aplicación o programa adecuado para editar o crear el tipo de archivo que deseas guardar.

2. Edita o crea el contenido del archivo según tus necesidades.

3. Haz clic en la opción "Guardar" o "Guardar como" en el menú del programa. La ubicación y el nombre del archivo se te pedirán en este punto.

4. Elige la ubicación donde deseas guardar el archivo en tu computadora o en la nube. Puedes seleccionar una carpeta específica.

5. Asigna un nombre al archivo y selecciona el formato de archivo adecuado si es necesario. Algunos programas pueden seleccionar el formato automáticamente.

6. Haz clic en "Guardar" para confirmar y almacenar el archivo en la ubicación seleccionada.

7. Asegúrate de recordar la ubicación donde guardaste el archivo para poder acceder a él cuando lo necesites.

El proceso exacto puede variar según el programa que estés utilizando y el sistema operativo de tu computadora.

## Operaciones de manejo de archivos

Las operaciones de manejo de archivos son acciones que permiten gestionar la creación, lectura, escritura, modificación y eliminación de archivos en un sistema informático. Estas operaciones son esenciales para administrar datos y documentos, lo que incluye la creación de nuevos archivos, la lectura de información desde archivos existentes, la actualización de datos en archivos y la eliminación de archivos que ya no son necesarios.


## Disk Management

Es una utilidad de administración de discos en sistemas Windows que nos permite realizar diversas tareas relacionadas con el almacenamiento de datos, como la creación, formateo, redimensionamiento y eliminación de particiones en unidades de disco duro y unidades de estado sólido. En resumen, Disk Management es una herramienta poderosa para gestionar el almacenamiento en tu computadora Windows y garantizar que tus discos y particiones estén configurados de manera eficiente y segura.

## GParted Live

Es una distribución de Linux que proporciona muchas herramientas de gestión de particiones y discos. También nos permite crear, modificar, redimensionar y eliminar particiones en discos duros y unidades de estado sólido. Además, puede utilizarse para realizar copias de seguridad y restauraciones de datos, así como para administrar sistemas de archivos. GParted Live es una herramienta para gestionar el almacenamiento y las particiones en sistemas Linux y puede ser muy útil para tareas de mantenimiento y recuperación de datos.

## Disk Management vs GParted Live

Disk Management y GParted Live son dos herramientas de administración de almacenamiento, pero se diferencian en algunos aspectos clave:

1. Plataforma:
   - Disk Management: Es una herramienta nativa de Windows y está disponible en sistemas Windows.
   - GParted Live: Es una distribución de Linux que se inicia desde un medio externo, como un USB o un CD/DVD, por lo que es más versátil y puede utilizarse en sistemas Windows y Linux.

2. Interfaz de usuario:
   - Disk Management: Tiene una interfaz gráfica de usuario (GUI) integrada en el sistema operativo Windows, lo que facilita su uso para usuarios de Windows.
   - GParted Live: Utiliza una interfaz gráfica basada en Linux, que puede ser menos familiar para usuarios de Windows pero ofrece funciones avanzadas de gestión de particiones.

3. Funcionalidad:
   - Disk Management: Ofrece funciones básicas de administración de discos y particiones, como crear, eliminar, formatear y asignar letras de unidad a las particiones. Está diseñado principalmente para tareas simples.
   - GParted Live: Proporciona una amplia gama de funciones avanzadas, como redimensionamiento de particiones, cambio de sistemas de archivos, copia de particiones y más. Es más adecuado para tareas de administración de almacenamiento complejas.

4. Sistema operativo:
   - Disk Management: Se integra directamente con Windows y es fácil de usar en ese entorno.
   - GParted Live: Es una opción versátil para trabajar en sistemas Linux o realizar tareas de administración de particiones en sistemas Windows y Linux.

Disk Management es más adecuado para tareas simples de administración de discos en sistemas Windows, mientras que GParted Live es una herramienta más potente y versátil que se puede utilizar en una variedad de sistemas operativos, incluidos Windows y Linux, y es especialmente útil para tareas de gestión de particiones más complejas.


> [Volver](Tarea3-3.md)

> [Pag. Principla](README.md)
