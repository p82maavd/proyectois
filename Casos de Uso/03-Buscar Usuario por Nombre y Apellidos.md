**ID:** 03

**Descripción:** Se introduce el nombre y apellido del paciente que se busca y el sistema mostrará la ficha del mismo

**Actores Principales:** Administrador. 

**Actores Secundarios:** Paciente.

**Precondiciones:**
- Al menos un paciente en el registro.

**Flujo Principal:**
1. El Administrador desea consultar los datos de un paciente.
2. El Administrador selecciona la opción que le permitirá revisar la lista del menú.
3. El Administrador selecciona dentro de la lista seleccionará la opción que le permitirá buscarlos por nombre y apellido.
4. El Administrador introduce el nombre y apellido del paciente.
5. El sistema muestra la ficha del paciente.

**Postcondiciones:**
- Se muestran al Administrador las distintas operaciones relativas al paciente.

**Flujos alternativos:**
5.a. Si no existe el paciente, se muestra un mensaje de error y devuelve a la lista.
