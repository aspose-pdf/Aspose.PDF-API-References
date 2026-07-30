---
title: "XImageCollection.Replace"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode XImageCollection. Remplace l'image dans la collection par une autre image"
type: docs
weight: 150
url: /fr/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Remplacez l'image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Indice de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |

### Voir aussi

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Remplacez l'image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Indice de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |
| quality | Int32 | Qualité de la compression JPEG, en pourcentage (les valeurs valides sont 0..100). |
| isBlackAndWhite | Boolean | Si vrai, l'image est compressée avec la méthode de compression CCITT qui offre une meilleure compression pour les images noir et blanc. Peut être utilisée uniquement pour les images noir et blanc. |

### Voir aussi

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Remplacez l'image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Indice de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |
| quality | Int32 | Qualité JPEG. |

### Voir aussi

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


