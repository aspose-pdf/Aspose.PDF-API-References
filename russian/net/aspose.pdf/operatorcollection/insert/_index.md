---
title: Insert
second_title: Aspose.PDF для справочника API .NET
description: Вставляет оператор в коллекцию.
type: docs
weight: 130
url: /ru/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Вставляет оператор в коллекцию.

```csharp
public override void Insert(int index, Operator op)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс, в который необходимо добавить новый оператор |
| op | Operator | Оператор, который будет вставлен |

### Примеры

Пример демонстрирует, как вставить оператор в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Смотрите также

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* пространство имен [Aspose.Pdf](../../operatorcollection)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Вставить операторы в указанную позицию.

```csharp
public void Insert(int at, Operator[] ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | Int32 | Индекс, с которого начинается вставка операторов. |
| ops | Operator[] | Массив операторов для вставки. Каждый оператор может иметь любой индекс (по умолчанию -1), так как их индексы настраиваются автоматически, начиная с*at*. |

### Примеры

Пример демонстрирует, как вставить оператор в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Смотрите также

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* пространство имен [Aspose.Pdf](../../operatorcollection)
* сборка [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Вставить операторы в указанную позицию.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | Int32 | Индекс, с которого начинается вставка операторов. |
| ops | IList`1 | Массив операторов для вставки. |

### Примеры

Пример демонстрирует, как вставлять операторы в содержимое страницы.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Смотрите также

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* пространство имен [Aspose.Pdf](../../operatorcollection)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->