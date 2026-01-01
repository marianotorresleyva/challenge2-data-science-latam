# Telecom X - Análisis de Evasión de Clientes
El propósito de este analisis es reconocer las fallencias y oportunidades que le quedan a la empresa Telecom.

## Estructura del Proyecto 
Para este analisis trabajaremos con herramientas en la nube como Google colab, y el documento final es un reporte en pdf listo para descargar.

En el siguiente ejercicio trabajaremos la parte de extracción, transformación y carga

Los ejemplos y graficos obtenidos lo obtendrán en la carpeta de assets.

Para obtener el Proyecto en cuestion solo deben descargar y ejecutarlo.

#### Diccionario de datos

- `customerID`: número de identificación único de cada cliente
- `Churn`: si el cliente dejó o no la empresa
- `gender`: género (masculino y femenino)
- `SeniorCitizen`: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- `Partner`: si el cliente tiene o no una pareja
- `Dependents`: si el cliente tiene o no dependientes
- `tenure`: meses de contrato del cliente
- `PhoneService`: suscripción al servicio telefónico
- `MultipleLines`: suscripción a más de una línea telefónica
- `InternetService`: suscripción a un proveedor de internet
- `OnlineSecurity`: suscripción adicional de seguridad en línea
- `OnlineBackup`: suscripción adicional de respaldo en línea
- `DeviceProtection`: suscripción adicional de protección del dispositivo
- `TechSupport`: suscripción adicional de soporte técnico, menor tiempo de espera
- `StreamingTV`: suscripción de televisión por cable
- `StreamingMovies`: suscripción de streaming de películas
- `Contract`: tipo de contrato
- `PaperlessBilling`: si el cliente prefiere recibir la factura en línea
- `PaymentMethod`: forma de pago
- `Charges.Monthly`: total de todos los servicios del cliente por mes
- `Charges.Total`: total gastado por el cliente
## Analisis Principal
**Objetivo**: Saber por qué los clientes están cancelando su suscripción.

### Hipotesis
Las siguientes hipotesis nos ayudarán a guiarnos con respecto al analisis Principales
- Clientes Senior no necesitan más los servicios.
- Clientes tuvieron una mala experiencia con algun servio o atención.
- Deudas y/o cuotas atrasadas.
- Acumulacion de facturas no vistas. PaperlessBiling

### Gráficos utilizados
Para la visualización de datos, se ha seleccionado un conjunto de graficas selectas.
1. Gráfico Circular
2. Gráfico

## Tecnologías Utilizadas 
Bibliotecas de python
- Pandas
- Seaborn
- Matplotlib

# Conclusión
