---
title: "System::OperatingSystem clase"
linktitle: "OperatingSystem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::OperatingSystem clase. Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 5300
url: /es/cpp/system/operatingsystem/
---
## OperatingSystem class


Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class OperatingSystem
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Platform](./get_platform/)() const | Devuelve el identificador de plataforma del sistema operativo representado por el objeto actual. |
| [get_ServicePack](./get_servicepack/)() const | Devuelve el nombre del service pack del sistema operativo representado por el objeto actual. |
| [get_Version](./get_version/)() const | Devuelve una referencia constante a un objeto [Version](../version/) que representa la versión del sistema operativo representado por el objeto actual. |
| [get_VersionString](./get_versionstring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |
| static [IsFreeBSD](./isfreebsd/)() | Indica si la aplicación actual se está ejecutando en FreeBSD. |
| static [IsLinux](./islinux/)() | Indica si la aplicación actual se está ejecutando en Linux. |
| static [IsMacOS](./ismacos/)() | Indica si la aplicación actual se está ejecutando en MacOS. |
| static [IsOSPlatform](./isosplatform/)(const String\&) | Indica si la aplicación actual se está ejecutando en la plataforma especificada. |
| static [IsWindows](./iswindows/)() | Indica si la aplicación actual se está ejecutando en [Windows](../../system.windows/). |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&) | Construye una instancia que representa un sistema operativo especificado como un identificador de plataforma y versión particulares. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&, const String\&) | Construye una instancia que representa un sistema operativo especificado como un identificador de plataforma, versión y paquete de servicio. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
