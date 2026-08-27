---
title: "OptimizedMemoryStream.Read"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OptimizedMemoryStream. Lorsqu'elle est remplacée dans une classe dérivée, elle lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus."
type: docs
weight: 100
url: /fr/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

Lorsqu'il est remplacé dans une classe dérivée, lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tampon | Byte[] | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs. |
| décalage | Int32 | Le décalage d'octet basé sur zéro dans le tampon à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| nombre | Int32 | Le nombre maximal d'octets à lire depuis le flux actuel. |

### Valeur de retour

Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandé si autant d'octets ne sont pas disponibles actuellement, ou zéro (0) si la fin du flux a été atteinte.

### Voir aussi

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


