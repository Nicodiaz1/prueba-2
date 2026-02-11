README - Script-8.sql

Descripcion
Este repositorio contiene un script SQL para crear y poblar una base de datos de ejemplo llamada HealthTrackDB. El script define tablas de pacientes, doctores y citas, inserta datos ficticios y ejecuta consultas basicas. sisisisi

Archivo principal
- [Script-8.sql](Script-8.sql)

Base de datos objetivo
El script esta escrito para PostgreSQL (usa SERIAL y EXTRACT).

Esquema
- patients: datos basicos del paciente.
- doctors: datos del doctor y si esta activo.
- appointments: citas que relacionan pacientes y doctores.

Datos de ejemplo
Se insertan 3 pacientes, 3 doctores y 3 citas.

Consultas incluidas
- Citas del doctor con id 1 (sin duplicados).
- Pacientes nacidos desde 1980 con telefono no nulo.
- Citas sin notas.

Uso rapido (psql)
1) Crear la base de datos y cargar el script.
	psql -f Script-8.sql

Notas
- El script elimina las tablas si existen.
- La base de datos se crea al inicio con CREATE DATABASE.
