# Preguntas: Elementos, características, funciones y arquitectura de un SO

![a](Varios/banner.jpg)


1. **Diferencia entre interrupción y excepción** 🚨⚠️:

2. **Diferencia entre software propietario y software comercial** 💻💸:
   - **Software propietario**: Es el software que tiene restricciones en su uso, modificación y distribución. Generalmente, el dueño del software establece estas reglas a través de licencias, y el código fuente no suele estar disponible para el público 👀🚫.
   - **Software comercial**: Es el software creado con la intención de venderse o generar ganancias, pero no necesariamente es propietario. Puede ser propietario o de código abierto (como el software open-source que se comercializa) 💵🌐.

3. **Multiprogramación en los sistemas operativos de los años 60** 🕰️💽:
   - La multiprogramación permite cargar varios programas en la memoria principal y cambiar entre ellos, aprovechando los tiempos de espera (como los de entrada/salida) para que otro programa continúe su ejecución. Así, se aprovechan mejor los recursos del sistema ⚙️💡.

4. **Diferencia entre multiprogramación y multiprocesamiento** 🤔🔄:
   - **Multiprogramación**: Permite que varios programas se ejecuten de forma concurrente en un solo procesador, alternando su ejecución 🔄💻.
   - **Multiprocesamiento**: Usa varios procesadores que trabajan al mismo tiempo para ejecutar múltiples programas o procesos a la vez, permitiendo un paralelismo real 💥⚡.

5. **Concepto de tiempo compartido** 🕒👥:
   - El tiempo compartido permite que múltiples usuarios usen el sistema como si estuvieran trabajando simultáneamente. El sistema operativo asigna tiempo de CPU a cada usuario o proceso en intervalos cortos ⏱️. Los sistemas de tiempo compartido deben ser **multitarea** y permitir **interactividad** rápida para cada usuario 🙋‍♂️🙋‍♀️.

6. **Diferencia entre un sistema operativo en red y uno distribuido** 🌐🖥️:
   - **Sistema operativo en red**: Permite la comunicación y el intercambio de recursos entre varios sistemas conectados, pero cada equipo mantiene su propio sistema operativo 🤝.
   - **Sistema operativo distribuido**: Coordina varios sistemas para que funcionen como un solo sistema lógico. Aquí, los recursos se gestionan y distribuyen de forma integrada y transparente para el usuario 🔗✨.

7. **¿Un sistema operativo monousuario puede ser multitarea y multiproceso?** 🧑‍💻🔄:
   - **Monousuario y multitarea**: Sí, un sistema monousuario puede ser multitarea (como Windows XP o macOS), permitiendo que una sola persona ejecute varias aplicaciones al mismo tiempo 📂🖥️.
   - **Monousuario y multiproceso**: También, un sistema monousuario puede manejar varios procesos a la vez, siempre y cuando el hardware lo permita 💪💻.

8. **Núcleo de un sistema operativo** 🧠:
   - El núcleo (o kernel) es la parte central del sistema operativo que controla las operaciones básicas y esenciales, como la administración de memoria, la gestión de procesos y el control del hardware 🔧.

9. **Diferencia entre interrupción y excepción** 🚨⚠️:
   - **Interrupción**: Es una señal que indica al procesador que debe pausar su tarea actual para atender una operación externa (como una solicitud de un periférico) ⏸️🔌.
   - **Excepción**: Es una interrupción generada por el procesador en respuesta a un error o evento inesperado dentro de un programa (como una división por cero o una falla de segmentación) 💥🚫.

10. **Diferencia entre interrupción y excepción** 🚨⚠️:

---
```
**Licencias de Software**

1. Software Libre
   - Licencia GPL (General Public License): Permite usar, modificar y distribuir el software, siempre que se mantenga la misma licencia en las versiones derivadas.
   - Licencia LGPL (Lesser General Public License): Similar a la GPL, pero permite el enlace con bibliotecas de software propietario.
   - Licencia Apache: Permite el uso, modificación y distribución del software, incluso para fines comerciales, siempre que se incluya una copia de la licencia original y el aviso de derechos de autor.
   - Licencia MIT: Muy permisiva, permite casi cualquier uso, incluido el uso comercial y la modificación sin necesidad de mantener la misma licencia.
   - Licencia BSD: Similar a la MIT, permite la modificación y redistribución, incluso para fines comerciales, pero exige reconocimiento al autor original.

2. Software de Código Abierto
   - Licencia MPL (Mozilla Public License): Permite el uso, modificación y distribución, pero obliga a compartir cambios bajo la misma licencia si se modifica y distribuye el código fuente.
   - Licencia EPL (Eclipse Public License): Similar a la MPL, permite la modificación y redistribución, pero requiere que las modificaciones se liberen bajo la misma licencia si se distribuyen.

3. Software Propietario
   - Licencia de Usuario Final (EULA Licencia que otorga el derecho de uso del software sin acceso al código fuente y restringe la modificación y redistribución.
   - Licencia Shareware Permite probar el software por un tiempo o con funcionalidad limitada, luego se requiere un pago para obtener la versión completa.
   - Licencia Freeware Software gratuito para uso, pero sin acceso al código fuente ni derecho a modificarlo o distribuirlo.
   - Licencia OEM (Original Equipment Manufacturer): Licencia que permite la instalación del software solo en el hardware con el que se vende, como los sistemas operativos preinstalados en equipos.

4. Software de Dominio Público
   - Licencia CC0 (Creative Commons Zero): Libera el software en el dominio público, permitiendo cualquier uso, modificación y redistribución sin restricciones.
   - Dominio Público: Software sin ninguna restricción de derechos de autor, de uso libre para cualquier propósito sin condiciones. 
```
--- 


## **Licencia Creative Commons** CC:
   - he escogido esta licencia ya que es la mas restrictiva, y menos huecos deja a nadie para que pueda robar mi trabajo.
