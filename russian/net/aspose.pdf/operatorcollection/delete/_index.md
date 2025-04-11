---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Метод OperatorCollection. Удаляет оператор из коллекции
type: docs
weight: 110
url: /ru/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Удаляет оператор из коллекции.

```csharp
public void Delete(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс оператора, который должен быть удалён. Нумерация операторов начинается с 1. |

## Примеры

Пример демонстрирует, как удалить оператор по его индексу.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### См. также

* класс [OperatorCollection](../)
* пространство имён [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Удаляет операторы из коллекции.

```csharp
public void Delete(Operator[] ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | Operator[] | Массив операторов для удаления |

## Примеры

Пример демонстрирует, как удалить оператор из содержимого страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имён [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Delete(IList<Operator>) {#delete_2}

Удаляет операторы из коллекции.

```csharp
public void Delete(IList<Operator> list)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| list | IList`1 | Список операторов для удаления |

## Примеры

Пример демонстрирует, как удалить оператор из содержимого страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имён [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)