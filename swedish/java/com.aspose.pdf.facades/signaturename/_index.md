---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för ett signaturnamn. Representerar ett mer exakt signaturnamn. Används istället för strängnamn. Gör det möjligt att presentera signaturer med samma strängnamn."
type: docs
weight: 690
url: /sv/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Representerar en klass för ett signaturnamn. Representerar ett mer exakt signaturnamn. Används istället för strängnamn. Gör det möjligt att presentera signaturer med samma strängnamn.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [FullName](#FullName) | Hämtar hela namnet på signaturen och tillhandahåller en unik och exakt identifierare för signaturfältet. |
| [Name](#Name) | Hämtar namnet på en signatur. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Bestämmer om detta objekt och ett angivet objekt är lika. |
| [getSignatureDictionary](#getSignatureDictionary--) | Hämtar signaturordlistan. |
| [hashCode](#hashCode--) | Returnerar en hashkod för detta objekt baserat på egenskapen FullName. |
| [hasSignature](#hasSignature--) | Anger om signaturen är närvarande eller inte. |
| [toString](#toString--) | Returnerar en strängrepresentation av {@link SignatureName}-instansen, främst med dess namn. |

### FullName {#FullName}
```
public final String FullName
```

Hämtar hela namnet på signaturen och tillhandahåller en unik och exakt identifierare för signaturfältet.

### Name {#Name}
```
public final String Name
```

Hämtar namnet på en signatur.

### equals {#equals-java.lang.Object-}
Bestämmer om detta objekt och ett angivet objekt är lika.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Hämtar signaturordlistan.

**Returns:**
Signaturordlistan eller null om den inte hittas.

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar en hashkod för detta objekt baserat på egenskapen FullName.

**Returns:**
Ett heltal som representerar hashkoden för egenskapen FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Anger om signaturen är närvarande eller inte.

**Returns:**
booleskt värde

### toString {#toString--}
```
public String toString()
```

Returnerar en strängrepresentation av {@link SignatureName}-instansen, främst med dess namn.

**Returns:**
En sträng som representerar signaturens namn.
