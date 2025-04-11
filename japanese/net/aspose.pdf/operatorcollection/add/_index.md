---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection メソッド。コレクションに新しいオペレーターを追加します
type: docs
weight: 60
url: /ja/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

コレクションに新しいオペレーターを追加します。

```csharp
public override void Add(Operator op)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| op | Operator | 追加するオペレーター |

## 例

例は、オペレーターを page.contents の最後に追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### 参照

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

コンテンツオペレーターの最後にオペレーターを追加します。

```csharp
public void Add(Operator[] ops)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ops | Operator[] | 追加されるオペレーターの配列。各オペレーターは任意のインデックスを持つことができ（デフォルトは -1）、コンテンツオペレーターの最後に来るため、インデックスは自動的に割り当てられます。 |

## 例

例は、オペレーターをページコンテンツの最後に追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 参照

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

他のコレクションからすべてのオペレーターをコレクションに追加します。

```csharp
public void Add(ICollection<Operator> ops)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ops | ICollection`1 | 追加されるオペレーターを含むコレクション。 |

## 例

例は、オペレーターコレクションをページコンテンツに追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### 参照

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)