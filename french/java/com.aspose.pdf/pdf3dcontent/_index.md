---
title: "PDF3DContent"
linktitle: "PDF3DContent"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe PDF3DContent."
type: docs
weight: 3580
url: /fr/java/com.aspose.pdf/pdf3dcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DContent

```
public class PDF3DContent extends Object
```

Classe PDF3DContent.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PDF3DContent](#PDF3DContent--) | Initialise une nouvelle instance de la classe {@code PDF3DContent}. |
| [PDF3DContent](#PDF3DContent-java.lang.String-) | Initialise une nouvelle instance de la classe {@code PDF3DContent}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAsByteArray](#getAsByteArray--) | Obtient le contenu 3D sous forme de tableau d'octets. |
| [getAsStream](#getAsStream--) | Obtient le contenu 3D sous forme de flux. |
| [getExtension](#getExtension--) | Obtient l'extension . |
| [load](#load-java.lang.String-) | Charge le contenu 3D avec le nom de fichier spécifié. |
| [loadAsPRC](#loadAsPRC-byte:A-) | Charge le contenu 3D depuis un tableau d'octets au format PRC. |
| [loadAsPRC](#loadAsPRC-java.io.InputStream-) | Charge le contenu 3D depuis un flux au format PRC. |
| [loadAsPRC](#loadAsPRC-java.lang.String-) | Charge le contenu 3D avec le nom de fichier spécifié au format PRC. |
| [loadAsU3D](#loadAsU3D-byte:A-) | Charge le contenu 3D depuis un tableau d'octets au format U3D. |
| [loadAsU3D](#loadAsU3D-java.io.InputStream-) | Charge le contenu 3D depuis un flux au format U3D. |
| [loadAsU3D](#loadAsU3D-java.lang.String-) | Charge le contenu 3D avec le nom de fichier spécifié au format U3D. |
| [saveToFile](#saveToFile-java.lang.String-) | Enregistre le contenu 3D dans un fichier. |

### PDF3DContent {#PDF3DContent--}
```
public PDF3DContent()
```

Initialise une nouvelle instance de la classe {@code PDF3DContent}.

### PDF3DContent {#PDF3DContent-java.lang.String-}
Initialise une nouvelle instance de la classe {@code PDF3DContent}.

### getAsByteArray {#getAsByteArray--}
```
public byte[] getAsByteArray()
```

Obtient le contenu 3D sous forme de tableau d'octets.

**Returns:**
System.Byte[].

### getAsStream {#getAsStream--}
```
public InputStream getAsStream()
```

Obtient le contenu 3D sous forme de flux.

**Returns:**
Flux.

### getExtension {#getExtension--}
```
public String getExtension()
```

Obtient l'extension .

**Returns:**
Objet String : L'extension.

### load {#load-java.lang.String-}
Charge le contenu 3D avec le nom de fichier spécifié.

### loadAsPRC {#loadAsPRC-byte:A-}
```
public void loadAsPRC(byte[] stream)
```

Charge le contenu 3D depuis un tableau d'octets au format PRC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux |  | Le flux. |

### loadAsPRC {#loadAsPRC-java.io.InputStream-}
Charge le contenu 3D depuis un flux au format PRC.

### loadAsPRC {#loadAsPRC-java.lang.String-}
Charge le contenu 3D avec le nom de fichier spécifié au format PRC.

### loadAsU3D {#loadAsU3D-byte:A-}
```
public void loadAsU3D(byte[] stream)
```

Charge le contenu 3D depuis un tableau d'octets au format U3D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux |  | Le flux. |

### loadAsU3D {#loadAsU3D-java.io.InputStream-}
Charge le contenu 3D depuis un flux au format U3D.

### loadAsU3D {#loadAsU3D-java.lang.String-}
Charge le contenu 3D avec le nom de fichier spécifié au format U3D.

### saveToFile {#saveToFile-java.lang.String-}
Enregistre le contenu 3D dans un fichier.
