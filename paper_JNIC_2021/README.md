# HOUSE: Marco de trabajo modular de arquitectura escalable y desacoplada para el uso de técnicas de fuzzing en HPC
## [Descargar PDF](https://github.com/b0rh/Latex/blob/main/paper_JNIC_2021/HOUSE%20Marco%20de%20trabajo%20modular%20de%20arquitectura%20escalable%20y%20desacoplada%20para%20el%20uso%20de%20t%C3%A9cnicas%20de%20fuzzing%20en%20HPC.pdf)

Publicado en JNIC 2021, VI Jornadas Nacionales de Investigación en Ciberseguridad (9 al 10 de junio de 2021)

*DOI:* 10.18239/JORNADAS_2021.34.39 
*Corpus ID:* 236708872
*Authors:* Francisco Borja Garnelo Del Río, F. J. Rodríguez Lera, Gonzalo Esteban Costales, Camino Fernández Llamas, Vicente Matellán Olivera


*abstract:* El fuzzing es una técnica de prueba automatizada que hace uso de mutaciones de entradas para ejecutar el software utilizando estas a fin de observar los valores de retorno y el estado externo del sistema; todo ello para identificar comportamientos no esperados.
Por su simpleza y fácil automatización inicial, el fuzzing es una de las técnicas más populares para identificar vulnerabilidades en software en el mundo real. El uso de técnicas de fuzzing como parte del desarrollo de software en grandes compañías ha acelerado la evolución de las técnicas y mejorado las herramientas, como contrapartida muchos proyectos quedan huérfanos de sus desarrolladores originales, al ser captados por estas empresas y todas aquellas características con potencial uso comercial, son restringidas al ámbito privado o son dependientes de nubes propietarias. Esto supone una barrera inicial para nuevos desarrollos, una posible dependencia tecnológica de terceros y problemas de confidencialidad de los datos para adoptar modelos seguros de desarrollo o realizar investigaciones. Las investigaciones sobre fuzzing y las nuevas herramientas tienen en común partir desde cero o una base teórica y focalizarse en una característica o funcionalidad. 
Por todo lo anterior resulta valioso desarrollar un marco de trabajo común que de coherencia y continuidad de forma global abordando el fuzzing como un flujo con distintas fases, organizando todos los procesos implicados, incluyendo también aquellos con relación directa, de forma modular, abierta y agnóstica a las herramientas y técnicas.
Con ello se potencia la reutilización y se elimina la dependencia a herramientas o casos de uso, a la vez que permiten sinergias con otros enfoques de seguridad en el software. El uso de una arquitectura desacoplada y escalable permite la distribución y paralelización de trabajos. Esta arquitectura es ideal para entornos de computación de alto rendimiento en adelante HPC ( high-performance computing por su traducción al inglés) o basados en cargas de trabajo. El código fuente y la documentación empleada para la prueba de concepto se encuentra disponible públicamente en GitHub.


