---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Klistrar in en bild på den befintliga knappfältet som dess utseende enligt dess fullständiga kvalificerade fältnamn
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Klistrar in en bild på den befintliga knappfältet som dess utseende enligt dess fullständiga kvalificerade fältnamn.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullständiga kvalificerade fältnamnet för bildknappfältet. |
| imageFileName | Sträng | Sökvägen till bildfilen, både relativa och absoluta är okej. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Överlagrar funktionen för FillImageField. Inmatningen är en bildström.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullständiga kvalificerade fältnamnet. |
| imageStream | Ström | Bildens ström. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)