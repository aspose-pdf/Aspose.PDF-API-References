---
title: "System::Drawing::ImageConverter clase"
linktitle: "ImageConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::ImageConverter clase. Convierte objetos Image de un tipo de datos a otro. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.drawing/imageconverter/
---
## ImageConverter class


Convierte objetos [Image](../image/) de un tipo de datos a otro. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Convierte el objeto a un tipo específico. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Convierte el objeto a un tipo específico. |
| [ImageConverter](./imageconverter/)() | Construye una nueva instancia de [ImageConverter](./). |
## Ver también

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
