---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.BaseOperatorCollection. Представляет базовый класс для коллекции операторов
type: docs
weight: 2830
url: /ru/net/aspose.pdf/baseoperatorcollection/
---
## Класс BaseOperatorCollection

Представляет базовый класс для коллекции операторов.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Получает количество операторов в коллекции. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Указывает, ограничена ли коллекция быстрым извлечением текста |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Возвращает true, если коллекция доступна только для чтения. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Получает оператор по его индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Добавляет новый оператор в коллекцию. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Очищает коллекцию. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Проверяет, существует ли оператор в коллекции. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Копирует операторов в список операторов. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Возвращает перечислитель для коллекции |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Вставляет оператора в коллекцию. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Удаляет оператора из коллекции. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Возобновляет обновление документа. Обновляет поток содержимого в случае наличия ожидающих изменений. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызван ResumeUpdate. |

### См. также

* класс [Operator](../operator/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)