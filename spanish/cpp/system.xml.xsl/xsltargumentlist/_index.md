---
title: "Clase System::Xml::Xsl::XsltArgumentList"
linktitle: "XsltArgumentList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Xsl::XsltArgumentList. Contiene un número variable de argumentos que son parámetros XSLT o objetos de extensión en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.xsl/xsltargumentlist/
---
## XsltArgumentList class


Contiene un número variable de argumentos que son parámetros XSLT o objetos de extensión.

```cpp
class XsltArgumentList : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddExtensionObject](./addextensionobject/)(const String\&, const SharedPtr\<Object\>\&) | Agrega un nuevo objeto a la [XsltArgumentList](./) y lo asocia con el URI del espacio de nombres. |
| [AddParam](./addparam/)(const String\&, const String\&, const SharedPtr\<Object\>\&) | Agrega un parámetro a la [XsltArgumentList](./) y lo asocia con el nombre calificado del espacio de nombres. |
| [Clear](./clear/)() | Elimina todos los parámetros y objetos de extensión de la [XsltArgumentList](./). |
| [GetExtensionObject](./getextensionobject/)(const String\&) | Devuelve el objeto asociado con el espacio de nombres proporcionado. |
| [GetParam](./getparam/)(const String\&, const String\&) | Devuelve el parámetro asociado con el nombre calificado del espacio de nombres. |
| [RemoveExtensionObject](./removeextensionobject/)(const String\&) | Elimina el objeto con el URI del espacio de nombres de la [XsltArgumentList](./). |
| [RemoveParam](./removeparam/)(const String\&, const String\&) | Elimina el parámetro de la [XsltArgumentList](./). |
| [XsltArgumentList](./xsltargumentlist/)() | Implementa una nueva instancia de la [XsltArgumentList](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
