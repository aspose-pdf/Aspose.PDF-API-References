---
title: "Класс OperatorCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.OperatorCollection. Класс представляет коллекцию операторов."
type: docs
weight: 7220
url: /ru/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

Класс представляет коллекцию операторов.

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Возвращает количество операторов в коллекции. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Указывает, ограничена ли коллекция быстрым извлечением текста. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Возвращает оператор по его индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Принимает объект‑посетитель IOperatorSelector для обработки операторов. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Добавляет в коллекцию все операторы из другой коллекции. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Добавляет новый оператор в коллекцию. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Добавляет операторы в конец операторов содержимого. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Отменяет последнее обновление. Этот метод может вызываться, когда изменение не должно вызывать обновление содержимого. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Удаляет все операторы из списка. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Возвращает true, если коллекция содержит указанный оператор. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Копирует операторы в список операторов. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Удаляет операторы из коллекции. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Удаляет оператор из коллекции. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Удаляет операторы из коллекции. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Возвращает перечислитель для коллекции |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Вставить операторы в указанную позицию. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Вставляет оператор в коллекцию. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Вставить операторы в указанную позицию. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Удаляет оператор из коллекции. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Заменяет операторы в коллекции другими операторами. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Возобновляет обновление документа. Обновляет поток содержимого, если есть ожидающие изменения. Помечает все операторы как "changed", если параметр invalidate равен true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Подавляет обновление данных содержимого. Поток содержимого не обновляется, пока не будет вызван ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Возвращает текстовое представление оператора. |

### См. также

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


