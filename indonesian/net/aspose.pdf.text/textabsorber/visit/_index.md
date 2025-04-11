---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metode TextAbsorber. Mengekstrak teks pada halaman yang ditentukan
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
| page | Page | Objek halaman dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [TextAbsorber](../)
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
| form | XForm | Objek formulir Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### Lihat Juga

* kelas [XForm](../../../aspose.pdf/xform/)
* kelas [TextAbsorber](../)
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
| pdf | Document | Objek dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)