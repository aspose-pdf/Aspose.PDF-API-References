---
title: "OperatorCollection.Add"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OperatorCollection メソッド。新しいオペレーターをコレクションに追加します"
type: docs
weight: 60
url: /ja/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

新しいオペレーターをコレクションに追加します。

```csharp
public override void Add(Operator op)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| op | オペレーター | 追加する必要があるオペレーター |

## 例

例では、page.contents の末尾にオペレーターを追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

コンテンツオペレーターの末尾にオペレーターを追加します。

```csharp
public void Add(Operator[] ops)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ops | Operator[] | 追加されるオペレーターの配列。各オペレーターは任意のインデックス（デフォルトは -1）を持つことができ、コンテンツのオペレーターの末尾に配置されるため、インデックスは自動的に割り当てられます。 |

## 例

例では、ページコンテンツの末尾にオペレーターを追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ops | ICollection`1 | 追加されるオペレーターを含むコレクション。 |

## 例

例では、オペレーターコレクションをページコンテンツに追加する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


