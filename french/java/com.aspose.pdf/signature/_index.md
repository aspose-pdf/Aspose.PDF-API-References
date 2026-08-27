---
title: "Signature"
linktitle: "Signature"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe abstraite qui représente un objet signature dans le document pdf. Les signatures sont des champs contenant des objets signature, le dernier contenant des données utilisées pour la vérification."
type: docs
weight: 4490
url: /fr/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

Une classe abstraite qui représente un objet de signature dans le document PDF. Les signatures sont des champs contenant des objets de signature, ces derniers contenant des données utilisées pour vérifier la validité du document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Signature](#Signature--) | Initialise une nouvelle instance de la classe {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Initialise une nouvelle instance de la classe {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe {@code Signature}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Destructeur qui ferme les flux temporaires (si nécessaire). |
| [getAuthority](#getAuthority--) | Le nom de la personne ou de l'autorité signant le document. |
| [getByteRange](#getByteRange--) | Obtient un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) qui décrivent la plage d'octets exacte pour le calcul du condensat. |
| [getContactInfo](#getContactInfo--) | Obtient les informations fournies par le signataire afin de permettre à un destinataire de contacter le signataire pour vérifier la signature, par ex. un numéro de téléphone. |
| [getCustomAppearance](#getCustomAppearance--) | Obtient/definit l'apparence personnalisée. |
| [getCustomSign](#getCustomSign--) | Le délégué pour le hachage personnalisé et la signature du document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | Le délégué pour la signature personnalisée du hachage du document (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Obtient l'heure de la signature. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Obtient ou définit la longueur par défaut des données de signature en octets. Il s'agit d'une estimation de la longueur de la signature en octets. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si le paramètre {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) est défini. La valeur par défaut est 3000. |
| [getImageInternal](#getImageInternal--) | Obtient le flux d'image. Usage interne uniquement. |
| [getLocation](#getLocation--) | Obtient le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [getOcspSettings](#getOcspSettings--) | Obtient/definit les paramètres OCSP. |
| [getReason](#getReason--) | Obtient la raison de la signature, telle que (J'ai accepté !, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Récupère les informations sur l'algorithme de signature utilisé dans la signature. |
| [getSignatureReferences](#getSignatureReferences--) | obtenir les références de signature |
| [getTimestampSettings](#getTimestampSettings--) | Obtient les paramètres d'horodatage. |
| [getUseLtv](#getUseLtv--) | Obtient/definit le drapeau de validation LTV. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature. Évite d'estimer la longueur de la signature avant la signature d'un document. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) et via {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) renvoie une signature plus longue que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), alors {@code SignatureLengthMismatchException} sera levée. La valeur par défaut est {@code false}. |
| [isShowProperties](#isShowProperties--) | Force l'affichage/masquage des propriétés de la signature. Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {certificate subject} Date : {signature.Date} Raison : {signature.Reason} Lieu : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas les chaînes listées sont placées sur l'image. ShowProperties est vrai par défaut. |
| [setAuthority](#setAuthority-java.lang.String-) | Définit le nom de la personne ou de l'autorité signant le document. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature. Évite d'estimer la longueur de la signature avant la signature d'un document. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) et via {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) renvoie une signature plus longue que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), alors {@code SignatureLengthMismatchException} sera levée. La valeur par défaut est {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Définit les informations fournies par le signataire afin de permettre à un destinataire de contacter le signataire pour vérifier la signature, par ex. un numéro de téléphone. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Obtient/definit l'apparence personnalisée. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Le délégué pour le hachage personnalisé et la signature du document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Le délégué pour la signature personnalisée du hachage du document (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Définit l'heure de la signature. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Obtient ou définit la longueur par défaut des données de signature en octets. Il s'agit d'une estimation de la longueur de la signature en octets. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si le paramètre {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) est défini. La valeur par défaut est 3000. |
| [setImage](#setImage-java.io.InputStream-) | Définit le flux d'image. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Définit le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Obtient/definit les paramètres OCSP. |
| [setReason](#setReason-java.lang.String-) | Définit la raison de la signature, comme (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Force l'affichage/masquage des propriétés de la signature. Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {certificate subject} Date : {signature.Date} Raison : {signature.Reason} Lieu : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas les chaînes listées sont placées sur l'image. ShowProperties est vrai par défaut. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Définit les paramètres d'horodatage. |
| [setUseLtv](#setUseLtv-boolean-) | Obtient/definit le drapeau de validation LTV. |
| [verify](#verify--) | Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false. |

### Signature {#Signature--}
```
public Signature()
```

Initialise une nouvelle instance de la classe {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Initialise une nouvelle instance de la classe {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
Initialise une nouvelle instance de la classe {@code Signature}.

### close {#close--}
```
public void close()
```

Destructeur qui ferme les flux temporaires (si nécessaire).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Le nom de la personne ou de l'autorité signant le document.

**Returns:**
valeur String

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Obtient un tableau de paires d'entiers (décalage d'octet de départ, longueur en octets) qui décrivent la plage d'octets exacte pour le calcul du condensat.

**Returns:**
tableau de valeurs int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Obtient les informations fournies par le signataire afin de permettre à un destinataire de contacter le signataire pour vérifier la signature, par ex. un numéro de téléphone.

**Returns:**
valeur String

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Obtient/definit l'apparence personnalisée.

**Returns:**
instance de SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Le délégué pour le hachage personnalisé et la signature du document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
instance de SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Le délégué pour la signature personnalisée du hachage du document (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
instance de SignHash

### getDate {#getDate--}
```
public Date getDate()
```

Obtient l'heure de la signature.

**Returns:**
valeur Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Obtient ou définit la longueur par défaut des données de signature en octets. Il s'agit d'une estimation de la longueur de la signature en octets. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si le paramètre {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) est défini. La valeur par défaut est 3000.

**Returns:**
valeur int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Obtient le flux d'image. Usage interne uniquement.

**Returns:**
objet Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

Obtient le nom d'hôte du CPU ou l'emplacement physique de la signature.

**Returns:**
valeur String

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Obtient/definit les paramètres OCSP.

**Returns:**
instance de OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

Obtient la raison de la signature, telle que (J'ai accepté !, Pip B.).

**Returns:**
valeur String

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Récupère les informations sur l'algorithme de signature utilisé dans la signature.

**Returns:**
Une instance de { SignatureAlgorithmInfo} qui contient des détails sur l'algorithme de signature.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

obtenir les références de signature

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Obtient les paramètres d'horodatage.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Obtient/definit le drapeau de validation LTV.

**Returns:**
valeur booléenne

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature. Évite d'estimer la longueur de la signature avant la signature d'un document. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) et via {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) renvoie une signature plus longue que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), alors {@code SignatureLengthMismatchException} sera levée. La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Force l'affichage/masquage des propriétés de la signature. Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {certificate subject} Date : {signature.Date} Raison : {signature.Reason} Lieu : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas les chaînes listées sont placées sur l'image. ShowProperties est vrai par défaut.

**Returns:**
valeur booléenne

### setAuthority {#setAuthority-java.lang.String-}
Définit le nom de la personne ou de l'autorité signant le document.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature. Évite d'estimer la longueur de la signature avant la signature d'un document. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) et via {@code ExternalSignature}. Si {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) renvoie une signature plus longue que {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), alors {@code SignatureLengthMismatchException} sera levée. La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setContactInfo {#setContactInfo-java.lang.String-}
Définit les informations fournies par le signataire afin de permettre à un destinataire de contacter le signataire pour vérifier la signature, par ex. un numéro de téléphone.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Obtient/definit l'apparence personnalisée.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Le délégué pour le hachage personnalisé et la signature du document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Le délégué pour la signature personnalisée du hachage du document (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Définit l'heure de la signature.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Obtient ou définit la longueur par défaut des données de signature en octets. Il s'agit d'une estimation de la longueur de la signature en octets. Utilisé pour la signature via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) si le paramètre {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) est défini. La valeur par défaut est 3000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setImage {#setImage-java.io.InputStream-}
Définit le flux d'image.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Définit le nom d'hôte du CPU ou l'emplacement physique de la signature.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Obtient/definit les paramètres OCSP.

### setReason {#setReason-java.lang.String-}
Définit la raison de la signature, comme (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Force l'affichage/masquage des propriétés de la signature. Si ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini (chaînes à représenter) : ------------------------------------------- Signé numériquement par {certificate subject} Date : {signature.Date} Raison : {signature.Reason} Lieu : {signature.Location} ------------------------------------------- où {X} est un espace réservé pour la valeur X. La signature peut également contenir une image ; dans ce cas les chaînes listées sont placées sur l'image. ShowProperties est vrai par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Définit les paramètres d'horodatage.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Obtient/definit le drapeau de validation LTV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### verify {#verify--}
```
public boolean verify()
```

Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false.

**Returns:**
true si le document est valide.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false.

**Returns:**
true si le document est valide.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Vérifie le document concernant cette signature et renvoie true si le document est valide, sinon false.

**Returns:**
true si le document est valide.
