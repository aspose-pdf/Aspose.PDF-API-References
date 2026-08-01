---
title: "OperatorCollection.Insert"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OperatorCollection メソッド。演算子をコレクションに挿入します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

演算子をコレクションに挿入します。

```csharp
public override void Insert(int index, Operator op)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| インデックス | Int32 | 新しいオペレーターを追加する必要があるインデックス |
| op | オペレーター | 挿入されるオペレーター |

## 例

例では、ページコンテンツにオペレーターを挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

指定された位置に演算子を挿入します。

```csharp
public void Insert(int at, Operator[] ops)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| at | Int32 | オペレーターの挿入を開始するインデックス |
| ops | Operator[] | 挿入されるオペレーターの配列。各オペレーターは任意のインデックス（デフォルトは -1）を持つことができ、インデックスは *at* から自動的に調整されます。 |

## 例

例では、ページコンテンツにオペレーターを挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

指定された位置に演算子を挿入します。

```csharp
public void Insert(int at, IList<Operator> ops)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| at | Int32 | オペレーターの挿入を開始するインデックス |
| ops | IList`1 | 挿入されるオペレーターの配列。 |

## 例

例では、ページコンテンツにオペレーターを挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


