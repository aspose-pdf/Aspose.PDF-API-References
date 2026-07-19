---
title: "Класс Aspose::Pdf::OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::OutlineItemCollection. Представляет элемент оглавления в иерархии оглавления PDF‑документа в C++."
type: docs
weight: 12600
url: /ru/cpp/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class


Представляет запись оглавления в иерархии оглавления PDF‑документа.

```cpp
class OutlineItemCollection : public Aspose::Pdf::Outlines
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Добавляет элемент оглавления в коллекцию. |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Проверяет, содержит ли коллекция заданный элемент. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Копирует элементы оглавления в [System.Array](../../system/array/), начиная с определённого индекса [System.Array](../../system/array/). |
| [Delete](./delete/)() | Удаляет этот элемент оглавления из иерархии оглавления документа. |
| [Delete](./delete/)(const System::String\&) | Удаляет запись оглавления с указанным именем из иерархии оглавления документа. |
| [get_Action](./get_action/)() | Получает действие для этого элемента оглавления. |
| [get_Bold](./get_bold/)() | Получает флаг полужирного начертания для текста заголовка этого элемента оглавления. |
| [get_Color](./get_color/)() | Получает цвет текста заголовка этого элемента оглавления. |
| [get_Count](./get_count/)() const override | Количество элементов в коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount возвращает число видимых элементов оглавления на всех уровнях. |
| [get_Destination](./get_destination/)() | Получает назначение для этого элемента оглавления. |
| [get_First](./get_first/)() const | Получает элемент оглавления, представляющий первый элемент верхнего уровня в иерархии оглавления. |
| [get_HasNext](./get_hasnext/)() | Проверьте, представляет ли элемент оглавления следующий элемент относительно этого элемента в иерархии оглавления. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасен). |
| [get_Italic](./get_italic/)() | Получает флаг курсивного начертания для текста заголовка этого элемента оглавления. |
| [get_Last](./get_last/)() | Получает элемент оглавления, представляющий последний элемент верхнего уровня в иерархии оглавления. |
| [get_Level](./get_level/)() | Получает уровень иерархии элемента оглавления. |
| [get_Next](./get_next/)() | Получает элемент оглавления, представляющий следующий элемент относительно этого элемента в иерархии оглавления. |
| [get_Open](./get_open/)() | Получает или задает статус открытости (true/false) для элемента оглавления. |
| [get_Parent](./get_parent/)() | Получает родительский объект этого элемента оглавления в иерархии оглавления. |
| [get_Prev](./get_prev/)() | Получает элемент оглавления, представляющий предыдущий элемент относительно этого элемента в иерархии оглавления. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [get_Title](./get_title/)() | Получает заголовок этого элемента оглавления. |
| [get_VisibleCount](./get_visiblecount/)() override | Получает общее количество элементов оглавления на всех уровнях в иерархии оглавления документа. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который проходит по коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент оглавления из коллекции по индексу. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<OutlineItemCollection\>\&) | Вставляет элемент оглавления в коллекцию в указанное место. |
| [OutlineItemCollection](./outlineitemcollection/)(const System::SharedPtr\<OutlineCollection\>\&) | Инициализирует экземпляр элемента оглавления, используя объект корневой иерархии. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Удаляет элемент коллекции оглавления. |
| [Remove](./remove/)(int32_t) | Удалить элемент по индексу. |
| [set_Action](./set_action/)(const System::SharedPtr\<Annotations::PdfAction\>\&) | Задает действие для этого элемента оглавления. |
| [set_Bold](./set_bold/)(bool) | Задает флаг полужирного начертания для текста заголовка этого элемента оглавления. |
| [set_Color](./set_color/)(System::Drawing::Color) | Задает цвет текста заголовка этого элемента оглавления. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Устанавливает назначение для этого элемента оглавления. |
| [set_Italic](./set_italic/)(bool) | Устанавливает флаг курсивного начертания для текста заголовка этого элемента оглавления. |
| [set_Open](./set_open/)(bool) | Получает или задает статус открытости (true/false) для элемента оглавления. |
| [set_Title](./set_title/)(const System::String\&) | Устанавливает заголовок для этого элемента оглавления. |
## См. также

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
