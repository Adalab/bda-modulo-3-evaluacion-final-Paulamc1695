# Solución-Evaluación Módulo 3 del bootcamp Data Analytics

## Análisis de Datos

• **Análisis y transformación de datos.**
• **Métodos de Pandas y gestión de nulos.**
• **Limpieza. Uso de “apply” para transformar datos.**
• **Visualización, creación e interpretación de gráficas.**
• **Estadística y A/B testing.**

Describen el comportamiento de los clientes dentro de un programa de lealtad de una
aerolínea.

**Customer Flight Analysis.csv**
Este archivo conEene información sobre la acEvidad de vuelo de los clientes, incluyendo
el número de vuelos reservados, la distancia volada, puntos acumulados y redimidos, y
costos asociados a los puntos redimidos.

• Loyalty Number: Este atributo representa un idenEficador único para cada
cliente dentro del programa de lealtad de la aerolínea. Cada número de lealtad
corresponde a un cliente específico.
• Year: Indica el año en el cual se registraron las acEvidades de vuelo para el
cliente.
• Month: Representa el mes del año (de 1 a 12) en el cual ocurrieron las acEvidades
de vuelo.
• Flights Booked: Número total de vuelos reservados por el cliente en ese mes
específico.
• Flights with Companions: Número de vuelos reservados en los cuales el cliente
viajó con acompañantes.
• Total Flights: El número total de vuelos que el cliente ha realizado, que puede
incluir vuelos reservados en meses anteriores.
• Distance: La distancia total (presumiblemente en millas o kilómetros) que el
cliente ha volado durante el mes.
• Points Accumulated: Puntos acumulados por el cliente en el programa de lealtad
durante el mes, con base en la distancia volada u otros factores.
• Points Redeemed: Puntos que el cliente ha redimido en el mes, posiblemente
para obtener beneficios como vuelos graEs, mejoras, etc.
• Dollar Cost Points Redeemed: El valor en dólares de los puntos que el cliente ha
redimido durante el mes.

**Customer Loyalty History.csv**
Este archivo proporciona un perfil detallado de los clientes, incluyendo su ubicación,
nivel educaEvo, ingresos, estado civil, y detalles sobre su membresía en el programa de
lealtad (como el Epo de tarjeta, valor de vida del cliente, y fechas de inscripción y
cancelación)

• Loyalty Number: IdenEficador único del cliente dentro del programa de lealtad.
Este número permite correlacionar la información de este archivo con el archivo
de acEvidad de vuelos.
• Country: País de residencia del cliente.
• Province: Provincia o estado de residencia del cliente (aplicable a países con
divisiones provinciales estatales, como Canadá).
• City: Ciudad de residencia del cliente.
• Postal Code: Código postal del cliente.
• Gender: Género del cliente (ej. Male para masculino y Female para femenino).
• EducaFon: Nivel educaEvo alcanzado por el cliente (ej. Bachelor para
licenciatura, College para estudios universitarios o técnicos, etc.).
• Salary: Ingreso anual esEmado del cliente.
• Marital Status: Estado civil del cliente (ej. Single para soltero, Married para
casado, Divorced para divorciado, etc.).
• Loyalty Card: Tipo de tarjeta de lealtad que posee el cliente. Esto podría indicar
disEntos niveles o categorías dentro del programa de lealtad.
• CLV (Customer LifeFme Value): Valor total esEmado que el cliente aporta a la
empresa durante toda la relación que manEene con ella.
• Enrollment Type: Tipo de inscripción del cliente en el programa de lealtad (ej.
Standard).
• Enrollment Year: Año en que el cliente se inscribió en el programa de lealtad.
• Enrollment Month: Mes en que el cliente se inscribió en el programa de lealtad.
• CancellaFon Year: Año en que el cliente canceló su membresía en el programa
de lealtad, si aplica.
• CancellaFon Month: Mes en que el cliente canceló su membresía en el programa
de lealtad, si aplica.