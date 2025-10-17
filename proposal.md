# Propuesta TP DSW:Gestión del campamento mestizo.

## Grupo

### Integrantes

- 52604 Abbate,Thiago
- 48866 Montes, Alejandro
- 52957 Stella, Camila

### Repositorios

- [frontend app]:(http://github.com/mimistella/Campamento-FE)
- [backend app]: (http://github.com/ale-montes/Campamento-BE)

## Tema

### Descripción

Plataforma web que gestiona la experiencia de un campamento temático mitológico con diferentes roles: campistas, instructores y administradores.

### Modelo

DIAGRAMA ENTIDAD-RELACIÓN (DER)

![DER CAMPAMENTO MESTIZO](https://github.com/mimistella/dsw_tp_3k01_Abbate_Montes_Stella_2025/blob/main/assets/system_final_drawio.jpg?raw=true)

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Deidades <br>2.CRUD Misiones <br> 3. CRUD Periodo |
|CRUD dependiente|1. CRUD Cabaña, depende del CRUD Deidad<br>2. Crud Talleres depende del CRUD instructor y del CRUD periodo|
|Listado<br>+<br>detalle| 1.Listado de Cabañas con filtro de estado y detalles => con detalle de deidad y cantidad de campistas<br> 2. Listado de Usuarios con filtro por rol y con detalles segun la actividad/rol|
|CUU/Epic|1.Inscripción a talleres <br> 2.Solicitud a evento |

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Deidades <br> 2. CRUD Misiones <br> 3. CRUD Periodo <br> 4. CRUD Evento <br> 5. CRUD Intructor <br> 6. CRUD Admin <br> 7. CRUD Campista <br> 8. CRUD Cabaña <br> 9.CRUD Evento <br> 10. CRUD solicitudEvento <br> 11. CRUD inscripcionTaller <br> 12. CRUD Taller <br> 13. CRUD inscripcionPeriodo <br> 14. CRUD Hospedaje 15. CRUD asignaMision   |
|CUU/Epic|1. Asignacion de misiones a los campistas<br>2. Inscripción a talleres<br>3.Asignación de notas suministradas por los instructores a los campistas<br>4.Evaluación de Talleres por parte de Campistas|

### Alcance Adicional Voluntario
| Req      | Detalle                                                                                                |
| :------- | :----------------------------------------------------------------------------------------------------- |
| Listados | 1. E. Listado talleres filtrado por activos<br>2. Listado de Eventos |
| CUU/Epic | 1. Gestion de Misiones <br>2. Enviar solicitud al administrador                            |
| Otros    | 1. Notificaciones de acciones, suspensión o aceptación.<br>2.Manejo de errores        |
