---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType sınıfı. PDF/A ValueType şeması, XMP 2004 spesifikasyonunda tanımlanmayan tüm özellik değer türleri için gereklidir, yani aşağıdaki listedeki değer türleri dışında kalan değer türleri için: - Dizi türleri: Alt, Bag, Seq - Temel değer türleri: Boolean, açık ve kapalı Seçim, Tarih, Boyutlar, Tam sayı, Lang Alt, Yerel, MIMEType, ProperName, Gerçek, Metin, Küçük resim, URI, URL, XPath - Medya Yönetimi değer türleri: AgentName, RenditionClass, ResourceEvent, ResourceRef, Versiyon - Temel İş/İş Akışı değer türü: İş - EXIF şeması değer türleri: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rasyonel Şema ad alanı URI: http://www.aiim.org/pdfa/ns/type# Gerekli şema ad alanı öneki: pdfaType
type: docs
weight: 11490
url: /tr/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType sınıfı

PDF/A ValueType şeması, XMP 2004 spesifikasyonunda tanımlanmayan tüm özellik değer türleri için gereklidir, yani aşağıdaki listedeki değer türleri dışında kalan değer türleri için: - Dizi türleri (bunlar bir veya daha fazla alan içerebilen konteyner türleridir): Alt, Bag, Seq - Temel değer türleri: Boolean, (açık ve kapalı) Seçim, Tarih, Boyutlar, Tam sayı, Lang Alt, Yerel, MIMEType, ProperName, Gerçek, Metin, Küçük resim, URI, URL, XPath - Medya Yönetimi değer türleri: AgentName, RenditionClass, ResourceEvent, ResourceRef, Versiyon - Temel İş/İş Akışı değer türü: İş - EXIF şeması değer türleri: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rasyonel Şema ad alanı URI: http://www.aiim.org/pdfa/ns/type# Gerekli şema ad alanı öneki: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Yeni nesneyi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Açıklama](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Açıklamayı alır. |
| [Alanlar](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Alanların listesini alır. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Ad alanı URI'sini alır. |
| [Önek](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Öneki alır. |
| [Tür](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Değer türünü alır. |
| [Değer](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Değeri alır veya ayarlar. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| [Ekle](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Yeni alan ekler. |
| [EkleAralık](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Alan aralığını ekler. |
| [Temizle](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Tüm alanları temizler. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | XML ağacında değer türünü temsil eden XML öğelerinin listesini döndürür. |
| [Kaldır](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Alanı alanlar listesinden kaldırır. |

### Ayrıca Bakınız

* sınıf [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)