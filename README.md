# De la idea a la App

## ¿Por qué?

### Hardware

La humanidad gracias a sus herramientas y, en particular, al conocimiento (ciencias, ingenierías, etc.), ha construido grandes sistemas artificiales: acueductos, telares con tarjetas perforadas, red eléctrica, red telefónica, etc.​ para automatizar tareas, o sea, simplificar y reutilizar

- ***8000 aec.***, Los sumerios construyen telares para cubrirse
- ***1642 ec.***, Blaise Pascal construye la Pascalina, primera calculadora mecánica girando ruedas
- ***1801 ec.***, Jacquard construye el primer telar mecánico y automático con tarjetas perforadas para definir los dibujos
- ***1842 ec.***, Charles Babbage y Ada Lovalace trabajan sobre la Máquina Analítica, con las tarjetas perforadas de los telares …​ pero no llegó a funcionar aunque Ada ya escribió las primeras líneas de código de la historia.
- ***1884 ec.***, Hollerith desarrolló la Máquina Tabular de tarjetas perforadas para ordenar el registro de propiedad en la Conquista del Oeste
- ***1936 ec.***, Konrad Zuse, ingeniero alemán, diseñó y fabricó la Z1, la que para muchos es la primera computadora programable de la historia

### Software

<div align=center>


|**Es la información que suministra el desarrollador al ordenador<br><br>para que manipule -de forma automática-<br><br>la información que suministrará el usuario**<br><br><div align=right>*[Brad Cox](https://keepcoding.io/blog-frr/brad-cox-creador-de-objective-c-in-memoriam/), inventor del [Objetive-C](https://es.wikipedia.org/wiki/Objective-C)*</div>|![](https://raw.githubusercontent.com/mmasias/IdSw2/main/images/modelosUML/modelosUML/sistemaDeInformacion.svg)|
|:-:|-|

</div>

#### [Naturaleza](https://github.com/mmasias/IdSw2/blob/main/temario/00-introduccion/software.md#qu%C3%A9)

> [Características](https://github.com/mmasias/IdSw2/blob/main/temario/00-introduccion/proyectosSoftware.md#caracter%C3%ADsticas-del-software): *-bilities*, que se resumen en la mantenibilidad.

#### [Proyectos](https://github.com/mmasias/IdSw2/blob/main/temario/00-introduccion/proyectosSoftware.md)

<div align=center>

|![](https://raw.githubusercontent.com/mmasias/IdSw2/main/images/modelosUML/trianguloHierro.svg)||
|:-:|-|
La forma de hacer en este modelo del juego del desarrollo del software es que las fuerzas externas (clientes, directores de proyecto) eligen los valores de **tres variables** cualquiera. El equipo de desarrollo determina el valor resultante de la **cuarta variable**.|**Algunos directores de proyecto y clientes creen que pueden escoger el valor de las cuatro variables**. Cuando esto suceda, la calidad siempre desaparecerá, ya que nadie hace bien el trabajo cuando está sujeto a una fuerte presión. También, probablemente, el tiempo estará fuera de control

</div>

---

<div align=center>

|![](https://raw.githubusercontent.com/mmasias/IdSw2/main/images/modelosUML/variablesProyectoSoftware.svg)
|:-:
|**Variables de un proyecto de software**
|No hay una relación sencilla entre las cuatro variables
|Ej.: *no puedes reducir el tiempo a la mitad, gastando el doble*

</div>

#### [Crisis](https://github.com/mmasias/IdSw2/blob/main/temario/00-introduccion/crisisSoftware.md)

<div align=center>

|||
|-|-|
|La crisis del sotfware es la **incapacidad para dominar la complejidad de los proyectos de software**.|Período histórico que empezó a ser reconocido en la década de 1960 y que se extendió durante décadas posteriores.

---

|¿Qué?|¿Por qué?|
|-|-|
|Proyectos que excedían significativamente sus presupuestos.|Complejidad creciente del software.
|Entregas que superaban enormemente los plazos establecidos.|Dificultades en la gestión de proyectos de software.
|Software altamente ineficiente.|Expectativas poco realistas.
|Baja calidad del software producido.|Falta de metodologías establecidas.
|Requisitos que no se cumplían.|Ausencia de herramientas adecuadas.
|Proyectos inmanejables y difíciles de mantener.|Escasez de profesionales cualificados.
|Código difícil de mantener.|

---

|Categoría|Motivo|Incidencia|
|-|-|-|
| **Gestión** | **Total** | **31.0%** |
|| Falta de involucración del usuario | 12.8% |
|| Poco apoyo de las gerencias involucradas | 7.5% |
|| Falta de recursos | 6.4% |
|| Tiempos poco realistas | 4.3% |
|**Requisitos** | **Total** | **35.3%** |
|| Requerimientos y especificaciones poco claras | 12.3% |
|| Cambio de requerimientos y especificaciones | 11.8% |
|| Expectativas poco realistas | 5.9% |
|| Objetivos poco claros | 5.3% |
|**Tecnologías** | **Total** | **10.7%** |
|| Tecnología deficiente | 7.0% |
|| Nuevas tecnologías | 3.7% |
|**Otros** | **Total** | **23.0%** |

</div>

## ¿Qué (hacer)?

<div align=center>

|¿Qué hacer?|
|-|
|Adoptar ingeniería del software como disciplina formal.|
|Metodologías estructuradas de desarrollo.|
|Mejores prácticas de programación.|
|Nuevas herramientas y técnicas de desarrollo.|
|Patrones de diseño.|
|Métodos de gestión de proyectos específicos para software.|

</div>

## ¿Para qué?

Garantizar la mantenibilidad del software, que finalmente, es lo que garantiza la calidad.

<div align=center>

|Mantenible|No mantenible|
|:-:|:-:|
|**Fluido**<br>se puede entender con facilidad|**Viscoso**<br>no se puede entender con facilidad.|
|**Flexible**<br>se puede cambiar con facilidad|**Rígido**<br>no se puede cambiar con facilidad.|
|**Fuerte**<br>se puede probar con facilidad|**Frágil**<br>no se puede probar con facilidad|
|**Reusable**<br>se puede reutilizar con facilidad|**Inmóvil**<br>no se puede reutilizar con facilidad|

</div>

### Ejemplos de software mantenible

A primera vista, dime:

- ¿Qué hace [este programa](https://github.com/mmasias/TicTacToe/blob/d7e522ea57daac92075da432a9193d8220b9488f/src/masiasManuel/v002/TresEnRaya.java#L17)?
- ¿Y [este](https://github.com/mmasias/carreraCaballos/blob/254866f9227f3f219ee4301752d9480a23d6a251/Carrera.java#L15)?

## ¿Cómo?

<div align=center>

![](https://raw.githubusercontent.com/mmasias/IdSw2/main/images/modelosUML/modelosUML/software.svg))

</div>

- [Disciplinas](https://github.com/mmasias/PRG1/blob/main/temario/00001-disciplinasSw.md#c%C3%B3mo)
  - [Requisitos](https://github.com/mmasias/IdSw1/blob/main/temario/disciplinaDeRequisitos.md)
  - [Análisis & Diseño](https://github.com/mmasias/IdSw2/blob/main/temario/01-dise%C3%B1o/README.md#qu%C3%A9)
  - Desarrollo
  - Pruebas
  - Despliegue