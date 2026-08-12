---
title: "Aspose::Pdf::OutlineItemCollection-klass"
linktitle: "OutlineItemCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OutlineItemCollection-klass. Representerar konturpost i konturhierarkin för PDF-dokument i C++."
type: docs
weight: 12600
url: /sv/cpp/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class


Representerar en dispositionspost i dispositionshierarkin för PDF-dokumentet.

```cpp
class OutlineItemCollection : public Aspose::Pdf::Outlines
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Lägger till ett dispositionsobjekt i samlingen. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Kontrollerar om samlingen innehåller det angivna objektet. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Kopierar konturposterna till en [System.Array](../../system/array/), med start vid ett specifikt [System.Array](../../system/array/) index. |
| [Delete](./delete/)() | Tar bort detta konturelement från dokumentets konturhierarki. |
| [Delete](./delete/)(const System::String\&) | Tar bort konturpost med angivet namn från dokumentets konturhierarki. |
| [get_Action](./get_action/)() | Hämtar åtgärden för detta konturelement. |
| [get_Bold](./get_bold/)() | Hämtar fetstil-flaggan för titeltexten för detta konturelement. |
| [get_Color](./get_color/)() | Hämtar färgen för titeltexten för detta konturelement. |
| [get_Count](./get_count/)() const override | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount ger antalet synliga dispositionsobjekt på alla nivåer. |
| [get_Destination](./get_destination/)() | Hämtar destinationen för detta konturelement. |
| [get_First](./get_first/)() const | Hämtar konturelementet som representerar det första toppnivåelementet i konturhierarkin. |
| [get_HasNext](./get_hasnext/)() | Kontrollera om konturelementet som representerar nästa element relativt detta element i konturhierarkin. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar värdet som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [get_Italic](./get_italic/)() | Hämtar kursiv-flaggan för titeltexten för detta konturelement. |
| [get_Last](./get_last/)() | Hämtar konturelementet som representerar det sista toppnivåelementet i konturhierarkin. |
| [get_Level](./get_level/)() | Hämtar hierarkinivån för konturelementet. |
| [get_Next](./get_next/)() | Hämtar konturelementet som representerar nästa element relativt detta element i konturhierarkin. |
| [get_Open](./get_open/)() | Hämtar eller anger öppet status (true/false) för innehållspost. |
| [get_Parent](./get_parent/)() | Hämtar föräldraobjektet för denna innehållspost i innehållshierarkin. |
| [get_Prev](./get_prev/)() | Hämtar innehållsposten som representerar föregående post relativt denna post i innehållshierarkin. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling. |
| [get_Title](./get_title/)() | Hämtar titeln för denna innehållspost. |
| [get_VisibleCount](./get_visiblecount/)() override | Hämtar det totala antalet innehållsposter på alla nivåer i dokumentets innehållshierarki. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar innehållspost från samlingen med hjälp av index. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<OutlineItemCollection\>\&) | Infogar innehållsposten i samlingen på den angivna platsen. |
| [OutlineItemCollection](./outlineitemcollection/)(const System::SharedPtr\<OutlineCollection\>\&) | Initierar en instans av innehållspost med hjälp av rot‑hierarkiobjektet. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Ta bort en post i innehållssamlingen. |
| [Remove](./remove/)(int32_t) | Ta bort objekt efter index. |
| [set_Action](./set_action/)(const System::SharedPtr\<Annotations::PdfAction\>\&) | Anger åtgärden för denna innehållspost. |
| [set_Bold](./set_bold/)(bool) | Anger fetstil‑flagga för titeltexten i denna innehållspost. |
| [set_Color](./set_color/)(System::Drawing::Color) | Anger färgen för titeltexten i denna innehållspost. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Anger destinationen för denna innehållspost. |
| [set_Italic](./set_italic/)(bool) | Anger kursiv‑flagga för titeltexten i denna innehållspost. |
| [set_Open](./set_open/)(bool) | Hämtar eller anger öppet status (true/false) för innehållspost. |
| [set_Title](./set_title/)(const System::String\&) | Anger titeln för denna innehållspost. |
## Se även

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
