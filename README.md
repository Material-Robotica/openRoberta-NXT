# LEGO Mindstorms NXT + Open Roberta Lab en Windows 11
 
Material para conectar ladrillos **LEGO Mindstorms NXT** a [Open Roberta Lab](https://lab.open-roberta.org) por USB desde computadoras con Windows 11.
 
## 📘 Guía paso a paso
 
**[Abrir la guía: NXT + Open Roberta en Windows](https://material-robotica.github.io/openRoberta-NXT/GuiaNXT-openRobertaWindows.html)**
 
La guía documenta el proceso completo, incluidos los problemas que aparecen en Windows 11 y cómo resolverlos:
 
- Descarga e instalación del programa USB de Open Roberta para NXT.
- Diagnóstico del NXT en el Administrador de dispositivos (`VID_0694&PID_0002`).
- Instalación del driver **Fantom** de LEGO en Windows de 64 bits, con la corrección del `setup.ini`.
- Cómo ejecutar el instalador cuando Windows lo bloquea por su firma digital vencida.
- Conexión del NXT con Open Roberta Lab.
## 📦 Instaladores
 
Los instaladores necesarios están guardados como copia de respaldo en el release **[instaladores-nxt](https://github.com/Material-Robotica/openRoberta-NXT/releases/tag/instaladores-nxt)**, por si las páginas originales dejan de estar disponibles:
 
| Archivo | Para qué sirve | Fuente original |
|---|---|---|
| `OpenRobertaUSBNXTSetupEN-1.0.0.msi` | Programa puente entre el NXT y Open Roberta Lab | [OpenRoberta/robertalab-usbprogram-nxt](https://github.com/OpenRoberta/robertalab-usbprogram-nxt/releases) |
| `NXT Fantom Drivers v120.zip` | Driver USB de LEGO para que Windows reconozca el NXT | [Softpedia](https://drivers.softpedia.com/get/Other-DRIVERS-TOOLS/Others/LEGO-Mindstorms-NXT-Fantom-Driver-102.shtml) |
 
## ⚠️ Firmware del NXT
 
Open Roberta convierte los bloques del NXT a **NXC**, que se ejecuta sobre el **firmware estándar de LEGO**. Un NXT con **leJOS** no ejecuta esos programas.
 
A diferencia del EV3, el NXT tiene un solo firmware a la vez, así que cada ladrillo se usa para una cosa:
 
| Firmware | Uso |
|---|---|
| LEGO (original) | Open Roberta Lab |
| leJOS NXJ | Programación en Java |
 
El cambio de firmware es reversible en ambos sentidos.
 
## 🔗 Material relacionado
 
- [openRoberta-ev3](https://github.com/Material-Robotica/openRoberta-ev3): kit para conectar robots LEGO EV3 con leJOS a Open Roberta Lab.
- [python-spikePrime](https://github.com/Material-Robotica/python-spikePrime): programación de LEGO SPIKE Prime en Python con Pybricks.
---
 
Prof. Elizabeth Izquierdo · Material-Robotica
 
