---
title: "Clase System::Guid"
linktitle: "Guid"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Guid. Representa un Identificador Globalmente Único. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 3100
url: /es/cpp/system/guid/
---
## Guid class


Representa un Identificador Globalmente Único. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Guid
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareTo](./compareto/)(const Guid\&) const | Realiza una comparación aritmética de los GUIDs representados por los objetos actual y especificado. |
| [Equals](./equals/)(const Guid\&) const | Determina si los GUIDs representados por los objetos actual y especificado son iguales. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [Guid](./guid/)() | Construye un objeto que representa un GUID compuesto únicamente de ceros. |
| [Guid](./guid/)(const ArrayPtr\<uint8_t\>\&) | Construye un objeto que representa un GUID especificado como una matriz de valores enteros sin signo de 8 bits. |
| [Guid](./guid/)(const System::Details::ArrayView\<uint8_t\>\&) | Construye un objeto que representa un GUID especificado como una vista de matriz de valores enteros sin signo de 8 bits. |
| [Guid](./guid/)(const String\&) | Construye un objeto que representa un GUID especificado como una cadena. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) | Construye una instancia de la clase [Guid](./) a partir de los componentes de GUID especificados. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) | Construye una instancia de la clase [Guid](./) a partir de los componentes de GUID especificados. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Construye una instancia de la clase [Guid](./) a partir de los enteros sin signo y bytes especificados. |
| [Guid](./guid/)(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Construye una instancia de la clase [Guid](./) a partir de los enteros sin signo y bytes especificados. |
| [Guid](./guid/)(const Guid\&) | Construye un objeto que representa el mismo GUID que el objeto especificado. |
| static [NewGuid](./newguid/)() | Genera un nuevo GUID y devuelve un objeto [Guid](./) que lo representa. |
| [operator!=](./operator!=/)(const Guid\&) const | Determina si los GUIDs representados por los objetos actual y especificado no son iguales. |
| [operator=](./operator=/)(const Guid\&) | Asigna al objeto actual el valor GUID representado por el objeto [Guid](./) especificado. |
| [operator==](./operator==/)(const Guid\&) const | Determina si los GUIDs representados por los objetos actual y especificado son iguales. |
| static [Parse](./parse/)(const String\&) | Convierte la representación de cadena especificada de un GUID en un objeto [Guid](./) equivalente. |
| [ToByteArray](./tobytearray/)() const | Convierte el GUID representado por el objeto actual en una matriz de bytes. |
| [ToString](./tostring/)() const | Convierte el GUID representado por el objeto actual a su representación en cadena. |
| [ToString](./tostring/)(const String\&) const | Convierte el GUID representado por el objeto actual a su representación en cadena usando el formato de cadena especificado. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const | Convierte el GUID representado por el objeto actual a su representación en cadena usando el formato de cadena especificado y la cultura. |
| static [TryParse](./tryparse/)(const String\&, Guid\&) | Intenta convertir la cadena especificada en un objeto [Guid](./). |
| [~Guid](./~guid/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Representa un GUID que tiene un valor de 0. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
