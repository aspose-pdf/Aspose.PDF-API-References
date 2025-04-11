---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection メソッド。コレクションからオペレーターを削除します
type: docs
weight: 110
url: /ja/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

コレクションからオペレーターを削除します。

```csharp
public void Delete(int index)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 削除するオペレーターのインデックス。オペレーターの番号付けは1から始まります。 |

## 例

例は、インデックスによってオペレーターを削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### 参照

* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

コレクションからオペレーターを削除します。

```csharp
public void Delete(Operator[] ops)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ops | Operator[] | 削除するオペレーターの配列 |

## 例

例は、ページの内容からオペレーターを削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### 参照

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

コレクションからオペレーターを削除します。

```csharp
public void Delete(IList<Operator> list)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| list | IList`1 | 削除するオペレーターのリスト |

## 例

例は、ページの内容からオペレーターを削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### 参照

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)