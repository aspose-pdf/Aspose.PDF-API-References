---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSignature メソッド。署名から単一の X.509 証明書を抽出します。"
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

署名の単一 X.509 証明書を抽出します。

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| 証明書 | X509Certificate2& | 証明書が見つかった場合は単一の X.509 証明書オブジェクトを返します。見つからない場合は null を返します。 |

### 戻り値

証明書が見つかりました。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

署名の単一 X.509 証明書をストリームとして抽出します。

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| stream | Stream& | 証明書が見つかった場合は単一の X.509 証明書ストリームを返します。見つからない場合は null を返します。 |

### 戻り値

証明書が見つかりました。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


