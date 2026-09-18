# Portafolio

## Sistema Espacial

Aplicación de escritorio desarrollada en **Java** para la gestión y planificación de misiones espaciales. El proyecto utiliza **Maven** para su configuración y ejecución, y cuenta con una interfaz gráfica de usuario para interactuar con el sistema.

### Características principales

- Gestión de misiones espaciales planificadas.
- Registro de información asociada a cada misión, incluyendo:
  - Código de misión.
  - Nombre o destino.
  - Estado de planificación.
  - Presupuesto o valor asignado.
  - Tipo de operación.
  - Parámetros numéricos de la misión.
  - Indicadores booleanos de configuración.
- Ejemplos de datos relacionados con misiones de **biología humana** y **microgravedad**.
- Ejecución mediante Maven.
- Interfaz principal implementada en la clase `com.uned.sistemaespacial.FrmPrincipal`.

### Tecnologías utilizadas

- Java 23
- Maven
- XML para la configuración del proyecto
- Programación orientada a objetos
- Interfaz gráfica de escritorio

### Estructura destacada

- `pom.xml`: configuración del proyecto Maven y versión de Java.
- `nbactions.xml`: configuraciones para ejecutar, depurar y perfilar la aplicación desde NetBeans.
- `BiologiaHumana.txt`: datos de ejemplo relacionados con una misión de biología humana.
- `Microgravedad.txt`: datos de ejemplo relacionados con una misión de microgravedad.

### Ejecución

Para ejecutar el proyecto se requiere tener instalado **Java 23** y **Maven**. Desde la carpeta raíz del proyecto, se puede utilizar:

```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.uned.sistemaespacial.FrmPrincipal"
```

> Este proyecto forma parte de mi portafolio académico y demuestra conocimientos en Java, Maven, manejo de datos y desarrollo de aplicaciones de escritorio.
