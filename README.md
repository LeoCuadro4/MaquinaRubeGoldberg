# Máquina de Rube Goldberg — Unity

## Descripción del proyecto

Proyecto desarrollado en **Unity versión 6000.6.3f1** para la asignatura de Desarrollo de Videojuegos. Consiste en una máquina de Rube Goldberg en un entorno 3D, en la que una acción inicial desencadena una secuencia de eventos mediante rampas, dominós, cubos, plataformas y otros elementos interactivos.

El proyecto utiliza el sistema de físicas de Unity para representar las interacciones entre objetos, las colisiones y la gravedad, complementado con materiales y texturas.

## Características principales

- **Simulación de físicas:** uso de gravedad, colisionadores y componentes `Rigidbody` para controlar el movimiento y las interacciones entre objetos.
- **Reacción en cadena:** mecanismos conectados que permiten desencadenar una serie de eventos a partir de una acción inicial.
- **Entorno 3D:** escenario compuesto por rampas , plataformas y elementos estructurales.
- **Materiales y texturas:** aplicación de recursos visuales personalizados para mejorar la apariencia de los objetos.

## Requisitos

- Unity Hub.
- Unity 6, preferiblemente la misma versión utilizada para desarrollar el proyecto.
- Un equipo compatible con los requisitos de Unity.

## Cómo descargar el proyecto

1. Acceder al repositorio de GitHub: [Máquina de Rube Goldberg](https://github.com/LeoCuadro4/MaquinaRubeGoldberg).
2. Pulsar el botón **Code**.
3. Seleccionar **Download ZIP**.
4. Descomprimir el archivo descargado en una ubicación local.

También es posible clonar el repositorio mediante Git o GitHub Desktop.

## Cómo abrir el proyecto

1. Abrir Unity Hub.
2. Seleccionar la opción **Add project from disk** (Añadir proyecto desde el disco).
3. Elegir la carpeta raíz del proyecto, donde se encuentran las carpetas `Assets`, `Packages` y `ProjectSettings`.
4. Abrir el proyecto con la versión correspondiente de Unity.
5. Esperar a que Unity importe los recursos y complete la preparación del proyecto.

## Cómo ejecutar la máquina

1. Abrir el proyecto en Unity.
2. En el panel **Project**, navegar hasta la carpeta `Assets/Scenes/`, si está disponible.
3. Abrir la escena principal del proyecto (MaquinaGoldberg).
4. Verificar que los objetos y mecanismos estén presentes en la jerarquía.
5. Pulsar **Play** para iniciar la simulación.

**Nota:** si la escena principal no se abre automáticamente, debe seleccionarse manualmente desde el panel Project.
## Estructura del proyecto

- `Assets/`: contiene las escenas, modelos 3D, materiales, texturas, animaciones y demás recursos del juego.
- `Packages/`: contiene la configuración de los paquetes y las dependencias de Unity.
- `ProjectSettings/`: almacena la configuración del proyecto.
- `.gitignore`: define los archivos y directorios excluidos del control de versiones.
- `Library/`: carpeta generada automáticamente por Unity durante la importación de recursos. No se incluye en el repositorio.
