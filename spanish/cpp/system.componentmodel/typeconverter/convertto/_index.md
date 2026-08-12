---
title: "System::ComponentModel::TypeConverter::ConvertTo método"
linktitle: "ConvertTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ComponentModel::TypeConverter::ConvertTo método. Convierte un objeto a un tipo específico en C++."
type: docs
weight: 500
url: /es/cpp/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Convierte el objeto a un tipo específico.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| cultura | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Cultura a usar al convertir objetos. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) para convertir. |
| destinationType | const System::TypeInfo\& | Tipo al que convertir. |

### ReturnValue

Objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Convierte el objeto a un tipo específico.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) para convertir. |
| destinationType | const System::TypeInfo\& | Tipo al que convertir. |

### ReturnValue

Objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
