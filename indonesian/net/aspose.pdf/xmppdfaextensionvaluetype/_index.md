---
title: "Kelas XmpPdfAExtensionValueType"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.XmpPdfAExtensionValueType class. Skema PDF/A ValueType diperlukan untuk semua tipe nilai properti yang tidak didefinisikan dalam spesifikasi XMP 2004, yaitu untuk tipe nilai di luar daftar berikut: Tipe array, yaitu tipe kontainer yang dapat berisi satu atau lebih bidang Alt Bag Seq  Tipe nilai dasar Boolean terbuka dan tertutup Choice Date Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath  Tipe nilai Manajemen Media AgentName RenditionClass ResourceEvent ResourceRef Version  Tipe nilai Dasar Job/Workflow Job  Tipe nilai skema EXIF Flash CFAPattern DeviceSettings GPSCoordinate OECF/SFR Rational Schema namespace URI http//www.aiim.org/pdfa/ns/type Prefiks namespace skema yang diperlukan pdfaType"
type: docs
weight: 11680
url: /id/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

Skema PDF/A ValueType diperlukan untuk semua tipe nilai properti yang tidak didefinisikan dalam spesifikasi XMP 2004, yaitu untuk tipe nilai di luar daftar berikut: - Tipe array (ini adalah tipe kontainer yang dapat berisi satu atau lebih bidang): Alt, Bag, Seq - Tipe nilai dasar: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipe nilai Manajemen Media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipe nilai Job/Workflow Dasar: Job - Tipe nilai skema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace URI skema: http://www.aiim.org/pdfa/ns/type# Prefiks namespace skema yang diperlukan: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Menginisialisasi objek baru. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Mendapatkan deskripsi. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Mendapatkan daftar bidang. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Mendapatkan URI namespace. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Mendapatkan prefiks. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Mendapatkan tipe nilai. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Mendapatkan atau mengatur nilai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Tambahkan bidang baru. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Menambahkan rentang bidang. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Menghapus semua bidang. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Mengembalikan daftar elemen xml yang mewakili tipe nilai dalam pohon xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Menghapus bidang dari daftar bidang. |

### Lihat Juga

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


