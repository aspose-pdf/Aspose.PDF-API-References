---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le fichier intégré."
type: docs
weight: 1510
url: /fr/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Classe représentant le fichier intégré.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Crée une nouvelle spécification de fichier vide. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Crée une nouvelle spécification de fichier vide. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Relation de fichier associée. |
| [getCollectionItem](#getCollectionItem--) | Obtient un élément de collection de la spécification de fichier. |
| [getContents](#getContents--) | Obtient le fichier de contenu. |
| [getContentsInternal](#getContentsInternal--) | Obtient le fichier de contenu. |
| [getDescription](#getDescription--) | Obtient le texte associé à la spécification de fichier. |
| [getEncoding](#getEncoding--) | Obtient le format d'encodage. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé. |
| [getEncryptedPayload](#getEncryptedPayload--) | Obtient la charge utile chiffrée. |
| [getEngineDict](#getEngineDict--) | Dictionnaire PDF contenant des informations sur le fichier. Interne uniquement |
| [getEngineObj](#getEngineObj--) | Interne uniquement |
| [getFileSystem](#getFileSystem--) | Obtient le nom du système de fichiers. |
| [getMIMEType](#getMIMEType--) | Obtient le sous-type du fichier intégré |
| [getName](#getName--) | Obtient le nom de la spécification de fichier. |
| [getParams](#getParams--) | Obtient les paramètres du fichier. |
| [getStreamContents](#getStreamContents--) | Obtient le contenu du fichier sous forme de flux. Le contenu n'est pas chargé en mémoire, ce qui permet de réduire l'utilisation de la mémoire. Cependant, ce flux ne prend pas en charge le positionnement ni la propriété Length. Si vous avez besoin de ces fonctionnalités, veuillez utiliser la propriété Contents à la place. |
| [getUnicodeName](#getUnicodeName--) | Obtient le nom Unicode de la spécification de fichier. |
| [getValue](#getValue-java.lang.String-) | Obtient le paramètre spécifique à l'application. |
| [isIncludeContents](#isIncludeContents--) | Si vrai, le contenu du fichier sera inclus dans la spécification de fichier. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Relation de fichier associée. |
| [setContents](#setContents-byte:A-) | Définit le contenu du fichier. |
| [setContents](#setContents-java.io.InputStream-) | Définit le contenu du fichier. |
| [setDescription](#setDescription-java.lang.String-) | Définit le texte associé à la spécification de fichier. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Définit le format d'encodage. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Définit le nom du système de fichiers. |
| [setIncludeContents](#setIncludeContents-boolean-) | Si vrai, le contenu du fichier sera inclus dans la spécification de fichier. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Définit le MIMEType. |
| [setName](#setName-java.lang.String-) | Définit le nom de la spécification de fichier. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Définit les paramètres du fichier. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Définit le nom Unicode de la spécification de fichier. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Définit le paramètre spécifique à l'application. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Crée une nouvelle spécification de fichier vide.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Crée une nouvelle spécification de fichier vide.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Relation de fichier associée.

**Returns:**
Élément AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Obtient un élément de collection de la spécification de fichier.

**Returns:**
Instance CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtient le fichier de contenu.

**Returns:**
Objet InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtient le fichier de contenu.

**Returns:**
objet Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

Obtient le texte associé à la spécification de fichier.

**Returns:**
valeur String

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Obtient le format d'encodage. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé.

**Returns:**
valeur int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Obtient la charge utile chiffrée.

**Returns:**
Instance EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Dictionnaire PDF contenant des informations sur le fichier. Interne uniquement

**Returns:**
Objet IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Interne uniquement

**Returns:**
Objet IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Obtient le nom du système de fichiers.

**Returns:**
valeur String

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Obtient le sous-type du fichier intégré

**Returns:**
valeur de chaîne

### getName {#getName--}
```
public String getName()
```

Obtient le nom de la spécification de fichier.

**Returns:**
valeur String

### getParams {#getParams--}
```
public FileParams getParams()
```

Obtient les paramètres du fichier.

**Returns:**
objet FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Obtient le contenu du fichier sous forme de flux. Le contenu n'est pas chargé en mémoire, ce qui permet de réduire l'utilisation de la mémoire. Cependant, ce flux ne prend pas en charge le positionnement ni la propriété Length. Si vous avez besoin de ces fonctionnalités, veuillez utiliser la propriété Contents à la place.

**Returns:**
Objet InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Obtient le nom Unicode de la spécification de fichier.

**Returns:**
valeur String

### getValue {#getValue-java.lang.String-}
Obtient le paramètre spécifique à l'application.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Si vrai, le contenu du fichier sera inclus dans la spécification de fichier.

**Returns:**
valeur booléenne

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Relation de fichier associée.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Définit le contenu du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau d'octets |

### setContents {#setContents-java.io.InputStream-}
Définit le contenu du fichier.

### setDescription {#setDescription-java.lang.String-}
Définit le texte associé à la spécification de fichier.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Définit le format d'encodage. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé.

### setFileSystem {#setFileSystem-java.lang.String-}
Définit le nom du système de fichiers.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Si vrai, le contenu du fichier sera inclus dans la spécification de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMIMEType {#setMIMEType-java.lang.String-}
Définit le MIMEType.

### setName {#setName-java.lang.String-}
Définit le nom de la spécification de fichier.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Définit les paramètres du fichier.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Définit le nom Unicode de la spécification de fichier.

### setValue {#setValue-java.lang.String-java.lang.String-}
Définit le paramètre spécifique à l'application.
