---
title: "Aspose::Pdf::Facades::FormEditor::CopyInnerField metod"
linktitle: "CopyInnerField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::FormEditor::CopyInnerField metod. Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.facades/formeditor/copyinnerfield/
---
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t) method


Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Det gamla fullständigt kvalificerade fältnamnet. |
| newFieldName | const System::String\& | Det nya fullständigt kvalificerade fältnamnet. Om null kommer det att sättas till fieldName + "~". |
| pageNum | int32_t | Numret på sidan som ska hålla det nya fältet. Om -1 kommer det nya fältet att kopieras till samma sida som det gamla fältet är placerat på. |

## Se även

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t, float, float) method


Kopierar ett befintligt fält till en ny position som anges av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | const System::String\& | Det gamla fullständigt kvalificerade fältnamnet. |
| newFieldName | const System::String\& | Det nya fullständigt kvalificerade fältnamnet. Om null kommer det att sättas till fieldName + "~". |
| pageNum | int32_t | Numret på sidan som ska hålla det nya fältet. Om -1 kommer det nya fältet att kopieras till samma sida som det gamla fältet är placerat på. |
| abscissa | float | Abskissan för det nya fältet. Om -1 kommer abskissan att bli lika med den ursprungliga. |
| ordinate | float | Ordinaten för det nya fältet. Om -1 kommer ordinaten att bli lika med den ursprungliga. |

## Se även

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
