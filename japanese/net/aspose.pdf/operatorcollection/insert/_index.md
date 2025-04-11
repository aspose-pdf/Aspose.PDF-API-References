---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection メソッド。オペレーターをコレクションに挿入します
type: docs
weight: 140
url: /ja/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

オペレーターをコレクションに挿入します。

```csharp
public override void Insert(int index, Operator op)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 新しいオペレーターを追加するインデックス |
| op | Operator | 挿入されるオペレーター |

## 例

例は、オペレーターをページコンテンツに挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### 関連項目

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

指定された位置にオペレーターを挿入します。

```csharp
public void Insert(int at, Operator[] ops)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| at | Int32 | オペレーターの挿入を開始するインデックス。 |
| ops | Operator[] | 挿入されるオペレーターの配列。各オペレーターは任意のインデックスを持つことができ（デフォルトは -1）、そのインデックスは *at* から自動的に調整されます。 |

## 例

例は、オペレーターをページコンテンツに挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 関連項目

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

指定された位置にオペレーターを挿入します。

```csharp
public void Insert(int at, IList<Operator> ops)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| at | Int32 | オペレーターの挿入を開始するインデックス。 |
| ops | IList`1 | 挿入されるオペレーターの配列。 |

## 例

例は、オペレーターをページコンテンツに挿入する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### 関連項目

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)