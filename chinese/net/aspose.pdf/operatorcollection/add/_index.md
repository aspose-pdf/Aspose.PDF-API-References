---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 方法。将新操作符添加到集合中
type: docs
weight: 60
url: /zh/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

将新操作符添加到集合中。

```csharp
public override void Add(Operator op)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| op | Operator | 必须添加的操作符 |

## 示例

示例演示如何将操作符添加到 page.contents 的末尾。

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

在内容操作符的末尾添加操作符。

```csharp
public void Add(Operator[] ops)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ops | Operator[] | 要添加的操作符数组。每个操作符可以具有任何索引（默认值为 -1），因为它们会被添加到内容操作符的末尾，即索引会自动分配。 |

## 示例

示例演示如何将操作符添加到页面内容的末尾。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

将其他集合中的所有操作符添加到集合中。

```csharp
public void Add(ICollection<Operator> ops)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ops | ICollection`1 | 包含将要添加的操作符的集合。 |

## 示例

示例演示如何将操作符集合添加到页面内容中。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)