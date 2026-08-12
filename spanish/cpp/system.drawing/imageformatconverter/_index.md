---
title: "System::Drawing::ImageFormatConverter clase"
linktitle: "ImageFormatConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::ImageFormatConverter clase. Convierte objetos ImageFormat de un tipo de datos a otro. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.drawing/imageformatconverter/
---
## ImageFormatConverter class


Convierte objetos ImageFormat de un tipo de datos a otro. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ImageFormatConverter : public System::ComponentModel::TypeConverter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&) override | Convierte objetos. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<System::Object\>\&) | Convierte objetos. |
| virtual [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Convierte objetos. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Convierte cadena a objeto. |
| [ConvertTo](./convertto/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) override | Convierte el objeto a un tipo específico. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Convierte el objeto a un tipo específico. |
| virtual [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Convierte el objeto a un tipo específico. |
| [ImageFormatConverter](./imageformatconverter/)() | Construye una nueva instancia de [ImageFormatConverter](./). |
## Ver también

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
