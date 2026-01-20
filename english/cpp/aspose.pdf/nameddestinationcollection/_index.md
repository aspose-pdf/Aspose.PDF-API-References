---
title: Aspose::Pdf::NamedDestinationCollection class
linktitle: NamedDestinationCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::NamedDestinationCollection class. Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document in C++.'
type: docs
weight: 11600
url: /cpp/aspose.pdf/nameddestinationcollection/
---
## NamedDestinationCollection class


Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.

```cpp
class NamedDestinationCollection : public Aspose::Pdf::INamedDestinationCollection
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Add new named destination. |
| [get_Count](./get_count/)() override | Count of named destinations. |
| [get_Names](./get_names/)() override | List of names of the destinations. |
| [idx_get](./idx_get/)(System::String) override | Gets appointment by its name. |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Sets appointment by its name. |
| [Remove](./remove/)(System::String) override | Delete named destination. |
## See Also

* Class [INamedDestinationCollection](../inameddestinationcollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
