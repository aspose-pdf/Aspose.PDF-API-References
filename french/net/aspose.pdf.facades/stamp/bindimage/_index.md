---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode Stamp. Définit l'image comme un tampon
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Définit l'image comme un tampon.

```csharp
public void BindImage(string imageFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageFile | String | Nom et chemin du fichier image. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* classe [Stamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Définit l'image qui sera utilisée comme tampon.

```csharp
public void BindImage(Stream image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Stream | Flux qui contient les données de l'image. |

### Voir aussi

* classe [Stamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)