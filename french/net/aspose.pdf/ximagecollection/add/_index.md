---
title: Add
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute une nouvelle image à la liste des images. Cette méthode ajoute limage comme référence au même PdfObject ce qui permet de diminuer la taille du fichier
type: docs
weight: 70
url: /fr/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add}

Ajoute une nouvelle image à la liste des images. Cette méthode ajoute l'image comme référence au même PdfObject (ce qui permet de diminuer la taille du fichier)

```csharp
public string Add(XImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | XImage | XImage à ajouter. |

### Return_Value

Nom de l'image ajoutée.

### Voir également

* class [XImage](../../ximage)
* class [XImageCollection](../../ximagecollection)
* espace de noms [Aspose.Pdf](../../ximagecollection)
* Assemblée [Aspose.PDF](../../../)

---

## Add(Stream) {#add_1}

Ajoute une entité à la fin de la collection, afin que l'entité soit accessible par le dernier index.

```csharp
public string Add(Stream image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Stream | Flux contenant des données d'image (au format JPEG). |

### Return_Value

Nom de l'image ajoutée.

### Voir également

* class [XImageCollection](../../ximagecollection)
* espace de noms [Aspose.Pdf](../../ximagecollection)
* Assemblée [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_2}

Ajoute une entité à la fin de la collection, afin que l'entité soit accessible par le dernier index.

```csharp
public void Add(Stream image, ImageFilterType filterType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Stream | Flux contenant des données d'image. |
| filterType | ImageFilterType | Le type de filtre d'image. |

### Voir également

* enum [ImageFilterType](../../imagefiltertype)
* class [XImageCollection](../../ximagecollection)
* espace de noms [Aspose.Pdf](../../ximagecollection)
* Assemblée [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_3}

Ajoute une entité à la fin de la collection, afin que l'entité soit accessible par le dernier index.

```csharp
public void Add(Stream image, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Stream | Flux contenant des données d'image (au format JPEG). |
| quality | Int32 | Qualité JPEG. |

### Voir également

* class [XImageCollection](../../ximagecollection)
* espace de noms [Aspose.Pdf](../../ximagecollection)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->