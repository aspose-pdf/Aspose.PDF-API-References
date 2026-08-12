---
title: "Aspose::Pdf::BaseOperatorCollection class"
linktitle: "BaseOperatorCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::BaseOperatorCollection class. Representerar basklass för operator‑samling i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class


Representerar basklass för operator‑samling.

```cpp
class BaseOperatorCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Operator>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<Operator\>\&) | Lägger till en ny operator i samlingen. |
| virtual [CancelUpdate](./cancelupdate/)() | Avbryter den senaste uppdateringen. Denna metod kan anropas när förändringen inte bör utlösa en innehållsuppdatering. |
| virtual [Clear](./clear/)() | Rensar samling. |
| virtual [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const | Kontrollerar om operator finns i samlingen. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) | Kopierar operatorer till operatorlistan. |
| virtual [get_Count](./get_count/)() const | Hämtar antalet operatorer i samlingen. |
| virtual [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const | Indikerar huruvida samlingen är begränsad till snabb textutvinning. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Returnerar true om samlingen är skrivskyddad. |
| virtual [GetEnumerator](./getenumerator/)() | Returnerar enumerator för samlingen. |
| virtual [idx_get](./idx_get/)(int32_t) | Hämtar operatorn efter dess index. |
| virtual [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) | Hämtar operatorn efter dess index. |
| virtual [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) | Infogar operator i samlingen. |
| virtual [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) | Tar bort operator från samlingen. |
| virtual [ResumeUpdate](./resumeupdate/)() | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. |
| virtual [SuppressUpdate](./suppressupdate/)() | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
