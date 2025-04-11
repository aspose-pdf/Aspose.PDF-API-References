---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature メソッド。MDP 署名で文書を認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティによって提供される必要があります。
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

MDP 署名で文書を認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティによって提供される必要があります。

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 署名が行われるページ。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |
| docMdpSignature | DocMDPSignature | 署名の文書 MDP タイプ。 |

### 参照

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

既に提示された署名フィールドに配置された MDP 署名で文書を認証します。署名する前に署名フィールドは空でなければなりません。つまり、フィールドには署名辞書が含まれていてはいけません。したがって、PDF 文書には既に署名フィールドがあり、署名を押す場所、対応するページ、矩形を提供する必要はありません。これらは署名名によって見つけられた署名フィールドから取得されます（sigName パラメータを参照）。

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sigName | String | 署名フィールドの名前。 |
| docMdpSignature | DocMDPSignature | 署名のタイプで、[`PKCS1`](../../../aspose.pdf.forms/pkcs1/)、[`PKCS7`](../../../aspose.pdf.forms/pkcs7/) および [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) である可能性があります。 |

### 参照

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)