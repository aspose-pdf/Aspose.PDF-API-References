---
title: "Form.Form"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form コンストラクタ。パラメータなしの Form のコンストラクタです。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

パラメータなしの Form のコンストラクタです。

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Form のコンストラクタです。

```csharp
public Form(string srcFileName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | ソースファイルのパスです。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

フォームのコンストラクタです。

```csharp
public Form(Stream srcStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcStream | Stream | ソースストリームです。 |

## 例

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

*document* を基に新しい [`Form`](../) オブジェクトを初期化します。

```csharp
public Form(Document document)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | Pdf ドキュメント。 |

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


