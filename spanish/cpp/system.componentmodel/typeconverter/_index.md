---
title: "Clase System::ComponentModel::TypeConverter"
linktitle: "TypeConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::TypeConverter. Clase que maneja la conversión de tipos en el modelo de componentes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.componentmodel/typeconverter/
---
## TypeConverter class


Clase que maneja la conversión de tipos en el modelo de componentes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class TypeConverter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<System::Object\>\&) | Convierte objetos. |
| virtual [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Convierte objetos. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Convierte cadena a objeto. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::String\&) | Convierte una cadena invariante a un objeto. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Convierte una cadena invariante a un objeto. |
| [ConvertFromString](./convertfromstring/)(const System::String\&) | Convierte cadena a objeto. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Convierte cadena a objeto. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Convierte cadena a objeto. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Convierte el objeto a un tipo específico. |
| virtual [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Convierte el objeto a un tipo específico. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<System::Object\>\&) | Convierte un objeto a una cadena invariante. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Convierte un objeto a una cadena invariante. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<System::Object\>\&) | Convierte un objeto a una cadena. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Convierte un objeto a una cadena. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Convierte un objeto a una cadena. |
| [TypeConverter](./typeconverter/)() | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
