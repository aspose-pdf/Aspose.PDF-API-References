---
title: "System::ComponentModel::EnumConverter clase"
linktitle: "EnumConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ComponentModel::EnumConverter clase. Clase ficticia para que el código traducido que usa EnumConverter compile. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.componentmodel/enumconverter/
---
## EnumConverter class


Clase ficticia para que el código traducido que usa EnumConverter compile. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CanConvertFrom](./canconvertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Comprueba si los tipos son convertibles; no implementado. |
| [CanConvertTo](./canconvertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Comprueba si los tipos son convertibles; no implementado. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) override | Realiza la conversión de tipo real; no implementado. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Realiza la conversión de tipo real; no implementado. |
| [EnumConverter](./enumconverter/)(const System::TypeInfo\&) | Información RTTI. |
| [get_EnumType](./get_enumtype/)() | Obtiene el tipo de enumeración con el que trabaja [EnumConverter](./); no implementado. |
## Ver también

* Class [TypeConverter](../typeconverter/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
