---
title: "Método Aspose::Pdf::Facades::FormEditor::CopyOuterField"
linktitle: "CopyOuterField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::FormEditor::CopyOuterField. Copia un campo existente de un documento PDF a otro documento conservando el número de página y coordenadas originales. Aviso: Solo para campos AcroForm (excluyendo botones de radio) en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/formeditor/copyouterfield/
---
## FormEditor::CopyOuterField(const System::String\&, const System::String\&) method


Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas originales. Aviso: Solo para campos AcroForm (excluyendo botones de opción).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | const System::String\& | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | const System::String\& | El nombre de campo totalmente calificado original. |

## Ver también

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t) method


Copia un campo existente de un documento PDF a otro documento con el número de página especificado y coordenadas originales. Aviso: Solo para campos AcroForm (excluyendo botones de opción).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | const System::String\& | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | const System::String\& | El nombre de campo totalmente calificado original. |
| pageNum | int32_t | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página donde está alojado el anterior. |

## Ver también

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t, float, float) method


Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas especificados. Aviso: Solo para campos AcroForm (excluyendo botones de opción).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | const System::String\& | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | const System::String\& | El nombre de campo totalmente calificado original. |
| pageNum | int32_t | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página donde está alojado el anterior. |
| abscissa | float | La abscisa del nuevo campo. Si es -1, la abscisa será igual a la original. |
| ordinate | float | La ordenada del nuevo campo. Si es -1, la ordenada será igual a la original. |

## Ver también

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
