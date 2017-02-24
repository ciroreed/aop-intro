TIPS

Cross-cutting concerns are often about

-- no significa que todos los ccc relacionados con la validación se resuelvan en el mismo sitio...

CALM DOWN

-- cambia la forma de codificar...

Technical definition

-- los aspectos describen un patrón repetitivo en nuestro código,
-- aspects must be so well defined that you may able to drop from proyect to proyect
-- los aspectos son piezas que podemos ensamblar en una clase (stack)
-- los aspectos reciben toda la información contextual a la que tiene acceso ese método, además de servicios
-- un aspecto debe ser responsable de hacer o resolver un único problema
-- joinpoint básicamente indica en que momento de la ejecución se va a ejecutar nuestro aspecto

sobre kaop respecto a aspect.js

-- en lugar de definir aspectos "oficiales" estamos construyendo advices
-- los advices no pueden iniciar código asíncrono,
-- un único aspecto por clase,
-- que podemos unir a nuestras clases de forma independiente, y podemos conocer el orden de ejecución,
-- probablemente tengamos uno o mas problemas que queramos resolver mediante AOP.
-- los callbacks son mas faciles de integrar con librerías de terceros
-- dificil interpretación
-- no existe joinpoint para instancias
