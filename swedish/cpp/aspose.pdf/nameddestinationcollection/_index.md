---
title: "Aspose::Pdf::NamedDestinationCollection klass"
linktitle: "NamedDestinationCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::NamedDestinationCollection klass. Klassen representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, \"Named Destinations\") och (se 7.7.4, \"Name Dictionary\")) i pdf-dokumentet i C++."
type: docs
weight: 11600
url: /sv/cpp/aspose.pdf/nameddestinationcollection/
---
## NamedDestinationCollection class


Klassen representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, "Named Destinations") och (se 7.7.4, "Name Dictionary")) i pdf-dokumentet.

```cpp
class NamedDestinationCollection : public Aspose::Pdf::INamedDestinationCollection
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Lägg till en ny namngiven destination. |
| [get_Count](./get_count/)() override | Antal namngivna destinationer. |
| [get_Names](./get_names/)() override | Lista över namn på destinationerna. |
| [idx_get](./idx_get/)(System::String) override | Hämtar möte efter dess namn. |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Ställer in möte efter dess namn. |
| [Remove](./remove/)(System::String) override | Ta bort namngiven destination. |
## Se även

* Class [INamedDestinationCollection](../inameddestinationcollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
