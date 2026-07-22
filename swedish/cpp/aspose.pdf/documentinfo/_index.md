---
title: "Aspose::Pdf::DocumentInfo klass"
linktitle: "DocumentInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocumentInfo klass. Representerar metadata för PDF-dokument i C++."
type: docs
weight: 4200
url: /sv/cpp/aspose.pdf/documentinfo/
---
## DocumentInfo class


Representerar metadata för PDF-dokument.

```cpp
class DocumentInfo : public System::Collections::Generic::Dictionary<System::String, System::String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::String\&) override | Lägger till ett element med den angivna nyckeln och värdet i samlingen. |
| [Clear](./clear/)() override | Rensar dokumentinformationen. |
| [ClearCustomData](./clearcustomdata/)() | Rensar endast anpassad data, lämnar alla andra fördefinierade värden (Titel, Författare, etc.). |
| [DocumentInfo](./documentinfo/)(const System::SharedPtr\<Document\>\&) | Initiera [DocumentInfo](./) instans. |
| [get_Author](./get_author/)() | Hämtar dokumentets författare. |
| [get_CreationDate](./get_creationdate/)() | Hämtar datumet för dokumentets skapande. |
| [get_CreationTimeZone](./get_creationtimezone/)() | Tidzon för skapandedatum. |
| [get_Creator](./get_creator/)() | Hämtar dokumentets skapare. |
| [get_Keywords](./get_keywords/)() | Hämtar eller anger nyckelorden för dokumentet. |
| [get_ModDate](./get_moddate/)() | Hämtar datumet för dokumentets ändring. |
| [get_ModTimeZone](./get_modtimezone/)() | Tidzon för ändringsdatum. |
| [get_Producer](./get_producer/)() | Hämtar dokumentets producent. |
| [get_Subject](./get_subject/)() | Hämtar dokumentets ämne. |
| [get_Title](./get_title/)() | Hämtar dokumentets titel. |
| [get_Trapped](./get_trapped/)() | Hämtar flaggan för trapped. |
| [idx_get](./idx_get/)(const System::String\&) const override | Hämtar värdet som är associerat med den angivna nyckeln. |
| [idx_set](./idx_set/)(const System::String\&, System::String) override | Anger värdet som är associerat med den angivna nyckeln. |
| static [IsPredefinedKey](./ispredefinedkey/)(const System::String\&) | Avgör om nyckeln är fördefinierad (Title, Author, etc.), inte anpassad. |
| [Remove](./remove/)(const System::String\&) override | Tar bort elementet med den angivna nyckeln från samlingen. |
| [set_Author](./set_author/)(const System::String\&) | Ställer in dokumentets författare. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Ställer in datumet för dokumentets skapande. |
| [set_CreationTimeZone](./set_creationtimezone/)(System::TimeSpan) | Tidzon för skapandedatum. |
| [set_Creator](./set_creator/)(const System::String\&) | Ställer in dokumentets skapare. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Hämtar eller anger nyckelorden för dokumentet. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Ställer in datumet för dokumentets ändring. |
| [set_ModTimeZone](./set_modtimezone/)(System::TimeSpan) | Tidzon för ändringsdatum. |
| [set_Producer](./set_producer/)(const System::String\&) | Ställer in dokumentets producent. |
| [set_Subject](./set_subject/)(const System::String\&) | Ställer in ämnet för dokumentet. |
| [set_Title](./set_title/)(const System::String\&) | Ställer in dokumentets titel. |
| [set_Trapped](./set_trapped/)(const System::String\&) | Ställer in den fångade flaggan. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
## Se även

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
