# INSTALACIÓN DE SISTEMAS OPERATIVOS EN UN MEDIO EXTRAÍBLE

#### ¿Qué es un sistema operativo (SO)?

Un sistema operativo es un software fundamental que gestiona los recursos de hardware y proporciona servicios esenciales para que otros programas funcionen en una computadora. Actúa como intermediario entre el hardware y las aplicaciones, permitiendo la ejecución de tareas como la gestión de archivos, la administración de memoria y la interacción con dispositivos periféricos.

Tipos de SO:

1. **Microsoft Windows**: Microsoft Windows es uno de los sistemas operativos de escritorio más populares y ampliamente utilizados en el mundo. Ejemplos de versiones de Windows incluyen Windows 10 y Windows 11.

2. **macOS**: macOS es el sistema operativo de escritorio desarrollado por Apple para sus computadoras Mac. Ofrece una interfaz elegante y es conocido por su integración con hardware y software de Apple.

3. **Linux**: Linux es un sistema operativo de código abierto que cuenta con una amplia variedad de distribuciones diseñadas para uso en escritorio, como Ubuntu, Fedora y Linux Mint. Ofrece flexibilidad y opciones de personalización.

4. **Chrome OS**: Chrome OS es un sistema operativo basado en Linux desarrollado por Google. Está diseñado principalmente para dispositivos Chromebooks y se centra en la nube y la navegación web.

Comparativa entre Windows, Linux y Mac:

**Windows:**

Ventajas:
- Amplia compatibilidad de software y juegos.
- Interfaces familiares para la mayoría de los usuarios.
- Gran cantidad de soporte y recursos disponibles.
- Utilizado en la mayoría de las computadoras personales.

Desventajas:
- Vulnerable a virus y malware.
- Puede requerir software antivirus adicional.
- Actualizaciones de software a veces pueden ser intrusivas.
- Algunas versiones pueden ser costosas.

Seguridad:
- Tradicionalmente ha sido más vulnerable a ataques debido a su popularidad y arquitectura.
- Windows 10 ha mejorado la seguridad con características como Windows Defender y actualizaciones regulares de seguridad.

Uso:
- Ideal para usuarios que necesitan una amplia compatibilidad de software y juegos.
- Comúnmente utilizado en entornos empresariales y de consumo.
- Ampliamente adoptado en la industria.

**macOS:**

Ventajas:
- Diseño elegante y experiencia de usuario cohesiva.
- Buena seguridad y menos vulnerable al malware en comparación con Windows.
- Integración perfecta con otros productos de Apple.
- Actualizaciones regulares y gratuitas.

Desventajas:
- Costoso, ya que solo se encuentra en computadoras Mac.
- Menos compatibilidad con software de terceros en comparación con Windows.
- Menos opciones de hardware para elegir.

Seguridad:
- macOS generalmente se considera más seguro debido a su arquitectura Unix y su control de acceso.
- La Mac App Store controla la distribución de software, lo que puede mejorar la seguridad.

Uso:
- Atractivo para usuarios que valoran el diseño y la experiencia del usuario.
- Ideal para quienes ya utilizan otros productos de Apple.
- Utilizado en entornos creativos y de desarrollo.

**Linux:**

Ventajas:
- Gratuito y de código abierto.
- Variedad de distribuciones para diferentes necesidades.
- Gran flexibilidad y personalización.
- Generalmente menos vulnerable al malware.

Desventajas:
- Menos soporte de software comercial en comparación con Windows y macOS.
- Puede requerir conocimientos técnicos para la configuración y el uso avanzado.
- Menos juegos disponibles en comparación con Windows.

Seguridad:
- Linux es conocido por su seguridad y la capacidad de los usuarios para controlar las actualizaciones y configuraciones de seguridad.
- Menos propenso al malware debido a su arquitectura y menor popularidad en el escritorio.

Uso:
- Ideal para usuarios técnicos y desarrolladores.
- Utilizado en servidores y supercomputadoras.
- Algunas distribuciones, como Ubuntu, ofrecen experiencias de usuario más amigables para principiantes.

La elección entre Windows, macOS y Linux depende en gran medida de las preferencias personales, las necesidades específicas y el contexto de uso. Cada uno tiene sus ventajas y desventajas, y la decisión final dependerá de lo que sea más importante para el usuario.

## IMAGEN ISO

Una imagen ISO es un archivo que contiene una copia exacta de los datos y la estructura de un disco óptico, como un CD o un DVD. Se utiliza comúnmente para distribuir sistemas operativos, software y otros contenidos en formato digital. Puede ser montada como una unidad virtual o quemada en un disco para su uso en una computadora.

## CONCEPTOS INVOLUCRADOS

**Bootear Equipo:**

Booetear un equipo significa iniciar o cargar el sistema operativo y otros programas esenciales en la memoria RAM desde un dispositivo de almacenamiento, como un disco duro, una unidad USB o un DVD, durante el proceso de arranque o encendido del equipo. Esto permite que la computadora esté lista para su uso y ejecute aplicaciones una vez que el proceso de arranque haya finalizado.

**BIOS:**

El BIOS (Basic Input/Output System, por sus siglas en inglés) es un programa de firmware que reside en un chip de la placa base de una computadora. Su función principal es iniciar y configurar los componentes de hardware esenciales de la computadora durante el proceso de arranque, antes de cargar el sistema operativo. El BIOS también proporciona una interfaz básica para configurar opciones de hardware y realizar diagnósticos en la computadora.

**UEFI:**

UEFI (Unified Extensible Firmware Interface) es un estándar más moderno y versátil en comparación con el tradicional BIOS (Basic Input/Output System). UEFI reemplaza al BIOS en la mayoría de las computadoras modernas y sirve para realizar el proceso de arranque y configuración de hardware de la computadora. UEFI ofrece características avanzadas, como soporte para discos duros de gran capacidad, arranque seguro (Secure Boot), una interfaz gráfica de usuario y mayor flexibilidad en la configuración de hardware. Es una evolución del BIOS que mejora la funcionalidad y la compatibilidad de las computadoras.

**Partición Física y Lógica de Arranque:**

- Partición física de arranque: Es una partición en el disco duro de una computadora que contiene el cargador de arranque y otros archivos esenciales para iniciar el sistema operativo. Esta partición almacena el código necesario para cargar el sistema operativo y se utiliza para el arranque inicial del equipo. En sistemas Windows, se conoce como la partición "System Reserved". En sistemas Linux, esta partición puede ser la partición raíz (root) o una partición separada.

- Partición lógica de arranque: Es una partición en el disco duro que se utiliza para almacenar datos y programas, pero no contiene los archivos necesarios para el arranque del sistema. Se diferencia de la partición física de arranque en que no contiene el cargador de arranque ni los archivos de sistema críticos. Las particiones lógicas son utilizadas para organizar y administrar el espacio de almacenamiento en el disco duro, y no son directamente responsables del proceso de arranque del sistema operativo.

**GPT y MBR:**

GPT (GUID Partition Table) es una especificación de partición de disco que se utiliza para organizar y administrar particiones en discos duros o unidades de estado sólido (SSD) en sistemas informáticos. A diferencia del esquema de partición MBR (Master Boot Record), GPT proporciona ventajas como soporte para discos de mayor capacidad, mayor número de particiones, mayor resistencia a errores y una mayor compatibilidad con sistemas operativos modernos y sistemas con arquitectura UEFI (Unified Extensible Firmware Interface).

MBR (Master Boot Record) es un sector especial en el disco duro o unidad de almacenamiento que almacena información crítica para el proceso de arranque de una computadora. Contiene un cargador de arranque y una tabla de particiones que enumera las ubicaciones y tamaños de las particiones en el disco. MBR se utiliza en sistemas con BIOS tradicional y tiene limitaciones en términos de capacidad de disco y número de particiones en comparación con el esquema de partición GPT (GUID Partition Table).


> [Continuar](Tarea3-3.md)

> [Volver](Tarea3-1.md)
