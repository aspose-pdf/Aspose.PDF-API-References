---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Erscheinungsbild gemäß seinem vollqualifizierten Feldnamen ein
type: docs
weight: 150
url: /de/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Erscheinungsbild gemäß seinem vollqualifizierten Feldnamen ein.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname des Bildschaltflächenfelds. |
| imageFileName | String | Der Pfad zur Bilddatei, sowohl relative als auch absolute Pfade sind in Ordnung. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Überladet die Funktion von FillImageField. Der Eingang ist ein Bildstream.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname. |
| imageStream | Stream | Der Stream des Bildes. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)