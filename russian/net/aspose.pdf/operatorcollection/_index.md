---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.OperatorCollection. Класс представляет собой коллекцию операторов
type: docs
weight: 7080
url: /ru/net/aspose.pdf/operatorcollection/
---
## Класс OperatorCollection

Класс представляет собой коллекцию операторов

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Получает количество операторов в коллекции. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Указывает, ограничена ли коллекция быстрым извлечением текста |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Получает оператор по его индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Принимает объект посетителя IOperatorSelector для обработки операторов. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Добавляет в коллекцию всех операторов из другой коллекции. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Добавляет новый оператор в коллекцию. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Добавляет операторы в конец операторов содержимого. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Удаляет всех операторов из списка. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Возвращает true, если коллекция содержит данный оператор. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Копирует операторов в список операторов. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Удаляет операторов из коллекции. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Удаляет оператора из коллекции. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Удаляет операторов из коллекции. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Выполняет определенные приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Возвращает перечислитель для коллекции |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Вставляет операторов в заданной позиции. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Вставляет оператор в коллекцию. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Вставляет операторов в заданной позиции. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Удаляет оператора из коллекции. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Заменяет операторов в коллекции другими операторами. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Возобновляет обновление документа. Обновляет поток содержимого в случае наличия ожидающих изменений. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Возобновляет обновление документа. Обновляет поток содержимого в случае наличия ожидающих изменений. Помечает всех операторов как "измененные", если параметр invalidate равен true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызван ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Возвращает текстовое представление оператора. |

### См. также

* класс [BaseOperatorCollection](../baseoperatorcollection/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)