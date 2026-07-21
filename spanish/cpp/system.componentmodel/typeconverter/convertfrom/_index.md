---
title: "System::ComponentModel::TypeConverter::ConvertFrom método"
linktitle: "ConvertFrom"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ComponentModel::TypeConverter::ConvertFrom método. Convierte objetos en C++."
type: docs
weight: 200
url: /es/cpp/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) method


Convierte objetos.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| cultura | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Cultura a usar al convertir objetos. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) para convertir. |

### ReturnValue

objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method


Convierte cadena a objeto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| cultura | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Cultura a usar al convertir objetos. |
| valor | const System::String\& | Valor a convertir. |

### ReturnValue

objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) method


Convierte objetos.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) para convertir. |

### ReturnValue

objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
