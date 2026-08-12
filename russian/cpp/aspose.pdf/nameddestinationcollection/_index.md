---
title: "Класс Aspose::Pdf::NamedDestinationCollection"
linktitle: "NamedDestinationCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::NamedDestinationCollection класс. Класс представляет собой коллекцию всех назначений (дерево имён, сопоставляющее строковые имена с назначениями (см. 12.3.2.3, \"Named Destinations\") и (см. 7.7.4, \"Name Dictionary\")) в PDF‑документе на C++."
type: docs
weight: 11600
url: /ru/cpp/aspose.pdf/nameddestinationcollection/
---
## NamedDestinationCollection class


Класс представляет коллекцию всех назначений (дерево имён, сопоставляющее строковые имена с назначениями (см. 12.3.2.3, "Named Destinations") и (см. 7.7.4, "Name Dictionary")) в PDF‑документе.

```cpp
class NamedDestinationCollection : public Aspose::Pdf::INamedDestinationCollection
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Добавить новое именованное назначение. |
| [get_Count](./get_count/)() override | Количество именованных назначений. |
| [get_Names](./get_names/)() override | Список имён назначений. |
| [idx_get](./idx_get/)(System::String) override | Получает назначение по его имени. |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<Annotations::IAppointment\>) override | Устанавливает назначение по его имени. |
| [Remove](./remove/)(System::String) override | Удалить именованное назначение. |
## См. также

* Class [INamedDestinationCollection](../inameddestinationcollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
