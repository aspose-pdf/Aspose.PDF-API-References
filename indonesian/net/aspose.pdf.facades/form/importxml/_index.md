---
title: "Form.ImportXml"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengimpor konten bidang dari file xml dan menempatkannya ke dalam pdf baru."
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Mengimpor konten bidang dari file xml dan menaruhnya ke dalam pdf baru.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputXmlStream | Stream | Stream dari mana XML untuk impor dibaca. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Mengimpor konten bidang dari file xml dan menaruhnya ke dalam pdf baru.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputXmlStream | Stream | Stream xml input. |
| IgnoreFormTemplateChanges | Boolean | Jika parameter ini true maka semua perubahan pada templat formulir XFA tidak akan disimpan. |

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


