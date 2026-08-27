---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Définit un MemoryStream qui peut contenir une capacité plus standard"
type: docs
weight: 3220
url: /fr/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Définit un MemoryStream qui peut contenir une capacité plus standard

## Champs

| Champ | Description |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Valeur par défaut de la taille du tampon en octets. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream} basée sur le tableau d'octets spécifié. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream} basée sur le tableau d'octets spécifié. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [canRead](#canRead--) | Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge la lecture. |
| [canSeek](#canSeek--) | Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge le repositionnement. |
| [canWrite](#canWrite--) | Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge l'écriture. |
| [flush](#flush--) | La fonction est surchargée. |
| [getBufferSize](#getBufferSize--) | Obtient ou définit la taille des tampons sous-jacents. Valeur : la taille des tampons. |
| [getFreeOnDispose](#getFreeOnDispose--) | Obtient ou définit une valeur indiquant s’il faut libérer les tampons sous-jacents lors du dispose. |
| [getLength](#getLength--) | Lorsqu’il est remplacé dans une classe dérivée, obtient la longueur en octets du flux. |
| [getPosition](#getPosition--) | Lorsqu’il est remplacé dans une classe dérivée, obtient ou définit la position dans le flux actuel. |
| [read](#read-byte:A-int-int-) | Lorsqu’il est remplacé dans une classe dérivée, lit une séquence d’octets du flux actuel et avance la position dans le flux du nombre d’octets lus. |
| [readByte](#readByte--) | Lit un octet du flux et avance la position dans le flux d’un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [seek](#seek-long-int-) | Lorsqu’il est remplacé dans une classe dérivée, définit la position dans le flux actuel. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Lorsqu’il est remplacé dans une classe dérivée, définit la position dans le flux actuel. |
| [setBufferSize](#setBufferSize-int-) | Obtient ou définit la taille des tampons sous-jacents. Valeur : la taille des tampons. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Obtient ou définit une valeur indiquant s’il faut libérer les tampons sous-jacents lors du dispose. |
| [setLength](#setLength-long-) | Lorsqu’il est remplacé dans une classe dérivée, définit la longueur du flux actuel. |
| [setPosition](#setPosition-long-) | Lorsqu’il est remplacé dans une classe dérivée, obtient ou définit la position dans le flux actuel. La position actuelle dans le flux. Valeur : |
| [toArray](#toArray--) | Convertit le flux actuel en tableau d’octets. |
| [write](#write-byte:A-int-int-) | Lorsqu’il est remplacé dans une classe dérivée, écrit une séquence d’octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d’octets écrits. |
| [writeByte](#writeByte-byte-) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d’un octet. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Écrit dans le flux spécifié. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Valeur par défaut de la taille du tampon en octets.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream} basée sur le tableau d'octets spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tampon |  | Le tableau d’octets non signés à partir duquel créer le flux actuel. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bufferSize |  | Taille des tampons sous-jacents. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Initialise une nouvelle instance de la classe {@link OptimizedMemoryStream} basée sur le tableau d'octets spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bufferSize |  | Taille des tampons sous-jacents. |
| tampon |  | Le tableau d’octets non signés à partir duquel créer le flux actuel. |

### canRead {#canRead--}
```
public boolean canRead()
```

Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge la lecture.

**Returns:**
true si le flux prend en charge la lecture ; sinon, false. Valeur :

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge le repositionnement.

**Returns:**
true si le flux prend en charge le repositionnement ; sinon, false. Valeur :

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Lorsqu'elle est remplacée dans une classe dérivée, obtient une valeur indiquant si le flux actuel prend en charge l'écriture.

**Returns:**
true si le flux prend en charge l’écriture ; sinon, false. Valeur :

### flush {#flush--}
```
public void flush()
```

La fonction est surchargée.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Obtient ou définit la taille des tampons sous-jacents. Valeur : la taille des tampons.

**Returns:**
valeur int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Obtient ou définit une valeur indiquant s’il faut libérer les tampons sous-jacents lors du dispose.

**Returns:**
valeur booléenne

### getLength {#getLength--}
```
public long getLength()
```

Lorsqu’il est remplacé dans une classe dérivée, obtient la longueur en octets du flux.

**Returns:**
Une valeur long représentant la longueur du flux en octets. Valeur :

### getPosition {#getPosition--}
```
public long getPosition()
```

Lorsqu’il est remplacé dans une classe dérivée, obtient ou définit la position dans le flux actuel.

**Returns:**
La position actuelle dans le flux. Valeur :

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Lorsqu’il est remplacé dans une classe dérivée, lit une séquence d’octets du flux actuel et avance la position dans le flux du nombre d’octets lus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tampon |  | Un tableau d’octets. Lorsque cette méthode retourne, le tampon contient le tableau d’octets spécifié avec les valeurs |
| décalage |  | Le décalage d’octet basé sur zéro à partir duquel commencer à stocker les données lues du flux actuel. |
| compte |  | Le nombre maximal d’octets à lire depuis le flux actuel. |

**Returns:**
Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandés si autant d'octets ne sont pas actuellement disponibles, ou zéro (0) si la fin du flux a été atteinte.

### readByte {#readByte--}
```
public int readByte()
```

Lit un octet du flux et avance la position dans le flux d’un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns:**
octet ou -1 si vous êtes à la fin du flux.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Lorsqu’il est remplacé dans une classe dérivée, définit la position dans le flux actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| décalage |  | Un décalage d'octet relatif au paramètre {@code origin}. |
| origin |  | Une valeur de type {@link SeekOrigin} indiquant le point de référence utilisé pour obtenir la nouvelle position. |

**Returns:**
La nouvelle position dans le flux actuel.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Lorsqu’il est remplacé dans une classe dérivée, définit la position dans le flux actuel.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Obtient ou définit la taille des tampons sous-jacents. Valeur : la taille des tampons.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Obtient ou définit une valeur indiquant s’il faut libérer les tampons sous-jacents lors du dispose.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Lorsqu’il est remplacé dans une classe dérivée, définit la longueur du flux actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | La longueur souhaitée du flux actuel en octets. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Lorsqu’il est remplacé dans une classe dérivée, obtient ou définit la position dans le flux actuel. La position actuelle dans le flux. Valeur :

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Convertit le flux actuel en tableau d’octets.

**Returns:**
Un tableau d'octets

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Lorsqu’il est remplacé dans une classe dérivée, écrit une séquence d’octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d’octets écrits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tampon |  | Un tableau d'octets. Cette méthode copie {@code count} octets de {@code buffer} vers le flux actuel. |
| décalage |  | Le décalage d'octet basé sur zéro dans {@code buffer} à partir duquel commencer à copier les octets vers le flux actuel. |
| compte |  | Le nombre d'octets à écrire dans le flux actuel. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d’un octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | L'octet à écrire dans le flux. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Écrit dans le flux spécifié.
