---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: Méthode XImageCollection. Remplacer une image dans la collection par une autre image
type: docs
weight: 150
url: /fr/net/aspose.pdf/ximagecollection/replace/
---
## Remplacer(int, Stream) {#replace}

Remplacer une image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |

### Voir aussi

* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Remplacer(int, Stream, int, bool) {#replace_2}

Remplacer une image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |
| quality | Int32 | Qualité de la compression JPEG, en pourcentage (valeurs valides sont 0..100). |
| isBlackAndWhite | Boolean | Si vrai, l'image est compressée avec la méthode de compression CCITT qui fournit une meilleure compression pour les images en noir et blanc. Peut être utilisé uniquement pour les images en noir et blanc. |

### Voir aussi

* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Remplacer(int, Stream, int) {#replace_1}

Remplacer une image dans la collection par une autre image.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de l'élément de la collection qui sera remplacé dans la plage [1..nombre d'images]. |
| stream | Stream | Flux contenant les données de l'image (au format JPEG). |
| quality | Int32 | Qualité JPEG. |

### Voir aussi

* classe [XImageCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)