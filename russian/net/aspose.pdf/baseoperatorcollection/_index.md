---
title: "Класс BaseOperatorCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.BaseOperatorCollection class. Представляет базовый класс для коллекции операторов."
type: docs
weight: 2940
url: /ru/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

Представляет базовый класс для коллекции операторов.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Возвращает количество операторов в коллекции. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Указывает, ограничена ли коллекция быстрым извлечением текста. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Возвращает true, если коллекция только для чтения. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Возвращает оператор по его индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Добавляет новый оператор в коллекцию. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Отменяет последнее обновление. Этот метод может вызываться, когда изменение не должно вызывать обновление содержимого. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Очищает коллекцию. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Проверяет, существует ли оператор в коллекции. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Копирует операторы в список операторов. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Возвращает перечислитель для коллекции |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Вставляет оператор в коллекцию. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Удаляет оператор из коллекции. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызван ResumeUpdate. |

### См. также

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


