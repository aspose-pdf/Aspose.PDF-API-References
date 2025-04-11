---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber メソッド。指定されたページのテキストを抽出します
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

指定されたページのテキストを抽出します

```csharp
public virtual void Visit(Page page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Page | Pdf ドキュメントページオブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページのテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

指定された XForm のテキストを抽出します。

```csharp
public virtual void Visit(XForm form)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| form | XForm | Pdf フォームオブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページのテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### 参照

* クラス [XForm](../../../aspose.pdf/xform/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定されたドキュメントのテキストを抽出します

```csharp
public virtual void Visit(Document pdf)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdf | Document | Pdf ドキュメントオブジェクト。 |

## 例

この例では、PDF ドキュメントのテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)