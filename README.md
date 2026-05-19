# Taller-3.1

📦 Taller 3.1 — Operaciones Unarias del Álgebra Relacional

Asignatura: Modelado de Bases de Datos
Escuela: Ingeniería de Sistemas — Universidad Andina del Cusco
Docente: Espetia Huamanga Hugo


📋 Descripción
Este repositorio contiene el desarrollo del Taller 3.1, cuyo objetivo es comprender y aplicar las operaciones unarias del álgebra relacional mediante el uso de ADO.NET Entity Framework, LINQ y la base de datos Northwind.
La base de datos Northwind simula el funcionamiento de una empresa comercial distribuidora de productos, permitiendo trabajar con entidades como clientes, productos, categorías, pedidos y empleados.

🎯 Objetivos

Implementar consultas de selección (σ) utilizando distintos tipos de condiciones y predicados.
Desarrollar consultas de proyección (π) para obtener subconjuntos específicos de atributos.
Aplicar el operador de renombramiento (ρ) para asignar alias a relaciones y atributos.
Comprender el funcionamiento de las operaciones unarias dentro del modelo relacional.
Utilizar LINQ y Entity Framework para acceder y manipular datos de forma eficiente.
Fortalecer habilidades relacionadas con la programación orientada a datos y consultas declarativas.


🧮 Operaciones Implementadas
σ — Selección
Filtra las filas de una tabla según una condición lógica.
σ condición (Relación)
Tipos de predicados utilizados:

Predicado de comparación
Predicado de rango
Predicado de pertenencia

π — Proyección
Selecciona únicamente ciertas columnas de una tabla.
π atributos (Relación)
Variantes implementadas:

Columnas específicas
Eliminación de duplicados
Subconjunto relevante

ρ — Renombramiento
Asigna un alias a una relación o a sus atributos.
ρ nuevo_nombre (Relación)
Alias utilizados: Apellido, Obra, Editorial, Empleado, Local

🗄️ Base de Datos
Northwind — base de datos de ejemplo de Microsoft que representa una empresa distribuidora de productos alimenticios.
EntidadDescripciónProductsProductos disponibles para distribuciónCustomersClientes registrados en el sistemaCategoriesCategorías de productosEmployeesEmpleados de la empresaOrdersPedidos realizados por los clientesSuppliersProveedores de los productos

🛠️ Tecnologías
TecnologíaUsoC#Lenguaje de programación principalADO.NETAcceso a datos de bajo nivelEntity FrameworkORM para mapear tablas a clases C#LINQConsultas declarativas integradas en C#Northwind DBBase de datos de ejemploWindows FormsInterfaz de usuario de escritorio

📁 Estructura del Proyecto
taller-3.1/
├── NorthwindContext.cs         # Contexto de Entity Framework
├── Models/                     # Entidades mapeadas
│   ├── Product.cs
│   ├── Customer.cs
│   ├── Category.cs
│   ├── Employee.cs
│   ├── Order.cs
│   └── Supplier.cs
├── Forms/
│   └── Form1.cs                # Formulario principal con las consultas
├── Queries/
│   ├── Seleccion.cs            # Operaciones σ (selección)
│   ├── Proyeccion.cs           # Operaciones π (proyección)
│   └── Renombramiento.cs       # Operaciones ρ (renombramiento)
└── README.md

⚠️ La estructura puede variar según la organización interna del proyecto.






👥 Integrantes
EstudianteCódigoParticipaciónCarpio Delgado, Alejandro Eduardo024100051j100%Haro Rosales, Joaquín024100970e100%Molero Zegarra, Thiago Valentino024100247a100%Olivera Ochoa, Paúl Claus024100569i100%

