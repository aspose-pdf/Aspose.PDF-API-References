---
title: "Clase System::Xml::NameTable"
linktitle: "NameTable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::NameTable. Implementa una XmlNameTable de un solo subproceso en C++."
type: docs
weight: 500
url: /es/cpp/system.xml/nametable/
---
## NameTable class


Implementa una [XmlNameTable](../xmlnametable/) de un solo subproceso.

```cpp
class NameTable : public System::Xml::XmlNameTable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const String\&) override | Atomiza la cadena especificada y la agrega a la [NameTable](./). |
| [Add](./add/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Atomiza la cadena especificada y la agrega a la [NameTable](./). |
| [Get](./get/)(const String\&) override | Devuelve la cadena atomizada con el valor especificado. |
| [Get](./get/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Devuelve la cadena atomizada que contiene los mismos caracteres que el rango especificado de caracteres en la matriz dada. |
| [NameTable](./nametable/)() | Inicializa una nueva instancia de la clase [NameTable](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlNameTable](../xmlnametable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
