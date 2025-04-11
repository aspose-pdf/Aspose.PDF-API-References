---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Belge hash'ini özel olarak imzalamak için delegate
type: docs
weight: 5260
url: /tr/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Belge hash'ini özel olarak imzalamak için delegate.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hash | Byte[] | Belgenin girdi hash'i. |
| digestHashAlgorithm | DigestHashAlgorithm | Hash'i oluşturmak için kullanılan özet algoritması. Değer asla Auto'ya eşit olmayacaktır. |

### Dönüş Değeri

Çıktı imzası.

## Açıklamalar

Dijital imzanın ayrılmış olup olmadığına bakılmaksızın, hash argümanı her zaman imzalanacak son hash olacaktır.

### Ayrıca Bakınız

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)