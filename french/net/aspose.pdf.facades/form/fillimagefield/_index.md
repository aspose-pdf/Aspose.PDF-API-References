---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Colle une image sur le champ de bouton existant en tant qu'apparence selon son nom de champ entièrement qualifié
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Colle une image sur le champ de bouton existant en tant qu'apparence selon son nom de champ entièrement qualifié.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié du champ de bouton image. |
| imageFileName | String | Le chemin du fichier image, relatif et absolu sont tous deux acceptables. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Surcharge de la fonction FillImageField. L'entrée est un flux d'image.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié. |
| imageStream | Stream | Le flux de l'image. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)