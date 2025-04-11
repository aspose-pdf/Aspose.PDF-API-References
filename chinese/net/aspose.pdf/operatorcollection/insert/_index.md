---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 方法。将操作符插入集合
type: docs
weight: 140
url: /zh/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

将操作符插入集合中。

```csharp
public override void Insert(int index, Operator op)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 新操作符必须添加的索引 |
| op | Operator | 将被插入的操作符 |

## 示例

示例演示如何将操作符插入页面内容中。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

在给定位置插入操作符。

```csharp
public void Insert(int at, Operator[] ops)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| at | Int32 | 开始插入操作符的索引。 |
| ops | Operator[] | 要插入的操作符数组。每个操作符可以具有任何索引（默认值为 -1），因为它们的索引从 *at* 开始自动调整。 |

## 示例

示例演示如何将操作符插入页面内容中。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

在给定位置插入操作符。

```csharp
public void Insert(int at, IList<Operator> ops)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| at | Int32 | 开始插入操作符的索引。 |
| ops | IList`1 | 要插入的操作符数组。 |

## 示例

示例演示如何将操作符插入页面内容中。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)