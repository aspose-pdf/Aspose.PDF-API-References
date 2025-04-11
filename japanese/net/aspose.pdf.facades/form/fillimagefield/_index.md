---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、その外観を設定します。
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

完全修飾フィールド名に従って、既存のボタンフィールドに画像を貼り付け、その外観を設定します。

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 画像ボタンフィールドの完全修飾フィールド名。 |
| imageFileName | String | 画像ファイルのパス、相対パスと絶対パスの両方が使用可能です。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

FillImageFieldのオーバーロード関数。入力は画像ストリームです。

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |
| imageStream | Stream | 画像のストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)