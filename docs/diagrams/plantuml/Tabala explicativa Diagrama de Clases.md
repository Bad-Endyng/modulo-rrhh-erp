    Tabla Explicativa:

Clase 	Descripción
Employee 	Representa la entidad principal del dominio, con sus atributos y métodos.
Department 	Representa el departamento al que pertenece un empleado.
EmployeeController 	Recibe las peticiones HTTP (ej. desde la SPA) y delega la lógica al servicio. Sigue el patrón MVC/Controller.
EmployeeService 	Contiene la lógica de negocio principal para la gestión de empleados.
EmployeeRepository 	Se encarga de la comunicación con la base de datos (abstracción de la persistencia). Sigue el patrón Repository.
