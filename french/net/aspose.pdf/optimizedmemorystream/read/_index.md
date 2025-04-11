---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: Méthode OptimizedMemoryStream. Lorsqu'elle est remplacée dans une classe dérivée, elle lit une séquence d'octets à partir du flux actuel et avance la position dans le flux du nombre d'octets lus.
type: docs
weight: 100
url: /fr/net/aspose.pdf/optimizedmemorystream/read/
---
## Méthode OptimizedMemoryStream.Read

Lorsqu'elle est remplacée dans une classe dérivée, elle lit une séquence d'octets à partir du flux actuel et avance la position dans le flux du nombre d'octets lus.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | Byte[] | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs |
| offset | Int32 | Le décalage d'octets basé sur zéro à partir duquel commencer à stocker les données lues à partir du flux actuel. |
| count | Int32 | Le nombre maximum d'octets à lire à partir du flux actuel. |

### Valeur de retour

Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandés si autant d'octets ne sont pas actuellement disponibles, ou zéro (0) si la fin du flux a été atteinte.

### Voir aussi

* classe [OptimizedMemoryStream](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)