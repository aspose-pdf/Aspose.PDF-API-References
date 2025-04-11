---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: スタンプメソッド。画像をスタンプとして設定します
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

画像をスタンプとして設定します。

```csharp
public void BindImage(string imageFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイル名とパス。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 参照

* クラス [Stamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

スタンプとして使用される画像を設定します。

```csharp
public void BindImage(Stream image)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Stream | 画像データを含むストリーム。 |

### 参照

* クラス [Stamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)