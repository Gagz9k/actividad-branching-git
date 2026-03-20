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


## Alumno 7 (SARY CHARA)
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
<<<<<<< HEAD
color: "rojo"
=======
color: "azul"
>>>>>>> rama-de-luis

**Solución:**
Alguien debe editar el archivo, decidir si queda rojo, azul o ambos, borrar los marcadores y hacer commit.

## Conclusión personal
Entendí que los conflictos no son errores ni algo malo, sino una protección de Git para que no se pierda trabajo. Lo importante es comunicarse con el equipo, hacer merges seguido (no esperar semanas) y aprender a resolver conflictos con calma. Al final, es parte normal del trabajo en equipo y mientras más práctica, más fácil se vuelve.

