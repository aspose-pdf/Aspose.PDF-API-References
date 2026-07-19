---
title: "Aspose::Pdf::Forms::XFA класс"
linktitle: "XFA"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::XFA класс. Представляет XML-форму, относящуюся к архитектуре XML Forms (XFA) в C++."
type: docs
weight: 3000
url: /ru/cpp/aspose.pdf.forms/xfa/
---
## XFA class


Представляет XML-форму, относящуюся к архитектуре XML [Forms](../) ([XFA](./)).

```cpp
class XFA : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Config](./get_config/)() | [XFA](./) компонент Config формы [XFA](./). |
| [get_Datasets](./get_datasets/)() | [XFA](./) компонент Datasets формы [XFA](./). |
| [get_FieldNames](./get_fieldnames/)() | Список имен полей в шаблоне формы. |
| [get_Form](./get_form/)() | [XFA](./)[Form](../form/) компонент формы [XFA](./). |
| [get_NamespaceManager](./get_namespacemanager/)() | Получает пространство имён для формы [XFA](./). Определены следующие пространства имён: "data" для данных формы и "tpl" для шаблона формы. |
| [get_Template](./get_template/)() | [XFA](./) компонент Template формы [XFA](./). |
| [get_XDP](./get_xdp/)() | Пакет данных XML (все компоненты формы [XFA](./) внутри окружающего XML‑контейнера). |
| [GetFieldTemplate](./getfieldtemplate/)(const System::String\&) | Возвращает XML‑узел шаблона поля [XFA](./). |
| [GetFieldTemplates](./getfieldtemplates/)() | Возвращает список всех шаблонов полей в форме [XFA](./). |
| [idx_get](./idx_get/)(const System::String\&) | Получает или задаёт значение узла данных согласно *path*. |
| [idx_set](./idx_set/)(const System::String\&, const System::String\&) | Получает или задаёт значение узла данных согласно *path*. |
| [SetFieldImage](./setfieldimage/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает изображение для поля [XFA](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
