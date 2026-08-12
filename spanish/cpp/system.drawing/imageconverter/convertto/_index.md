---
title: "Método System::Drawing::ImageConverter::ConvertTo"
linktitle: "ConvertTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Drawing::ImageConverter::ConvertTo. Convierte el objeto a un tipo específico en C++."
type: docs
weight: 200
url: /es/cpp/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Convierte el objeto a un tipo específico.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\& | Información del contexto de conversión de [Object](../../../system/object/) |
| cultura | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Cultura a usar al convertir objetos |
| valor | const System::SharedPtr\<System::Object\>\& | Un objeto a convertir. |
| destinationType | const System::TypeInfo\& | Un tipo al que convertir. |

### ReturnValue

Objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [ImageConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
