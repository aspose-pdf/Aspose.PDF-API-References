---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary::Remove metod"
linktitle: "Ta bort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary::Remove method. Tar bort den första förekomsten av ett specifikt objekt från CosPdfDictionary i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) method


Tar bort den första förekomsten av ett specifikt objekt från [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<ICosPdfPrimitive>> &item) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\& | Objektet som ska tas bort från [CosPdfDictionary](../). |

### ReturnValue

true om objektet framgångsrikt togs bort från [CosPdfDictionary](../); annars false. Denna metod returnerar också false om objektet inte hittas i den ursprungliga [CosPdfDictionary](../).

## Se även

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICosPdfPrimitive](../../icospdfprimitive/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
## CosPdfDictionary::Remove(const System::String\&) method


Tar bort elementet med den angivna nyckeln från [CosPdfDictionary](../).

```cpp
bool Aspose::Pdf::DataEditor::CosPdfDictionary::Remove(const System::String &key) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const System::String\& | Nyckeln för elementet som ska tas bort. |

### ReturnValue

True om elementet togs bort framgångsrikt; annars false. Denna metod returnerar också false om nyckeln inte hittades i den ursprungliga ordboken eller om nyckeln inte är redigerbar.

## Se även

* Class [String](../../../system/string/)
* Class [CosPdfDictionary](../)
* Namespace [Aspose::Pdf::DataEditor](../../)
* Library [Aspose.PDF for C++](../../../)
