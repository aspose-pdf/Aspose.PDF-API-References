---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Метод OperatorCollection. Вставляет оператор в коллекцию
type: docs
weight: 140
url: /ru/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Вставляет оператор в коллекцию.

```csharp
public override void Insert(int index, Operator op)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс, по которому должен быть добавлен новый оператор |
| op | Operator | Оператор, который будет вставлен |

## Примеры

Пример демонстрирует, как вставить оператор в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Вставить операторы в заданной позиции.

```csharp
public void Insert(int at, Operator[] ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | Int32 | Индекс, с которого начинаются вставка операторов. |
| ops | Operator[] | Массив операторов, которые будут вставлены. Каждый оператор может иметь любой индекс (по умолчанию -1), так как их индексы автоматически настраиваются, начиная с *at*. |

## Примеры

Пример демонстрирует, как вставить оператор в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Вставить операторы в заданной позиции.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | Int32 | Индекс, с которого начинаются вставка операторов. |
| ops | IList`1 | Массив операторов, которые будут вставлены. |

## Примеры

Пример демонстрирует, как вставить операторы в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)