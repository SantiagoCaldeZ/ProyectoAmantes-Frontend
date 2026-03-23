# ProyectoAmantes
Ejercicio #3
Santiago Calderón y Fabricio Monge

Ejercicio: API tradicional para encontrar mi amante ideal. Construyan una aplicación simple donde los usuarios puedan registrar perfiles de posibles amantes y luego consultar candidatos según un interés específico, con un backend desacoplado del frontend y siguiendo una arquitectura en capas clara. Ejercicio en parejas.


Arquitectura: NodeJS + Express + REST
Base de datos: MongoDB local con pocos registros
Capas obligatorias: controllers, services, repositories, model, dto
Repositorios separados: uno para backend y otro para frontend
Frontend: React con client side rendering
Operación de escritura: POST /amantes para crear un perfil con nombre, edad e intereses
Operación de lectura: GET /amantes?interes=x para listar coincidencias por interés
Validaciones básicas en DTOs
Scripts: npm run dev y npm run start para backend y frontend
Seed data mínima cargada automáticamente
Todo debe correr localmente sin dependencias externas
Entregables:
repositorio en github para revisión, se revisarán commits de los integrantes
todo el código debe ser generado por una AI especializada en coding, por ende se revisarán los markdown files y los agentes que se hayan definido para la creación del ejemplo de implementación
se harán preguntas sobre la implementación de la tecnología, paradigma y topología
la revisión será con cita por videollamada
