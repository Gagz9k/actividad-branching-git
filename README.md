# Actividad Branching Git

## Integrantes
- Natasha Cruz
- Felipe Segovia
- Sabrina Figueroa
- Cristian Díaz
- Camila Valdebenito
- Antonela Muñoz
- Sary Chara
- Alexander Hass

## Objetivo
Practicar branching, fork, pull request y merge.


## Alumno 1 (Natasha Cruz)

## Tema investigado  
Ramas (Branch) en Git  

## Definición  
Una rama en Git es una línea de desarrollo independiente que permite trabajar en cambios, nuevas funciones o correcciones sin afectar la versión principal del proyecto (main).

## Respuestas  
1. **¿Qué es una rama en Git?**  
Es una copia del proyecto donde se pueden hacer cambios de forma aislada sin modificar el código principal.

2. **¿Por qué las ramas ayudan a ordenar el trabajo?**  
Porque permiten separar tareas, trabajar en paralelo y organizar mejor el desarrollo sin mezclar cambios.

3. **¿Qué riesgo existe si todos trabajan en main?**  
Se pueden generar conflictos, errores en el sistema, pérdida de información y dificultad para identificar cambios.

## Ejemplo  
Un equipo está desarrollando una página web:  
- En la rama **main** está la versión estable  
- Una persona crea una rama llamada *login* para el sistema de inicio de sesión  
- Otra crea una rama *diseño* para cambiar la apariencia  

Cada uno trabaja sin afectar el proyecto principal y luego integran los cambios cuando están listos.

## Conclusión personal  
Las ramas en Git son fundamentales para trabajar de forma ordenada y segura, especialmente en equipo, ya que permiten evitar errores en la versión principal y facilitan la colaboración.

## Alumno 2 (Felipe Segovia)

### ¿Qué es una Branch (Rama)?
Es una **línea de desarrollo independiente** dentro de un mismo proyecto. 
Imagina que tu proyecto es el tronco de un árbol (la rama principal, usualmente llamada `main` o `master`). Cuando creas una *branch*, estás haciendo crecer una rama lateral. 
Te permite trabajar en nuevas funciones, corregir errores o experimentar con total seguridad, ya que nada de lo que hagas en esta rama alterará o romperá el código principal del tronco.

### ¿Qué es un Fork (Bifurcación)?
Es una **copia exacta, personal e independiente** de un proyecto *ajeno*. 
Al hacer un *fork*, agarras el repositorio de otra persona o equipo y te llevas un "clon" directamente a tu propia cuenta.  
Te permite experimentar y realizar cambios libremente en un código que no es tuyo, sin afectar el proyecto original y sin necesitar que sus creadores te den permisos de edición.

### ¿Cuál es la diferencia entre ambos?
La diferencia principal radica en el alcance del aislamiento y la propiedad del código: una branch es una división dentro del mismo proyecto, mientras que un fork es una copia completa e independiente del proyecto en tu propia cuenta.

## Alumno 3 (Sabrina Jeria)
## Qué representa la rama main
Es la rama principal del repositorio, en él está contenido la versión más completa y la más estable del proyecto. Es considerado un punto de referencia para las otras ramas y merge.
## Por qué suele ser la rama estable:
Se mantiene estable para que siempre exista una versión que sea funcional en el proyecto. Esto a su vez facilita que otros desarrolladores puedan basar su trabajo en ella sin tener el riesgo de cometer errores.
##  Qué significa proteger la rama principal
Significa el configurar reglas para que con ello no se puedan hacer cambios de forma directa sin una revisión previa. Esto nos asegura que solo los cambios que han sido revisados y aprobados se integren.

## Alumno 4 (Cristian Díaz)

## ¿Qué es un commit y por qué es importante?

**•	¿Qué es un commit?**
Un commit es como una “foto”, “instantanea” (snapshot) o punto de guardado que captura los cambios que se realizaron en un momento especifico dentro de un proyecto. Es importante porque funciona como un historial o punto de control, el cual sirve para revisar los cambios paso por paso o, en caso de algún error, volver a un estado anterior del código en que funcione correctamente.

**•	¿Por qué se hacen commits pequeños?**

Hacer commits pequeños es una buena práctica, y tiene varias ventajas como:
Mas claridad y orden: Cada commit representa un cambio específico.
Más fácil para encontrar errores: Si algo falla, puedes ver exactamente en qué cambio ocurrió.
Mejor control: Puedes volver atrás (rollback) sin perder todo el trabajo
Trabajo en equipo: Otros entienden fácilmente qué hiciste



**•	¿Cómo ayuda a seguir el historial del proyecto?**
Los commits crean una especie de línea de tiempo del proyecto. Gracias a eso se pueden ver qué cambios se hicieron, saber cuándo se hicieron, identificar quién los hizo y entender por qué se hicieron (gracias al mensaje) Podria decirse que es como un diario del proyecto.

**•	Ejemplos**

git commit -m "Inicio del proyecto"
git commit -m "Agrego título y párrafo"
git commit -m "Agrego estilos CSS"
git commit -m "Agrego imagen de demostración"
git commit -m "Corrijo errores"


**•	Conclusión**
Un commit es una “foto” de los cambios del proyecto.
Hacer commits pequeños nos otorga más orden, control y facilidad para detectar errores.
Los commits ayudan a contar la historia completa del desarrollo.

## Alumno 5 (Camila Valdebenito)
# Debe investigar

## ¿Qué significa trabajar local?
Significa que los desarrolladores realizan su trabajo en su propio equipo, en vez de depender de servidores externos.  
Con esto podemos trabajar en el código sin una conexión a internet y manipular realizando pruebas y cambios sin afectar a la aplicación en creación.

## ¿Qué significa remoto?
Es un repositorio alojado en un servidor externo.  
Estos actúan como enlace entre tu repositorio local y otros repositorios externos, facilitando la gestión de versiones, la colaboración y el intercambio de cambios entre desarrolladores.

## ¿Qué hace push?
**PUSH** se utiliza para subir los cambios realizados en un repositorio local a un repositorio remoto.  
Esto permite que otros colaboradores accedan a esos cambios.

---

## Alumno 6 (Antonela Muñoz)

## ¿Qué diferencia hay entre local y remoto?
Existen varias diferencias:

### DIFERENCIAS
- El repositorio local está en tu equipo, mientras que el remoto está en un servidor externo.
- El repositorio local permite trabajar sin conexión a internet.
- El repositorio remoto facilita la colaboración entre múltiples desarrolladores.
- El repositorio remoto actúa como respaldo del proyecto.

## ¿Qué hace git push?
Permite subir los commits desde tu rama (*branch*) local en tu repositorio Git local al repositorio remoto.

## ¿Por qué un commit local no siempre aparece aún en GitHub?
Existen varias razones:

- El repositorio local no está actualizado.
- La rama que contiene la confirmación haya sido eliminada.
- Hubo un empuje forzado sobre la confirmación.

Si el punto 2 o 3 sucede, significa que la confirmación puede quedar huérfana  
y no se capturará en el clon local.

# Ejemplo
Supongamos que estás trabajando en un proyecto en tu computadora:

Realizas cambios en un archivo.
Guardas los cambios con un commit:
          ```bash
          git commit -m   "Agrego nueva funcionalidad"
En este punto, el cambio **solo existe en tu repositorio local.**
Para enviarlo al repositorio remoto (por ejemplo, en GitHub), utilizas:
 git push origin main
Ahora otros desarrolladores pueden ver y descargar tus cambios.

## Conclusión Personal

Trabajar con repositorios locales y remotos es fundamental en el desarrollo moderno de software. 
El entorno local permite desarrollar y probar cambios de manera segura e independiente, mientras que el repositorio remoto facilita la colaboración y el respaldo del trabajo. 
El uso de comandos como `git push` permite sincronizar ambos entornos, asegurando que los cambios estén disponibles para todo el equipo y evitando la pérdida de información.



## Alumno 7 (Sary Chara)
## Tema investigado
Merge y conflictos en Git

## Definición
Un merge es la operación de unir dos ramas diferentes de código. Un conflicto ocurre cuando Git no puede decidir automáticamente qué cambios mantener porque dos personas modificaron las mismas líneas.

## Respuestas
**1. ¿Qué es un merge?**
Es el proceso de integrar cambios de una rama a otra. Git combina el historial de ambas ramas creando un nuevo commit que unifica el trabajo. Se usa cuando varios desarrolladores trabajan en paralelo y necesitan juntar sus avances.

**2. ¿Qué es un conflicto?**
Es una situación donde Git no puede resolver automáticamente las diferencias entre ramas. Ocurre cuando dos modificaciones afectan las mismas líneas de código de forma distinta, y Git necesita que un humano decida manualmente qué versión conservar.

**3. ¿Por qué ocurre cuando dos personas editan lo mismo?**
Porque Git compara tres versiones: tu rama, la otra rama y el punto donde ambas se separaron. Si las dos personas modificaron las mismas líneas de forma diferente, Git no tiene forma lógica de elegir cuál es la correcta y pide intervención humana.

## Ejemplo
**Situación:**
- Ana y Luis trabajan en el mismo archivo `config.js`
- Ana escribe: `color: "rojo"`
- Luis escribe: `color: "azul"`
- Ambos hacen commit y luego intentan mergear

**Resultado:**
Git muestra un conflicto:
```
color: "rojo"
=======
color: "azul"
```

**Solución:**
Alguien debe editar el archivo, decidir si queda rojo, azul o ambos, borrar los marcadores y hacer commit.

## Conclusión personal
Entendí que los conflictos no son errores ni algo malo, sino una protección de Git para que no se pierda trabajo. Lo importante es comunicarse con el equipo, hacer merges seguido (no esperar semanas) y aprender a resolver conflictos con calma. Al final, es parte normal del trabajo en equipo y mientras más práctica, más fácil se vuelve.

=======
___
