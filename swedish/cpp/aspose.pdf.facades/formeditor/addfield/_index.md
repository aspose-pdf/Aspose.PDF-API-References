---
title: "Aspose::Pdf::Facades::FormEditor::AddField metod"
linktitle: "AddField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::FormEditor::AddField metod. Lägg till fält av angiven typ till formuläret i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.facades/formeditor/addfield/
---
## FormEditor::AddField(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) method


Lägg till fält av angiven typ i formuläret.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, const System::String &initValue, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | FieldType | Typ av fält som måste läggas till. |
| fieldName | const System::String\& | Namn på fältet som måste läggas till. |
| initValue | const System::String\& | Initialvärde för fältet. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) nummer där det nya fältet ska placeras. |
| llx | float | Abskissa för fältets nedre vänstra hörn. |
| lly | float | Ordinat för fältets nedre vänstra hörn. |
| urx | float | Abskissa för fältets övre högra hörn. |
| ury | float | Ordinat för fältets övre högra hörn. |

### ReturnValue

true om fältet lades till framgångsrikt.
## Anmärkningar



///
## Se även

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::AddField(FieldType, const System::String\&, int32_t, float, float, float, float) method


Lägg till fält av angiven typ i formuläret.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | FieldType | Typ av fält som måste läggas till. |
| fieldName | const System::String\& | Namn på fältet som måste läggas till. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) nummer där det nya fältet ska placeras. |
| llx | float | Abskissa för fältets nedre vänstra hörn. |
| lly | float | Ordinat för fältets nedre vänstra hörn. |
| urx | float | Abskissa för fältets övre högra hörn. |
| ury | float | Ordinat för fältets övre högra hörn. |

### ReturnValue

true om fältet lades till framgångsrikt.

## Se även

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
