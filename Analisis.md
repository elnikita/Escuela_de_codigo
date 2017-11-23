Asuntos generales sobre analisis y planeacion del proyecto "Escuela de Codigo"
-------------

Lo ideal seria implementar una arquitectura SOA usando microservicios. Hasta el momento la arquitectura parece ser un monolito. 

Este proyecto tiene muchos objetivos dentro del sector educativo pero sobre todo es una forma de aprender y practicar Ruby y Rails. 

**Caracteristica tecnica principal de CodeSchool:**

CodeSchool permite aprender programacion de forma practica o a como le llaman "Aprendiendo haciendo". Es decir, el **estudiante** tiene la oportunidad de sumergirse en el lenguaje en cuestion de segundos sin necesidad de instalar ningun componente extra. 

**Tecnologias a implementar:**

Front-end: No se tiene planeado hacer esta division o implenetar alguna tecnologia. Algo que me dice que aqui vendria React u otra tecnologia. 

Back-end: Ruby on Rails

Motor de bases de datos: PostgreSQL

**Pedagogia**

La pedogogia a utilizar sera la misma implementada por CodeSchool, pienso se puede llegar a iguales terminos si se examinan otros sitios como CodeAcademy y SoloLearn. La pedagogia utilizada por CodeSchool no es de otro mundo, o al menos en su version gratis. Me recuerda mucho a la de cursos introductorios a X lenguaje. [hablar mas sobre este syllabus que es muy comun en cursos, videos de youtube y codeschool]. Por el momento esta parte no es muy importante de desarollar ya que se tiene pensado literalmente hacer una copia exacta de los ejercicios de los lenguajes a ofrecer en la plataforma.  Es necesario una analisis escrito de particularidades de la pedagogia usada por CodeSchool. 

**Diagrama de Entidad-Relación**

Version 1:

Usuarios: Cambiar usuario a **estudiante**

Cursos:

Cursos_Niveles: Esta relacionado con la tabla [Cursos]. Un curso tiene de 1 a n niveles. "n_index" se refiere al index o posicion del nivel dentro del curso. Es decir, el nivel puede llamarse: "Nivel 1: Enteros y cadenas en el rio" pero lo que da el numero de nivel es el campo index que en este caso seria el 1. "n_idcurso" es el id del curso al que pertenece un nivel. 

Cursos_niveles_capitulos:





![Alt text](https://github.com/elnikita/Escuela_de_codigo/blob/master/diagrama.jpg?raw=true "Diagrama")


**Etapas de planeacion**

**Etapas de produccion**
