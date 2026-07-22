---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue metod"
linktitle: "TryGetValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue method. För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary::TryGetValue method


För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer.

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::TryGetValue(const System::String &key, System::SharedPtr<ICosPdfPrimitive> &value) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const System::String\& | Nyckelvärde |
| value | System::SharedPtr\<ICosPdfPrimitive\>\& | returnerar [ICosPdfPrimitive](../../icospdfprimitive/) för nyckeln eller null. |

### ReturnValue

Returnerar true om [ICosPdfPrimitive](../../icospdfprimitive/) är som string, name, bool, number. Returnerar false för alla andra typer.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
