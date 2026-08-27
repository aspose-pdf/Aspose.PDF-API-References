---
title: "PageCollection.Insert"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PageCollection メソッド。指定された位置に empty Page を PageCollection に挿入します。Document にサイズが異なる Page がすでに含まれている場合、最も頻繁に出現する Page のサイズが選択されます。異なる Page が 2 種類しかない場合は、最初の Page のサイズが使用されます。"
type: docs
weight: 160
url: /ja/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

指定された位置に空のページをコレクションに挿入します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。異なるページが2つだけの場合は、最初のページのサイズが使用されます。

```csharp
public Page Insert(int pageNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しい Page の位置。 |

### 戻り値

挿入された Page。

### 関連項目

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

指定された場所にページをページコレクションに挿入します。

```csharp
public Page Insert(int pageNumber, Page entity)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | PageCollection 内の必要な Page インデックス。 |
| エンティティ | ページ | 挿入される Page。 |

### 戻り値

挿入された Page。

### 関連項目

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

コレクションからページをドキュメントに挿入します。

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しいページの開始位置です。 |
| pages | ICollection`1 | ページコレクション。 |

### 関連項目

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

配列のページをドキュメントに挿入します。

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しいページの開始番号です。 |
| pages | Page[] | 挿入されるページの配列です。 |

### 関連項目

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


