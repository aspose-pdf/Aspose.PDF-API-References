---
title: "Page.AddImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Page. Ajoute une image sur la page et la place au centre du rectangle spécifié en conservant les proportions de l'image."
type: docs
weight: 350
url: /fr/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Ajoute une image sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Le flux de l'image. |
| imageRect | Rectangle | La position de l'image. |
| bbox | Rectangle | Bbox de l'image. |
| autoAdjustRectangle | Boolean | Ajuster l'image au centre du rectangle d'entrée. |

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Ajoute une image recherchable sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| hocr | String | Le hocr de l'image. |
| imageStream | Stream | Le flux de l'image. |
| imageRect | Rectangle | La position de l'image. |
| bbox | Rectangle | Le bbox de l'image. |

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Ajoute une image sur la Page et la place en fonction de la position du rectangle de l'image.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Le flux de l'image. |
| imageRect | Rectangle | La position par défaut de l'image sur la page. |
| imageWidth | Int32 | La largeur de l'image. |
| imageHeight | Int32 | La hauteur de l'image. |
| saveImageProportions | Boolean | Si le drapeau est défini sur true, alors l'image est placée dans la position du rectangle ; sinon, la taille du rectangle devient égale à la taille de l'image. |
| bbox | Rectangle | Le bbox de l'image. |

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Ajoute une image sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imagePath | String | Le chemin vers l'image. |
| Rectangle | Rectangle | La position de l'image. |

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


