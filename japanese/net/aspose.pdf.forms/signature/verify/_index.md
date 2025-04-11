---
title: Signature.Verify
second_title: Aspose.PDF for .NET API Reference
description: 署名メソッド。 この署名に関する文書を検証し、文書が有効であれば true を返し、そうでなければ false を返します。
type: docs
weight: 170
url: /ja/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

この署名に関する文書を検証し、文書が有効であれば true を返し、そうでなければ false を返します。

```csharp
public bool Verify()
```

### Return Value

文書が有効であれば true。

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

この署名に関する文書を検証し、文書が有効であれば true を返し、そうでなければ false を返します。

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### Return Value

文書が有効であれば true。

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)