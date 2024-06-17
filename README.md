# AuditSimulation

Vamos a realizar una auditoria.

Se nos darán una serie de [datos](https://github.com/Ramonperu/AuditSimulation/blob/main/Botium-Toys-Scope-goals-and-risk-assessment-report.docx) para comprobar la seguridad de los controles realizados y cumplimiento de leyes de una empresa(Si necesitamos recordar los controles y sus tipos podemos acceder [aqui](https://github.com/Ramonperu/AuditSimulation/blob/main/Control-categories.docx))

Vamos a realizar una tabla para marcar el resultado de los controles y el cumplimiento de leyes y políticas

| Sí   | No   | Control                                                      |
| ---- | ---- | ------------------------------------------------------------ |
|      | X    | Principio de mínimo privilegio                               |
|      | X    | Planes de recuperación ante desastres                        |
|      | X    | Políticas de contraseñas                                     |
|      | X    | Separación de funciones                                      |
| X    |      | Cortafuegos (Firewall)                                       |
|      | X    | Sistema de detección de intrusos (IDS)                       |
|      | X    | Copias de seguridad (Backups)                                |
| X    |      | Software antivirus                                           |
|      | X    | Monitoreo, mantenimiento e intervención manual para sistemas heredados |
|      | X    | Cifrado (Encryption)                                         |
|      | X    | Sistema de gestión de contraseñas                            |
| X    |      | Cerraduras (oficinas, tiendas, almacenes)                    |
| X    |      | Vigilancia por circuito cerrado de televisión (CCTV)         |
| X    |      | Detección/previsión de incendios (alarma contra incendios, sistema de rociadores, etc.) |

### Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago (PCI DSS)

| Sí   | No   | Mejor práctica                                               |
| ---- | ---- | ------------------------------------------------------------ |
|      | X    | Solo los usuarios autorizados tienen acceso a la información de las tarjetas de crédito de los clientes. |
|      | X    | La información de las tarjetas de crédito se almacena, acepta, procesa y transmite internamente en un entorno seguro. |
|      | X    | Implementar procedimientos de cifrado de datos para asegurar mejor los puntos de transacción y los datos de las tarjetas de crédito. |
|      | X    | Adoptar políticas de gestión segura de contraseñas.          |

### Reglamento General de Protección de Datos (GDPR)

| Sí   | No   | Mejor práctica                                               |
| ---- | ---- | ------------------------------------------------------------ |
|      | X    | Los datos de los clientes de la UE se mantienen privados/seguros. |
| X    |      | Hay un plan en marcha para notificar a los clientes de la UE dentro de las 72 horas si sus datos han sido comprometidos/hay una brecha. |
| X    |      | Asegurar que los datos estén correctamente clasificados e inventariados. |
| X    |      | Hacer cumplir políticas de privacidad, procedimientos y procesos para documentar y mantener adecuadamente los datos. |

### Controles del Sistema y de las Organizaciones (SOC tipo 1, SOC tipo 2)

| Sí   | No   | Mejor práctica                                               |
| ---- | ---- | ------------------------------------------------------------ |
|      | X    | Se establecen políticas de acceso de usuarios.               |
|      | X    | Los datos sensibles (PII/SPII) son confidenciales/privados.  |
| X    |      | La integridad de los datos garantiza que los datos sean consistentes, completos, precisos y hayan sido validados. |
|      | X    | Los datos están disponibles para las personas autorizadas a acceder a ellos. |

Para comprobar la correcta realización de esta auditoria el curso de Google nos proporciona una manera de resolver el ejercicio [aqui](https://github.com/Ramonperu/AuditSimulation/blob/main/Solution.docx)