---
title: "Aspose::Pdf::Facades::FormEditor::CopyOuterField metod"
linktitle: "CopyOuterField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::FormEditor::CopyOuterField metod. Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med originalsidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknappar) i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/formeditor/copyouterfield/
---
## FormEditor::CopyOuterField(const System::String\&, const System::String\&) method


Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | const System::String\& | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | const System::String\& | Det ursprungliga fullständigt kvalificerade fältnamnet. |

## Se även

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t) method


Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | const System::String\& | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | const System::String\& | Det ursprungliga fullständigt kvalificerade fältnamnet. |
| pageNum | int32_t | Numret på sidan som ska hålla det nya fältet. Om -1 kommer det nya fältet att kopieras till samma sida som det gamla fältet är placerat på. |

## Se även

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(const System::String\&, const System::String\&, int32_t, float, float) method


Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(const System::String &srcFileName, const System::String &fieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | const System::String\& | Namnet på PDF-dokumentet som innehåller fältet som ska kopieras. |
| fieldName | const System::String\& | Det ursprungliga fullständigt kvalificerade fältnamnet. |
| pageNum | int32_t | Numret på sidan som ska hålla det nya fältet. Om -1 kommer det nya fältet att kopieras till samma sida som det gamla fältet är placerat på. |
| abscissa | float | Abskissan för det nya fältet. Om -1 kommer abskissan att bli lika med den ursprungliga. |
| ordinate | float | Ordinaten för det nya fältet. Om -1 kommer ordinaten att bli lika med den ursprungliga. |

## Se även

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
