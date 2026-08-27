---
title: "TextAbsorber.Visit"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextAbsorber. Mengekstrak teks pada halaman yang ditentukan."
type: docs
weight: 70
url: /id/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Mengekstrak teks pada halaman yang ditentukan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Halaman | Objek halaman dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk semua halaman dokumen
absorber.Visit(doc.Pages[1]);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;
```

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Mengekstrak teks pada XForm yang ditentukan.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formulir | XForm | Objek formulir Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk semua halaman dokumen
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;
```

### Lihat Juga

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Mengekstrak teks pada dokumen yang ditentukan

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdf | Document | Objek Pdf pocument. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk semua halaman dokumen
absorber.Visit(doc);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


