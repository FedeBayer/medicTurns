# Medic Turns

![GitHub top language](https://img.shields.io/github/languages/top/FedeBayer/medicTurns?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/FedeBayer/medicTurns?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/FedeBayer/medicTurns?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/FedeBayer/medicTurns?style=for-the-badge)


### Description

Software que permita sacar turnos para médicos.

VUE, PHP, MVC, web services(API Rest), template engine(Smarty), ruteo, arquitectura web, persistencia(BBDD), CRUD(BBDD), SSR vs CSR.

<details close="true">
  <summary><b>:gear: &nbsp;Info</b></summary>
  
  Trabajo practico universitario: (para practicar metodologias agiles)
  
  La startup TurnoFacil nos ha contactado para desarrollar un software que permita sacar
turnos para médicos. En una reunión inicial que hemos tenido con TurnoFacil nos
comentan que sus intenciones son contar con una aplicación web que ejecute en una
cloud pública contratada por la empresa. Esta aplicación será comercializada por
TurnoFacil a distintas instituciones médicas como clínicas y consultorios por lo que la
misma deberá ser fácilmente instanciable para cada una de ellas.
  
Los dueños de TurnoFacil quieren que el sistema sea de fácil acceso a los pacientes por lo
que la pantalla inicial de la app solo debe solicitar número de DNI. En caso de que sea la
primera vez que el paciente ingresa a la app se le solicitará, antes de poder sacar un turno,
nombre, apellido, dirección, teléfono, email, obra social y número de afiliado.
Una vez que el paciente ingresa al sistema tendrá dos opciones: sacar un nuevo turno y
ver sus próximos turnos. Al sacar un nuevo turno el paciente deberá inicialmente
seleccionar un médico filtrando, si así lo desease, por especialidad, y obra social que
atiende. Una vez seleccionado un médico, el sistema deberá mostrar los días y horarios en
los que atiende el médico. Además, el sistema deberá solicitar un rango de fechas para
mostrar los turnos disponibles y, si así lo quisiese, el paciente podrá indicar si busca un
turno por la mañana o por la tarde. En caso de no existir turnos disponibles para el rango
de fechas ingresado, el sistema consultará al paciente si quiere ver los turnos para la
siguiente semana luego del rango de fechas ingresado. En caso de encontrar turnos
disponibles, el paciente podrá seleccionar uno. Al seleccionar un turno, se le solicitará al
paciente re-confirmar sus datos personales (nombre, apellido, dirección, teléfono, email,
obra social y número de afiliado). Una vez hecho esto, se registrará el turno brindando un
detalle del mismo (el mismo se enviará también por email) y se dará la opción de
imprimirlo. En caso de haber sacado un turno con un médico que no trabaja con la obra
social del paciente (o que cobra un diferencial para su obra social) deberá alertarse al
paciente de esta situación, pero permitirá sacar el turno de todas formas.

  Cuando el paciente quiere ver sus próximos turnos, el sistema deberá listarlos ordenados
cronológicamente indicando por cada uno médico, especialidad, día y horario.
Adicionalmente, se deberá dar la opción de cancelar un turno.
TurnoFacil también nos ha pedido que exista un portal dedicado para que secretarias y
médicos puedan acceder a la información de los turnos. Para ingresar a la misma cada uno
contará con un nombre de usuario y contraseña. En particular, por cada “instanciación” de
la aplicación, se designará un responsable de la institución médica contratante que podrá
crear usuarios para secretarias y médicos de esa institución. También será responsabilidad
de esa persona asignar a cada secretaria el grupo de médicos con los que trabaja.
Cada secretaria podrá cargar días y horarios de un médico con el que trabaje para que
sean informados a los pacientes al momento de buscar un turno. Además, tendrán la
responsabilidad de cargar turnos para cada médico con el que trabaje. Para agilizar la
carga de turnos, la secretaria podrá definir para una franja horaria de un día determinado
la duración de cada turno. Dado que en ocasiones los médicos son llamados por urgencias,
las secretarias deberán poder cancelar o reagendar turnos. Además, para una mejor
organización, la aplicación deberá proveer una forma de que una secretaria pueda listar
todos los turnos venideros de los médicos con los que trabaja. Esta funcionalidad deberá
permitir filtrar por médico, turno (mañana, tarde) y rango de días. Además, sería deseable
que una de estas configuraciones pueda ser guardada para que se genere de forma
periódica y se imprima automáticamente (por ejemplo, un listado de todos los turnos del
día para cada uno de los médicos con los que trabaja).

  Finalmente, cada médico deberá poder listar todos los turnos venideros que tiene. Esta
funcionalidad deberá permitir filtrar por turno (mañana, tarde) y rango de días.
</details>

### Goal

● se pueda aplicar de forma práctica conceptos de Scrum en el desarrollo del TP.

● utilice UML para el modelado de sistemas.

● pueda coordinar su trabajo en un equipo reducido.


[Link JIRA](https://tpemetodologia.atlassian.net/jira/software/projects/TM/boards/1)

![jira img](https://github.com/FedeBayer/medicTurns/assets/89879671/86cb8da9-c0fa-469b-b972-8478ed7437d3)

![user story mapping](https://github.com/FedeBayer/medicTurns/assets/89879671/5a4379ae-8be7-483a-9cef-01153a4924bb)

![UML](https://github.com/FedeBayer/medicTurns/assets/89879671/4d03af64-23b6-4afe-a96b-342bbe9c43ef)

