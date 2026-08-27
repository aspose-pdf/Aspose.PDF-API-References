---
title: "OperatorCollection.Delete"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OperatorCollection. Удаляет оператор из коллекции"
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
| index | Int32 | Индекс оператора, который необходимо удалить. Нумерация операторов начинается с 1. |

## Примеры

Пример демонстрирует, как удалить оператор по его индексу.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### См. также

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Удаляет операторы из коллекции.

```csharp
public void Delete(IList<Operator> list)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| список | IList`1 | Список операторов для удаления |

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

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


