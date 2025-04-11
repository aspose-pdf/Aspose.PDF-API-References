---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize enum. PDF belgelerini şifrelemek için kullanılabilecek farklı anahtar boyutlarını tanımlar
type: docs
weight: 4390
url: /tr/net/aspose.pdf.facades/keysize/
---
## KeySize enumerasyonu

PDF belgelerini şifrelemek için kullanılabilecek farklı anahtar boyutlarını tanımlar.

```csharp
public enum KeySize
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| x40 | `0` | 40 bit anahtar. Bu anahtar boyutu RC4 algoritması ile kullanılır ve düşük seviyede güvenlik sağlar. Bununla birlikte, eski PDF belgeleri yalnızca bu tür anahtarlarla şifrelenebilir (v. 1.3 ve daha düşük); |
| x128 | `1` | 128 bit anahtar. Hem RC4 hem de AES algoritmaları bu anahtar boyutunu kullanabilir. |
| x256 | `2` | 256 bit anahtar. Bu anahtar boyutu yalnızca AES ile kullanılabilir ve en son Adobe Reader sürümleriyle tanınır (v.9'dan itibaren). |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)