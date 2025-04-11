---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Méthode XImageCollection. Ajoute une nouvelle image à la liste d'images. Cette méthode ajoute l'image en tant que référence au même PdfObject, ce qui permet de réduire la taille du fichier
type: docs
weight: 70
url: /fr/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Ajoute une nouvelle image à la liste d'images. Cette méthode ajoute l'image en tant que référence au même PdfObject (ce qui permet de réduire la taille du fichier)

```csharp
public string Add(XImage image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | XImage | XImage à ajouter. |

### Valeur de retour

Nom de l'image ajoutée.

### Voir aussi

* classe [XImage](../../ximage/)
* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Ajoute une entité à la fin de la collection, afin que l'entité puisse être accessible par le dernier index.

```csharp
public string Add(Stream image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Stream | Flux contenant les données de l'image (au format JPEG). |

### Valeur de retour

Nom de l'image ajoutée.

### Voir aussi

* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Ajoute une entité à la fin de la collection, afin que l'entité puisse être accessible par le dernier index.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objet contenant un tableau de pixels et des informations sur le bitmap (Largeur, Hauteur, Format de pixel). |

### Valeur de retour

Nom de l'image ajoutée.

### Voir aussi

* classe [BitmapInfo](../../bitmapinfo/)
* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Ajoute une entité à la fin de la collection, afin que l'entité puisse être accessible par le dernier index.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Stream | Flux contenant les données de l'image. |
| filterType | ImageFilterType | Le type de filtre d'image. |

### Valeur de retour

Nom de l'image ajoutée.

### Voir aussi

* enum [ImageFilterType](../../imagefiltertype/)
* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Ajoute une entité à la fin de la collection, afin que l'entité puisse être accessible par le dernier index.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objet contenant un tableau de pixels et des informations sur le bitmap (Largeur, Hauteur, Format de pixel). |
| filterType | ImageFilterType | Le type de filtre d'image. |

### Valeur de retour

Nom de l'image ajoutée.

### Voir aussi

* classe [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Ajoute une entité à la fin de la collection, afin que l'entité puisse être accessible par le dernier index.

```csharp
public void Add(Stream image, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Stream | Flux contenant les données de l'image (au format JPEG). |
| quality | Int32 | Qualité JPEG. |

### Voir aussi

* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)