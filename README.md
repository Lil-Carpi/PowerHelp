# PowerHelp 
Herramienta de ayuda para PowerShell. Mas rapida que Get-Help y menos confuso de usar.

---
## Descripción
PowerHelp es una utilidad de Windows para Powershell que despliega ayuda sobre un comando.
Actualmente, la versión nativa del propio PowerShell es lenta, no en local, confusa y llena de errores. PowerHelp soluciona esto.

La primera versión de PowerHelp (PowerHelp 1.0) estará desarrollada principalmente en PowerShell. Será algo pesada, pero sera lo mejor en velocidad de programación, ya que se podría hacer en un fin de semana.

La segunda versión de PowerHelp (PowerHelp 2.0) estará desarrollada en GoLang. Esto para reducir el tamaño de la versión 1.0 y mejorar la conexión a la base de datos.

La tercera versión, renombrada PoweRHelp (PoweRHelp 1.0) estará desarrollada en Rust. Esto para aumentar la velocidad de ejecucion de la version de GoLang.
Queda pendiente la decisión de si crear otro repositorio o usar este mismo pero con otra rama o un fork.

---
## Arquitectura
PowerHelp utilizara un sistema basado en una base de datos local lo mas pequeñita posible. Se descargara juntamente con el propio programa, conteniendo todos los archivos de ayuda dentro de la propia base de datos. Se pueden descargar todos los idiomas que se encuentren en `gh -Languages` o `GetHelp -Languages`.

Es posible que se utilicen y integren los proyectos [PoshCode/tldr](https://github.com/PoshCode/tldr) o [PowerShell/platyPS](https://github.com/powershell/platyps).

---
### El porque de hacer esto
Hermano, llevo utilizando Linux de hace años, y jamas he visto un software tan mal hecho como lo es el Get-Help de PowerShell, y solo me tomó 5 minutos darme cuenta.

---
Lil_Carpi - Licencia MIT
