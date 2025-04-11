---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OptimizedMemoryStream. Définit un MemoryStream qui peut contenir une capacité plus standard
type: docs
weight: 7990
url: /fr/net/aspose.pdf/optimizedmemorystream/
---
## Classe OptimizedMemoryStream

Définit un MemoryStream qui peut contenir une capacité plus standard

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Initialise une nouvelle instance de la classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `OptimizedMemoryStream` basée sur le tableau de bytes spécifié. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Initialise une nouvelle instance de la classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Initialise une nouvelle instance de la classe `OptimizedMemoryStream` basée sur le tableau de bytes spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Obtient ou définit la taille des tampons sous-jacents. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Lorsqu'il est remplacé dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge la lecture. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Lorsqu'il est remplacé dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge la recherche. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Lorsqu'il est remplacé dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge l'écriture. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut libérer les tampons sous-jacents lors de la suppression. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Lorsqu'il est remplacé dans une classe dérivée, obtient la longueur en octets du flux. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Lorsqu'il est remplacé dans une classe dérivée, obtient ou définit la position dans le flux actuel. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | La fonction remplacée. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Lorsqu'il est remplacé dans une classe dérivée, lit une séquence d'octets à partir du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Lit un octet à partir du flux et avance la position dans le flux d'un octet, ou retourne -1 si à la fin du flux. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Lorsqu'il est remplacé dans une classe dérivée, définit la position dans le flux actuel. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Lorsqu'il est remplacé dans une classe dérivée, définit la longueur du flux actuel. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Convertit le flux actuel en un tableau de bytes. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Lorsqu'il est remplacé dans une classe dérivée, écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Écrit dans le flux spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Valeur par défaut de la taille du tampon en octets. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)