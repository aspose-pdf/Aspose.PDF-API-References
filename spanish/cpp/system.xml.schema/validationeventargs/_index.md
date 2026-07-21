---
title: "Clase System::Xml::Schema::ValidationEventArgs"
linktitle: "ValidationEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::ValidationEventArgs. Devuelve información detallada relacionada con el ValidationEventHandler en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.schema/validationeventargs/
---
## ValidationEventArgs class


Devuelve información detallada relacionada con el [ValidationEventHandler](../validationeventhandler/).

```cpp
class ValidationEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Exception](./get_exception/)() | Devuelve la [XmlSchemaException](../xmlschemaexception/) asociada al evento de validación. |
| [get_Message](./get_message/)() | Devuelve la descripción de texto correspondiente al evento de validación. |
| [get_Severity](./get_severity/)() | Devuelve la gravedad del evento de validación. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
