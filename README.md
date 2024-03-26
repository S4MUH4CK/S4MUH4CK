CREATE TABLE Estudiantes (
    Id INT PRIMARY KEY,
    Apellido VARCHAR(50),
    Nombre VARCHAR(50),
    Genero VARCHAR(10),
    Fecha_Nacimiento DATE,
    Edad INT,
    Lugar_Nacimiento VARCHAR(100),
    Nombre_Padre VARCHAR(50),
    Nombre_Madre VARCHAR(50),
    Telefono VARCHAR(15),
    Correo VARCHAR(100),
    Direccion VARCHAR(255),
    Codigo VARCHAR(20)
);

-- Insertar datos de ejemplo
INSERT INTO Estudiantes (Id, Apellido, Nombre, Genero, Fecha_Nacimiento, Edad, Lugar_Nacimiento, Nombre_Padre, Nombre_Madre, Telefono, Correo, Direccion, Codigo) VALUES
(1, 'Pérez', 'Juan', 'Masculino', '2000-05-15', 24, 'Ciudad de México', 'Carlos Pérez', 'María González', '555-1234', 'juanperez@example.com', 'Calle 123, Colonia Centro', 'E001'),
(2, 'García', 'María', 'Femenino', '2001-08-20', 23, 'Guadalajara', 'Luis García', 'Ana Martínez', '555-5678', 'mariagarcia@example.com', 'Avenida 456, Colonia Norte', 'E002'),
(3, 'López', 'Pedro', 'Masculino', '2000-02-10', 25, 'Monterrey', 'Jorge López', 'Laura Ramírez', '555-9012', 'pedrolopez@example.com', 'Calle 789, Colonia Sur', 'E003'),
-- Agregar los demás estudiantes aquí
(32, 'Sánchez', 'Ana', 'Femenino', '2002-11-30', 21, 'Tijuana', 'Manuel Sánchez', 'Sofía Ruiz', '555-6789', 'anasanchez@example.com', 'Boulevard 321, Colonia Oeste', 'E032');
