---
title: "Form.FillImageField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Form méthode. Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié"
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié du champ bouton image. |
| imageFileName | String | Le chemin du fichier image, relatif et absolu sont tous deux acceptés. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Surcharge la fonction FillImageField. L'entrée est un flux d'image.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ. |
| imageStream | Stream | Le flux de l'image. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


