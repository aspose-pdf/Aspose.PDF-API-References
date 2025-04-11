---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: パラメータなしの Form コンストラクタ
type: docs
weight: 10
url: /ja/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

パラメータなしの Form コンストラクタです。

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Form のコンストラクタです。

```csharp
public Form(string srcFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | ソースファイルのパス。 |

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

フォームのコンストラクタです。

```csharp
public Form(Stream srcStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | ソースストリーム。 |

## Examples

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

*document* に基づいて新しい [`Form`](../) オブジェクトを初期化します。

```csharp
public Form(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Pdf ドキュメント。 |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)