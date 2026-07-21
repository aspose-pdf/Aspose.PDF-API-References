---
title: "Aspose::Pdf::Facades::FormEditor::CopyInnerField método"
linktitle: "CopyInnerField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::FormEditor::CopyInnerField método. Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento, que contiene todo lo que tiene el documento origen, excepto el campo recién copiado en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.facades/formeditor/copyinnerfield/
---
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t) method


Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento que contiene todo lo que tiene el documento original, excepto el campo recién copiado.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre de campo totalmente calificado antiguo. |
| newFieldName | const System::String\& | El nuevo nombre de campo totalmente calificado. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | int32_t | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página donde está alojado el anterior. |

## Ver también

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t, float, float) method


Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas. Se producirá un nuevo documento que contiene todo lo que tiene el documento original, excepto el campo recién copiado.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre de campo totalmente calificado antiguo. |
| newFieldName | const System::String\& | El nuevo nombre de campo totalmente calificado. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | int32_t | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página donde está alojado el anterior. |
| abscissa | float | La abscisa del nuevo campo. Si es -1, la abscisa será igual a la original. |
| ordinate | float | La ordenada del nuevo campo. Si es -1, la ordenada será igual a la original. |

## Ver también

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
