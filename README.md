# M210526 - Herramienta de Limpieza de Datos

Aplicación web estática, rápida y segura diseñada para la limpieza, formateo y exportación de hojas de cálculo (.xlsx, .csv).

## Funciones Principales

- **Privacidad Total**: Todo el procesamiento se realiza localmente en tu navegador. Los datos nunca se envían a ningún servidor externo.
- **Limpieza Automática Inteligente**: Al cargar un archivo, la aplicación detecta y elimina automáticamente las filas "fantasma" vacías al final del documento y las columnas sin datos que suelen exportar algunos sistemas.
- **Gestión de Estructura**: Permite renombrar, ordenar (arrastrando) y seleccionar qué columnas deseas mantener en el archivo final.
- **Estilos Visuales**: Aplica alineación de texto (izquierda, centro, derecha), negritas, formatos numéricos (Moneda, Decimal, Entero) y permite elegir el color de la cabecera del Excel resultante.
- **Exportación Profesional**: Genera un archivo `.xlsx` limpio, acotado estrictamente a los datos útiles y con un formato "cebra" (filas con colores intercalados) para facilitar su lectura.

## Instalación y Uso

Dado que es una aplicación estática (HTML, CSS y JS puro), no requiere instalación de dependencias ni servidor. 

1. Abre el archivo `index.html` en cualquier navegador moderno.
2. Arrastra tu archivo Excel o CSV.
3. Configura tus columnas y exporta.

También está diseñado para ser alojado rápida y gratuitamente a través de **GitHub Pages**.

## Licencia

Desarrollado por **Antonio G.**

Este software fue creado específicamente para uso personal. Está estrictamente prohibida su venta o distribución comercial. Revisa el archivo `LICENSE` para más detalles.
