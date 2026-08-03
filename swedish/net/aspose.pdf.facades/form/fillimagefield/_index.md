---
title: "Form.FillImageField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn."
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständiga fältnamn.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet för bildknappfältet. |
| imageFileName | String | Sökvägen till bildfilen, relativ och absolut är båda ok. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Överlagrar funktionen FillImageField. Indatan är en bildström.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet. |
| imageStream | Stream | Bildens ström. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


