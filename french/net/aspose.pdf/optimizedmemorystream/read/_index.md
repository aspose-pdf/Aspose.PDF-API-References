---
title: Read
second_title: Référence de l'API Aspose.PDF pour .NET
description: En cas de remplacement dans une classe dérivée lit une séquence doctets à partir du flux actuel et avance la position dans le flux du nombre doctets lus.
type: docs
weight: 100
url: /fr/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

En cas de remplacement dans une classe dérivée, lit une séquence d'octets à partir du flux actuel et avance la position dans le flux du nombre d'octets lus.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| buffer | Byte[] | Un tableau d'octets. Lorsque cette méthode revient, le tampon contient le tableau d'octets spécifié avec les valeurs |
| offset | Int32 | Décalage d'octet de base zéro à partir duquel commencer à stocker les données lues à partir du flux actuel. |
| count | Int32 | Le nombre maximal d'octets à lire à partir du flux actuel. |

### Return_Value

Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandés si ce nombre d'octets ne sont pas actuellement disponibles, ou zéro (0) si la fin du flux a été atteinte.

### Voir également

* class [OptimizedMemoryStream](../../optimizedmemorystream)
* espace de noms [Aspose.Pdf](../../optimizedmemorystream)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->