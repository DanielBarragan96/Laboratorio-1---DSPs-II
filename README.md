# Laboratorio-1---DSPs-II
# Implementación de un calendarizador de tiempo real

Para esta actividad deberás clonar el proyecto que se encuentra en esta liga: https://github.com/raldanal/rtos. En ella encontrarás el código fuente para que
coloques en un proyecto nuevo de MCUXpresso para la tarjeta freedom board K64.

El archivo rtos_main.c contiene el punto de entrada del programa, en el cual se definen 3 tareas las cuales el objetivo es que terminen corriendo en paralelo
manteniendo su funcionalidad y contexto.

El módulo rtos coniene la API e implementación incompleta de un calendarizador por prioridades que deberás completar. Por lo pronto no hay nada implementado a excepción del SysTick timer configurado para generar una senal de "vida"que servirá para saber si el sistema operativo esta vivo.

Tu labor será terminar de implementar el resto del archivo rtos.c de manera que las tareas en el archivo main corran como se desea. A continuación se muestran pseudocódigos de lo que las funciones deberán realizar.
