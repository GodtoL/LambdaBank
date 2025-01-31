# LambdaBank - Calculadora de Cuotas de Préstamos

LambdaBank es una función AWS Lambda escrita en Java que calcula la cuota mensual de un préstamo basado en el monto del préstamo, la tasa de interés y el plazo del crédito. Además, ofrece un cálculo adicional con una tasa de interés reducida para clientes con cuenta bancaria.

## Requisitos Previos

- **AWS CLI**: Asegúrate de tener instalado y configurado AWS CLI.
- **Java Development Kit (JDK)**: JDK 8 o superior.
- **Maven**: Para la gestión de dependencias y la construcción del proyecto.
- **AWS SAM CLI** (opcional): Para facilitar la implementación y prueba local de la función Lambda.


## Clases Principales

- **LambdaBank.java**: Contiene la lógica principal de la función Lambda que calcula la cuota mensual del préstamo.
- **BankRequest.java**: Representa la solicitud de entrada que contiene el monto del préstamo, la tasa de interés y el plazo.
- **BankResponse.java**: Representa la respuesta que contiene la cuota mensual calculada, la tasa de interés y el plazo.

