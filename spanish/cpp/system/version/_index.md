---
title: "Clase System::Version"
linktitle: "Versión"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Version. Representa un número de versión. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 7600
url: /es/cpp/system/version/
---
## Version class


Representa un número de versión. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Version
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareTo](./compareto/)(const Version\&) const | Compara las versiones representadas por el objeto actual y el objeto especificado. |
| [Equals](./equals/)(const Version\&) const | Determina si los números de versión representados por el actual y los objetos especificados son iguales. |
| [get_Build](./get_build/)() const | Devuelve el número de compilación. |
| [get_Major](./get_major/)() const | Devuelve la versión principal. |
| [get_MajorRevision](./get_majorrevision/)() const | Devuelve el valor de 16 bits altos del número de revisión. |
| [get_Minor](./get_minor/)() const | Devuelve la versión menor. |
| [get_MinorRevision](./get_minorrevision/)() const | Devuelve el valor de 16 bits bajos del número de revisión. |
| [get_Revision](./get_revision/)() const | Devuelve el número de revisión. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| static [Parse](./parse/)(const String\&) | Convierte la representación en cadena de un número de versión en una instancia equivalente de la clase [Version](./). |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del número de versión representado por el objeto actual. |
| [ToString](./tostring/)(int) const | Devuelve la representación en cadena del número especificado de secciones del número de versión representado por el objeto actual. |
| [Version](./version/)(int, int, int, int) | Construye una instancia que representa los valores especificados de mayor, menor, compilación y revisión. |
| [Version](./version/)(int, int, int) | Construye una instancia que representa los valores especificados de mayor, menor y compilación. |
| [Version](./version/)(int, int) | Construye una instancia que representa el número mayor y los valores especificados. |
| [Version](./version/)(const String\&) | Construye una instancia que representa el número de versión representado como una cadena. |
| [Version](./version/)() | Construye una instancia que representa el número de versión 0.0.-1.-1. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
