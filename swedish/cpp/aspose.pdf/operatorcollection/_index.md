---
title: "Aspose::Pdf::OperatorCollection klass"
linktitle: "OperatorCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OperatorCollection klass. Klassen representerar en samling av operatorer i C++."
type: docs
weight: 12100
url: /sv/cpp/aspose.pdf/operatorcollection/
---
## OperatorCollection class


Klassen representerar en samling av operatörer.

```cpp
class OperatorCollection : public Aspose::Pdf::BaseOperatorCollection,
                           public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Accepterar [IOperatorSelector](../ioperatorselector/) besökarobjekt för att bearbeta operatorer. |
| [Add](./add/)(const System::SharedPtr\<Operator\>\&) override | Lägger till en ny operator i samlingen. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Lägg till operatorer i slutet av innehållsoperatorerna. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) | Lägger till alla operatorer från en annan samling i samlingen. |
| [CancelUpdate](./cancelupdate/)() override | Avbryter den senaste uppdateringen. Denna metod kan anropas när förändringen inte bör utlösa en innehållsuppdatering. |
| [Clear](./clear/)() override | Tar bort alla operatorer från listan. |
| [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const override | Returnerar true om samlingen innehåller den angivna operatorn. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) override | Kopierar operatorer till operatorlistan. |
| [Delete](./delete/)(int32_t) | Raderar operator från samlingen. |
| [Delete](./delete/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Raderar operatorer från samlingen. |
| [Delete](./delete/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Raderar operatorer från samlingen. |
| [Dispose](./dispose/)() override | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [get_Count](./get_count/)() const override | Hämtar antalet operatorer i samlingen. |
| [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const override | Indikerar huruvida samlingen är begränsad till snabb textutvinning. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [GetEnumerator](./getenumerator/)() override | Returnerar enumerator för samlingen. |
| [idx_get](./idx_get/)(int32_t) override | Hämtar operatorn efter dess index. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) override | Hämtar operatorn efter dess index. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) override | Infogar operator i samlingen. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Infoga operatorer på den angivna positionen. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Infoga operatorer på den angivna positionen. |
| [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) override | Ta bort operator från samlingen. |
| [Replace](./replace/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Ersätt operatorer i samlingen med andra operatorer. |
| [ResumeUpdate](./resumeupdate/)(bool) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. Markerar alla operatorer som "changed" om parametern invalidate är true. |
| [ResumeUpdate](./resumeupdate/)() override | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns väntande ändringar. |
| [SuppressUpdate](./suppressupdate/)() override | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| [ToString](./tostring/)() const override | Returnerar textrepresentation av operatorn. |
## Se även

* Class [BaseOperatorCollection](../baseoperatorcollection/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
