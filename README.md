# Sistema de monitoreo de ruido en sala de cuidados intensivos neonatales

## Universidad Nacional de Córdoba

**Facultad de Ciencias Exactas, Físicas y Naturales**

**Facultad de Ciencias Médicas**

**Ingeniería Biomédica**

### Diseño y desarrollo de prototipo de equipo de control de niveles de ruido en sala de cuidados intensivos neonatales

**Alumnas:**

* Gonzalez Leahy, María Clara
* Nuñez, Anna

---

## Descripción

Este repositorio contiene los códigos desarrollados para el prototipo de monitoreo y alerta de niveles de ruido en una sala de cuidados intensivos neonatales.

El sistema está compuesto por tres nodos:

* **2 ESP32 Super Mini**, utilizados como clientes para la adquisición de las señales de los micrófonos.
* **1 ESP32-WROOM**, utilizado como servidor para la adquisición de la señal de uno de los micrófonos, la recepción de la información de los clientes y la gestión del sistema de alerta.

La adquisición del sonido se realiza mediante tres micrófonos MEMS INMP441 distribuidos en distintos sectores de la unidad.

## Estructura

El repositorio contiene los códigos correspondientes a los clientes y al servidor:

* `Cliente_1`: código del primer ESP32 Super Mini.
* `Cliente_2`: código del segundo ESP32 Super Mini.
* `Servidor`: código del ESP32-WROOM.
