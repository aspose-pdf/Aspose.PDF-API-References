---
title: "OperatorCollection.Delete"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OperatorCollection メソッド。コレクションから演算子を削除します。"
type: docs
weight: 110
url: /ja/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

コレクションからオペレーターを削除します。

```csharp
public void Delete(int index)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| インデックス | Int32 | 削除する演算子のインデックス。演算子の番号は 1 から始まります。 |

## 例

例ではインデックスで演算子を削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### 関連項目

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

コレクションからオペレーターを削除します。

```csharp
public void Delete(Operator[] ops)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ops | Operator[] | 削除する演算子の配列 |

## 例

例ではページコンテンツから演算子を削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

コレクションからオペレーターを削除します。

```csharp
public void Delete(IList<Operator> list)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| リスト | IList`1 | 削除する演算子のリスト |

## 例

例ではページコンテンツから演算子を削除する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


