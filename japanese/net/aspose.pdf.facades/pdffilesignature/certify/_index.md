---
title: "PdfFileSignature.Certify"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSignature メソッド。MDP 署名でドキュメントを認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

MDP 署名でドキュメントを認証します。署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | 署名が作成されるページ。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |
| docMdpSignature | DocMDPSignature | 署名のドキュメント MDP タイプです。 |

### 関連項目

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

既に存在する署名フィールドに配置された MDP 署名でドキュメントを認証します。署名を行う前に署名フィールドは空である必要があります。つまり、フィールドに署名ディクショナリが含まれていてはいけません。そのため、pdf ドキュメントにはすでに署名フィールドがあり、署名をスタンプする場所、対応するページおよび矩形は、署名名（sigName パラメータを参照）で見つかる署名フィールドから取得されます。

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| sigName | String | 署名フィールドの名前です。 |
| docMdpSignature | DocMDPSignature | 署名のタイプは、[`PKCS1`](../../../aspose.pdf.forms/pkcs1/)、[`PKCS7`](../../../aspose.pdf.forms/pkcs7/) および [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) のいずれかです。 |

### 関連項目

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


