# Proyecto Spring Batch - Conversión de CSV
El objetivo de este proyecto es demostrar cómo utilizar Spring Batch para automatizar la transformación de datos. El proyecto lee un archivo CSV de entrada, procesa los datos para convertir el nombre a mayúsculas, y luego escribe el resultado en un nuevo archivo CSV de salida, mostrando un flujo completo de ETL (Extracción, Transformación y Carga) con Spring Batch.

## Requisitos previos
- **Java 21**: Asegúrate de tener instalado JDK 21.
- **Maven 3.x** o superior: Para compilar y ejecutar el proyecto.

## Tecnologías utilizadas
- **Java 21**
- **Spring Batch**
- **Spring Boot**
- **Maven**

## Estructura del proyecto
El proyecto incluye la configuración básica de Spring Batch para leer datos desde un archivo CSV (`data.csv`), procesarlos y escribirlos en otro archivo CSV (`output.csv`).

- **`Person`**: Clase que representa el modelo de datos con los atributos `id`, `name` y `age`.
- **`CsvBatchJobConfiguration`**: Clase de configuración principal que define el `Job`, el `Step`, el `ItemReader`, el `ItemProcessor` y el `ItemWriter`.


# Como utilizar
Para poder utilizar este repositorio, deberas abrir tu terminal (bash/PowerShell) e ir al directorio del proyecto.

1. Clonar el repositorio

```bash
git clone https://github.com/KariVillagran/batch_basic_csv_processor.git
cd batch_basic_csv_processor
```

2. Compila y ejecuta

```bash
mvn clean install
mvn spring-boot:run
```

Alternativamente, también puedes ejecutar el proyecto directamente usando el comando:

```bash
java -jar target/batch-basic-csv-processor-0.0.1-SNAPSHOT.jar
```