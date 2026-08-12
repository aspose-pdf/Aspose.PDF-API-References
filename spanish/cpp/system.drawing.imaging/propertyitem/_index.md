---
title: "Clase System::Drawing::Imaging::PropertyItem"
linktitle: "PropertyItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Imaging::PropertyItem. Representa una propiedad de metadatos que se incluye en un archivo de imagen. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.drawing.imaging/propertyitem/
---
## PropertyItem class


Representa una propiedad de metadatos que se incluye en un archivo de imagen. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class PropertyItem : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Id](./get_id/)() const | Devuelve el ID de la propiedad representada por el objeto actual. |
| [get_Len](./get_len/)() const | Devuelve la longitud de la propiedad representada por el objeto actual en bytes. |
| [get_Type](./get_type/)() const | Devuelve el tipo de la propiedad representada por el objeto actual en bytes. |
| [get_Value](./get_value/)() const | Devuelve el valor de la propiedad representada por el objeto actual en bytes. |
| [PropertyItem](./propertyitem/)() | Construye una nueva instancia de la clase [PropertyItem](./). |
| [set_Id](./set_id/)(int32_t) | Establece el ID de la propiedad representada por el objeto actual. |
| [set_Len](./set_len/)(int32_t) | Establece la longitud de la propiedad representada por el objeto actual en bytes. |
| [set_Type](./set_type/)(int16_t) | Establece el tipo de la propiedad representada por el objeto actual en bytes. |
| [set_Value](./set_value/)(const System::ArrayPtr\<uint8_t\>\&) | Establece el tipo de la propiedad representada por el objeto actual en bytes. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
