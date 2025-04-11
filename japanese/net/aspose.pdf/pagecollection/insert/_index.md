---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: PageCollection メソッド。指定された位置にコレクションに空のページを挿入します。ドキュメントにすでに異なるサイズのページが含まれている場合、最も頻繁に発生するページのサイズが選択されます。異なるページが2つだけの場合は、最初のページのサイズが使用されます。
type: docs
weight: 160
url: /ja/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

指定された位置にコレクションに空のページを挿入します。ドキュメントにすでに異なるサイズのページが含まれている場合、最も頻繁に発生するページのサイズが選択されます。異なるページが2つだけの場合は、最初のページのサイズが使用されます。

```csharp
public Page Insert(int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しいページの位置。 |

### 戻り値

挿入されたページ。

### 参照

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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | コレクション内の必要なページインデックス。 |
| entity | Page | 挿入されるページ。 |

### 戻り値

挿入されたページ。

### 参照

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

コレクションからドキュメントにページを挿入します。

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しいページの開始位置。 |
| pages | ICollection`1 | ページコレクション。 |

### 参照

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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 新しいページの開始番号。 |
| pages | Page[] | 挿入されるページの配列。 |

### 参照

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)