---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Lisans yöntemi. Bileşeni lisanslar
type: docs
weight: 20
url: /tr/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | String | Tam veya kısa bir dosya adı veya gömülü bir kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

## Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesinde gömülü bir kaynak.

**Not:** .NET Compact Framework'te, lisansı yalnızca bu konumlarda bulmaya çalışır:

1. Açık yol.

2. İstemcinin çağıran derlemesinde gömülü bir kaynak.

[Java]

2. Aspose bileşen JAR dosyasını içeren klasör.

3. İstemcinin çağıran JAR dosyasını içeren klasör.

### Ayrıca Bakınız

* sınıf [License](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Lisansı içeren bir akış. |

## Açıklamalar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.

### Ayrıca Bakınız

* sınıf [License](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)