---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextAbsorber メソッド。指定されたページのテキストを抽出します"
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

指定されたページからテキストを抽出します。

```csharp
public virtual void Visit(Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | Pdf ドキュメント ページ オブジェクト。 |

## 例

この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// すべての document のページに対してアブソーバーを受け入れます
absorber.Visit(doc.Pages[1]);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;
```

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

指定された XForm からテキストを抽出します。

```csharp
public virtual void Visit(XForm form)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| フォーム | XForm | Pdf フォーム オブジェクト。 |

## 例

この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// すべての document のページに対してアブソーバーを受け入れます
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;
```

### 関連項目

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定されたドキュメントからテキストを抽出します。

```csharp
public virtual void Visit(Document pdf)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pdf | Document | Pdf ドキュメント オブジェクト。 |

## 例

この例は PDF ドキュメントからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// すべての document のページに対してアブソーバーを受け入れます
absorber.Visit(doc);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;
```

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


