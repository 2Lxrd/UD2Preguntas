# Preguntas: Elementos, características, funciones y arquitectura de un SO

![a](./Varios/banner.png)


1. **Diferencia entre software propietario y software comercial** 💻💸:
   - **Software propietario**: Es el software que tiene restricciones en su uso, modificación y distribución. Generalmente, el dueño del software establece estas reglas a través de licencias, y el código fuente no suele estar disponible para el público 👀🚫.
   - **Software comercial**: Es el software creado con la intención de venderse o generar ganancias, pero no necesariamente es propietario. Puede ser propietario o de código abierto (como el software open-source que se comercializa) 💵🌐.

2. **Multiprogramación en los sistemas operativos de los años 60** 🕰️💽:
   - La multiprogramación permite cargar varios programas en la memoria principal y cambiar entre ellos, aprovechando los tiempos de espera (como los de entrada/salida) para que otro programa continúe su ejecución. Así, se aprovechan mejor los recursos del sistema ⚙️💡.

3. **Diferencia entre multiprogramación y multiprocesamiento** 🤔🔄:
   - **Multiprogramación**: Permite que varios programas se ejecuten de forma concurrente en un solo procesador, alternando su ejecución 🔄💻.
   - **Multiprocesamiento**: Usa varios procesadores que trabajan al mismo tiempo para ejecutar múltiples programas o procesos a la vez, permitiendo un paralelismo real 💥⚡.

4. **Concepto de tiempo compartido** 🕒👥:
   - El tiempo compartido permite que múltiples usuarios usen el sistema como si estuvieran trabajando simultáneamente. El sistema operativo asigna tiempo de CPU a cada usuario o proceso en intervalos cortos ⏱️. Los sistemas de tiempo compartido deben ser **multitarea** y permitir **interactividad** rápida para cada usuario 🙋‍♂️🙋‍♀️.

5. **Diferencia entre un sistema operativo en red y uno distribuido** 🌐🖥️:
   - **Sistema operativo en red**: Permite la comunicación y el intercambio de recursos entre varios sistemas conectados, pero cada equipo mantiene su propio sistema operativo 🤝.
   - **Sistema operativo distribuido**: Coordina varios sistemas para que funcionen como un solo sistema lógico. Aquí, los recursos se gestionan y distribuyen de forma integrada y transparente para el usuario 🔗✨.

6. **¿Un sistema operativo monousuario puede ser multitarea y multiproceso?** 🧑‍💻🔄:
   - **Monousuario y multitarea**: Sí, un sistema monousuario puede ser multitarea (como Windows XP o macOS), permitiendo que una sola persona ejecute varias aplicaciones al mismo tiempo 📂🖥️.
   - **Monousuario y multiproceso**: También, un sistema monousuario puede manejar varios procesos a la vez, siempre y cuando el hardware lo permita 💪💻.

7. **Núcleo de un sistema operativo** 🧠:
   - El núcleo (o kernel) es la parte central del sistema operativo que controla las operaciones básicas y esenciales, como la administración de memoria, la gestión de procesos y el control del hardware 🔧.

8. **Diferencia entre interrupción y excepción** 🚨⚠️:
   - **Interrupción**: Es una señal que indica al procesador que debe pausar su tarea actual para atender una operación externa (como una solicitud de un periférico) ⏸️🔌.
   - **Excepción**: Es una interrupción generada por el procesador en respuesta a un error o evento inesperado dentro de un programa (como una división por cero o una falla de segmentación) 💥🚫.
