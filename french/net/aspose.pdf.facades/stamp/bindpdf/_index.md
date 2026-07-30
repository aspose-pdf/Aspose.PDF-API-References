---
title: "Stamp.BindPdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Stamp. Définit le fichier PDF et le numéro de page qui sera utilisé comme tampon"
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdfFile | String | Chemin du fichier PDF. |
| pageNumber | Int32 | Numéro de page dans le fichier PDF |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La première page sera utilisée comme tampon.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdfStream | Stream | Flux contenant le document PDF. |
| pageNumber | Int32 | Indice de page du document qui sera utilisé comme tampon. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La première page sera utilisée comme tampon.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


