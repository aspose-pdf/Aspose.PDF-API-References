---
title: "Aspose::Pdf::Facades::FormEditor::AddField método"
linktitle: "AddField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::FormEditor::AddField método. Añadir un campo del tipo especificado al formulario en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.facades/formeditor/addfield/
---
## FormEditor::AddField(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) method


Agregar campo del tipo especificado al formulario.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, const System::String &initValue, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo que debe añadirse. |
| fieldName | const System::String\& | Nombre del campo que debe añadirse. |
| initValue | const System::String\& | Valor inicial del campo. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) número donde debe colocarse el nuevo campo. |
| llx | float | Abscisa de la esquina inferior izquierda del campo. |
| lly | float | Ordenada de la esquina inferior izquierda del campo. |
| urx | float | Abscisa de la esquina superior derecha del campo. |
| ury | float | Ordenada de la esquina superior derecha del campo. |

### ReturnValue

true si el campo se añadió correctamente.
## Observaciones



///
## Ver también

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::AddField(FieldType, const System::String\&, int32_t, float, float, float, float) method


Agregar campo del tipo especificado al formulario.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo que debe añadirse. |
| fieldName | const System::String\& | Nombre del campo que debe añadirse. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) número donde debe colocarse el nuevo campo. |
| llx | float | Abscisa de la esquina inferior izquierda del campo. |
| lly | float | Ordenada de la esquina inferior izquierda del campo. |
| urx | float | Abscisa de la esquina superior derecha del campo. |
| ury | float | Ordenada de la esquina superior derecha del campo. |

### ReturnValue

true si el campo se añadió correctamente.

## Ver también

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
