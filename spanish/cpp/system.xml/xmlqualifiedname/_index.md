---
title: "Clase System::Xml::XmlQualifiedName"
linktitle: "XmlQualifiedName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlQualifiedName. Representa un nombre calificado XML en C++."
type: docs
weight: 3200
url: /es/cpp/system.xml/xmlqualifiedname/
---
## XmlQualifiedName class


Representa un nombre calificado XML.

```cpp
class XmlQualifiedName : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determina si el objeto [XmlQualifiedName](./) especificado es igual al objeto [XmlQualifiedName](./) actual. |
| [get_IsEmpty](./get_isempty/)() const | Devuelve un valor que indica si el [XmlQualifiedName](./) está vacío. |
| [get_Name](./get_name/)() const | Devuelve una representación en cadena del nombre calificado del [XmlQualifiedName](./). |
| [get_Namespace](./get_namespace/)() const | Devuelve una representación en cadena del espacio de nombres del [XmlQualifiedName](./). |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash para el [XmlQualifiedName](./). |
| static [ToString](./tostring/)(const String\&, const String\&) | Devuelve el valor de cadena del [XmlQualifiedName](./). |
| [ToString](./tostring/)() const override | Devuelve el valor de cadena del [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)() | Inicializa una nueva instancia de la clase [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&) | Inicializa una nueva instancia de la clase [XmlQualifiedName](./) con el nombre especificado. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&, const String\&) | Inicializa una nueva instancia de la clase [XmlQualifiedName](./) con el nombre y espacio de nombres especificados. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Proporciona un [XmlQualifiedName](./) vacío. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
