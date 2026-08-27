---
title: "OperatorCollection.Delete"
second_title: "Aspose.PDF for .NET API 参考"
description: "OperatorCollection 方法。删除集合中的运算符"
type: docs
weight: 110
url: /zh/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

从集合中删除单个运算符。

```csharp
public void Delete(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 必须删除的运算符的索引。运算符编号从 1 开始。 |

## 示例

示例演示如何通过索引删除运算符。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### 另请参见

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

从集合中删除运算符。

```csharp
public void Delete(Operator[] ops)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ops | Operator[] | 要删除的运算符数组 |

## 示例

示例演示如何从页面内容中移除运算符。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### 另请参见

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

从集合中删除运算符。

```csharp
public void Delete(IList<Operator> list)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 列表 | IList`1 | 要删除的运算符列表 |

## 示例

示例演示如何从页面内容中移除运算符。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### 另请参见

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


