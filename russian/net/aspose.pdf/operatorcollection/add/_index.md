---
title: "OperatorCollection.Add"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OperatorCollection. Добавляет новый оператор в коллекцию."
type: docs
weight: 60
url: /ru/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Добавляет новый оператор в коллекцию.

```csharp
public override void Add(Operator op)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | Operator | Оператор, который должен быть добавлен. |

## Примеры

Пример демонстрирует, как добавить операторы в конец page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### См. также

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Добавляет операторы в конец операторов содержимого.

```csharp
public void Add(Operator[] ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | Operator[] | Массив операторов для добавления. Каждый оператор может иметь любой индекс (по умолчанию -1), поскольку они помещаются в конец операторов содержимого, т.е. индексы назначаются автоматически. |

## Примеры

Пример демонстрирует, как добавить оператор в конец содержимого страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### См. также

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Добавляет в коллекцию все операторы из другой коллекции.

```csharp
public void Add(ICollection<Operator> ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | ICollection`1 | коллекция, которая содержит операторы, которые будут добавлены. |

## Примеры

Пример демонстрирует, как добавить коллекцию операторов в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### См. также

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


