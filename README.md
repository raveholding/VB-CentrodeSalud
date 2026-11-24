# VB · Centro de Salud (demo)

Demo del **Sistema VB** para consultorio médico general, consultorio odontológico y clínica profesional (multiespecialidad).

- Selector **Modo demo** arriba: Médico general · Odontológico · Clínica profesional.
- Sala de espera en vivo (agendado → confirmado → en sala → llamado → en atención → pendiente de cobro → cerrado), pantalla para la TV y sobrecupos autorizados.
- Historia clínica: alertas, antecedentes, evoluciones firmadas, signos vitales, odontograma por pieza y cara, recetas, órdenes, certificados, adjuntos y consentimientos.
- Coberturas con copago (en Vender se cobra sólo el copago), prestaciones por período, autorizaciones y débitos.
- Planes de tratamiento y presupuestos, insumos por práctica, liquidación de profesionales y tablero gerencial.

Usuario de prueba: **Administrador · 1111**. Datos de ejemplo.

El código fuente vive en `raveholding/VB-Demo-Salud.Estetica/fuente` (mismo motor de turnos). Esta página se genera con:

```
cd fuente && VB_MED=1 python3 build.py barber <destino>/index.html
```
