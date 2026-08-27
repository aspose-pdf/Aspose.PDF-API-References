---
title: "SoundData"
linktitle: "SoundData"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente des données sonores définissant le son à jouer lorsque l'annotation est activée."
type: docs
weight: 4540
url: /fr/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Représente des données sonores définissant le son à jouer lorsque l'annotation est activée.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBits](#getBits--) | Obtient le nombre de bits par valeur d'échantillon par canal. |
| [getChannels](#getChannels--) | Obtient le nombre de canaux audio. |
| [getContents](#getContents--) | Obtient le flux du son à lire lorsque l'annotation est activée. |
| [getContentsInternal](#getContentsInternal--) | Obtient le flux du son à lire lorsque l'annotation est activée. |
| [getEncoding](#getEncoding--) | Obtient le format d'encodage des données d'échantillon. |
| [getRate](#getRate--) | Obtient le taux d'échantillonnage, en échantillons par seconde. |
| [setBits](#setBits-int-) | Définit le nombre de bits par valeur d'échantillon par canal. |
| [setChannels](#setChannels-int-) | Définit le nombre de canaux audio. |
| [setEncoding](#setEncoding-int-) | Définit le format d'encodage des données d'échantillon. |
| [setRate](#setRate-int-) | Définit le taux d'échantillonnage, en échantillons par seconde. |

### getBits {#getBits--}
```
public int getBits()
```

Obtient le nombre de bits par valeur d'échantillon par canal.

**Returns:**
int valeur nombre de bits

### getChannels {#getChannels--}
```
public int getChannels()
```

Obtient le nombre de canaux audio.

**Returns:**
Le nombre de canaux audio.

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtient le flux du son à lire lorsque l'annotation est activée.

**Returns:**
Valeur InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtient le flux du son à lire lorsque l'annotation est activée.

**Returns:**
Valeur Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Obtient le format d'encodage des données d'échantillon.

**Returns:**
Valeur SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Obtient le taux d'échantillonnage, en échantillons par seconde.

**Returns:**
valeur int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Définit le nombre de bits par valeur d'échantillon par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | nombre de bits |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Définit le nombre de canaux audio.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Le nombre de canaux audio. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Définit le format d'encodage des données d'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Définit le taux d'échantillonnage, en échantillons par seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
