---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant d'accéder aux métadonnées d'un document PDF."
type: docs
weight: 490
url: /fr/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Représente une classe permettant d'accéder aux métadonnées d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialise la façade. |
| [clearInfo](#clearInfo--) | Efface toutes les métadonnées du document PDF. |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [dispose](#dispose--) | Ferme toutes les ressources utilisées par cette instance. Cette méthode est obsolète, utilisez close() à la place. |
| [getAuthor](#getAuthor--) | Obtient les informations d'auteur du document PDF. |
| [getCreationDate](#getCreationDate--) | Obtient les informations de CreationDate du document PDF. |
| [getCreator](#getCreator--) | Obtient les informations du créateur du document PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Obtient les paramètres de privilèges du document PDF. |
| [getHeader](#getHeader--) | <p> Obtient les informations personnalisées du document PDF. </p> |
| [getInputFile](#getInputFile--) | Obtient le fichier d'entrée. |
| [getInputStream](#getInputStream--) | Obtient le flux d'entrée. |
| [getKeywords](#getKeywords--) | Obtient les informations des mots‑clés du document PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Obtient les informations personnalisées du document PDF avec le nom de propriété. S'il n'existe aucune propriété correspondant au nom, cela renverra une chaîne vide. |
| [getModDate](#getModDate--) | Obtient les informations de date ModDate du document PDF. |
| [getNumberOfPages](#getNumberOfPages--) | Obtient le nombre de pages du document. |
| [getPageHeight](#getPageHeight-int-) | Obtient la hauteur de la page spécifiée. |
| [getPageRotation](#getPageRotation-int-) | Obtient la rotation de la page spécifiée. |
| [getPageWidth](#getPageWidth-int-) | Obtient la largeur de la page spécifiée. |
| [getPageXOffset](#getPageXOffset-int-) | Obtient le décalage horizontal de la zone d'affichage de la page spécifiée. |
| [getPageYOffset](#getPageYOffset-int-) | Obtient le décalage vertical de la zone d'affichage de la page spécifiée. |
| [getPasswordType](#getPasswordType--) | Renvoie le type de mot de passe qui a été fourni lors de la création de l'instance PdfFileInfo. Voir les valeurs possibles dans {@code PasswordType}. Notez que le document PDF peut être ouvert à l'aide à la fois du mot de passe utilisateur (ou d'ouverture) et du mot de passe propriétaire (ou de permissions, d'édition). |
| [getPdfVersion](#getPdfVersion--) | Obtient les informations de version du document PDF. |
| [getProducer](#getProducer--) | Obtient les informations du producteur du document PDF. |
| [getSubject](#getSubject--) | Obtient les informations du sujet du document PDF. |
| [getTitle](#getTitle--) | Obtient les informations du titre du document PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | Utilise des règles de validation strictes via la propriété {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Renvoie true si le fichier d'entrée actuel est un fichier « Portfolio » contenant une collection de fichiers PDF. |
| [hasEditPassword](#hasEditPassword--) | Renvoie true si un mot de passe est nécessaire pour modifier les permissions ou la propriété de sécurité du document. Notez que cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur {@code PdfFileInfo}. Dans le cas où PasswordType est Inaccessible (ce qui signifie qu'un mot de passe invalide a été fourni), la lecture de cette propriété échouera avec {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Renvoie true si un mot de passe est nécessaire pour ouvrir le document PDF protégé par mot de passe. |
| [isEncrypted](#isEncrypted--) | Vérifie si le document PDF est chiffré. |
| [isPdfFile](#isPdfFile--) | Vérifie si l'entrée source est un fichier PDF valide. |
| [save](#save-java.io.OutputStream-) | Enregistre le document PDF dans le fichier spécifié. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Enregistrer le document PDF mis à jour dans le flux spécifié. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Enregistrer le document PDF mis à jour dans le fichier spécifié. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Modifie les propriétés spécifiées explicitement en définissant les informations du fichier, les autres propriétés restent inchangées. |
| [setAuthor](#setAuthor-java.lang.String-) | Définit les informations d'auteur du document PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Définit les informations de date de création du document PDF. |
| [setCreator](#setCreator-java.lang.String-) | Définit les informations du créateur du document PDF. |
| [setHeader](#setHeader-java.util.Map-) | Définit les informations personnalisées du document PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Définit le fichier d'entrée. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Définit le flux d'entrée. |
| [setKeywords](#setKeywords-java.lang.String-) | Définit les mots‑clés du document PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Définit les informations personnalisées du document PDF. |
| [setModDate](#setModDate-java.lang.String-) | Définit les informations de date de modification du document PDF. |
| [setSubject](#setSubject-java.lang.String-) | Définit les informations de sujet du document PDF. |
| [setTitle](#setTitle-java.lang.String-) | Définit les informations de titre du document PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Utilise des règles de validation strictes via la propriété {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialise une nouvelle instance de la classe com.aspose.pdf.facades.PdfFileInfo avec les valeurs par défaut.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialise la façade.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Efface toutes les métadonnées du document PDF.

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Ferme toutes les ressources utilisées par cette instance. Cette méthode est obsolète, utilisez close() à la place.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtient les informations d'auteur du document PDF.

**Returns:**
valeur String

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Obtient les informations de CreationDate du document PDF.

**Returns:**
valeur String

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtient les informations du créateur du document PDF.

**Returns:**
valeur String

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Obtient les paramètres de privilèges du document PDF.

**Returns:**
Les paramètres de privilèges du document PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Obtient les informations personnalisées du document PDF. </p>

**Returns:**
{@code Map<String, String>} objet

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtient le fichier d'entrée.

**Returns:**
valeur String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Obtient le flux d'entrée.

**Returns:**
Objet InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtient les informations des mots‑clés du document PDF.

**Returns:**
valeur String

### getMetaInfo {#getMetaInfo-java.lang.String-}
Obtient les informations personnalisées du document PDF avec le nom de propriété. S'il n'existe aucune propriété correspondant au nom, cela renverra une chaîne vide.

### getModDate {#getModDate--}
```
public String getModDate()
```

Obtient les informations de date ModDate du document PDF.

**Returns:**
valeur String

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Obtient le nombre de pages du document.

**Returns:**
valeur int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Obtient la hauteur de la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNum |  | Numéro de page. |

**Returns:**
La hauteur de la page.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Obtient la rotation de la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNum |  | Numéro de page. |

**Returns:**
La rotation de la page. La valeur peut être 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Obtient la largeur de la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNum |  | Numéro de page. |

**Returns:**
La largeur de la page.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Obtient le décalage horizontal de la zone d'affichage de la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNum |  | Numéro de page. |

**Returns:**
Le décalage horizontal depuis le côté gauche de la page.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Obtient le décalage vertical de la zone d'affichage de la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNum |  | Numéro de page. |

**Returns:**
Le décalage vertical de la zone d'affichage de la page.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Renvoie le type de mot de passe qui a été fourni lors de la création de l'instance PdfFileInfo. Voir les valeurs possibles dans {@code PasswordType}. Notez que le document PDF peut être ouvert à l'aide à la fois du mot de passe utilisateur (ou d'ouverture) et du mot de passe propriétaire (ou de permissions, d'édition).

**Returns:**
élément PasswordType @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Obtient les informations de version du document PDF.

**Returns:**
La chaîne de version.

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtient les informations du producteur du document PDF.

**Returns:**
valeur String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtient les informations du sujet du document PDF.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient les informations du titre du document PDF.

**Returns:**
valeur String

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Utilise des règles de validation strictes via la propriété {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
valeur booléenne

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Renvoie true si le fichier d'entrée actuel est un fichier « Portfolio » contenant une collection de fichiers PDF.

**Returns:**
valeur booléenne

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Renvoie true si un mot de passe est nécessaire pour modifier les permissions ou la propriété de sécurité du document. Notez que cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur {@code PdfFileInfo}. Dans le cas où PasswordType est Inaccessible (ce qui signifie qu'un mot de passe invalide a été fourni), la lecture de cette propriété échouera avec {@code InvalidPasswordException}.

**Returns:**
valeur booléenne

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Renvoie true si un mot de passe est nécessaire pour ouvrir le document PDF protégé par mot de passe.

**Returns:**
valeur booléenne

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Vérifie si le document PDF est chiffré.

**Returns:**
valeur booléenne

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Vérifie si l'entrée source est un fichier PDF valide.

**Returns:**
valeur booléenne

### save {#save-java.io.OutputStream-}
Enregistre le document PDF dans le fichier spécifié.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Enregistrer le document PDF mis à jour dans le flux spécifié.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Enregistrer le document PDF mis à jour dans le fichier spécifié.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Modifie les propriétés spécifiées explicitement en définissant les informations du fichier, les autres propriétés restent inchangées.

### setAuthor {#setAuthor-java.lang.String-}
Définit les informations d'auteur du document PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
Définit les informations de date de création du document PDF.

### setCreator {#setCreator-java.lang.String-}
Définit les informations du créateur du document PDF.

### setHeader {#setHeader-java.util.Map-}
Définit les informations personnalisées du document PDF.

### setInputFile {#setInputFile-java.lang.String-}
Définit le fichier d'entrée.

### setInputStream {#setInputStream-java.io.InputStream-}
Définit le flux d'entrée.

### setKeywords {#setKeywords-java.lang.String-}
Définit les mots‑clés du document PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Définit les informations personnalisées du document PDF.

### setModDate {#setModDate-java.lang.String-}
Définit les informations de date de modification du document PDF.

### setSubject {#setSubject-java.lang.String-}
Définit les informations de sujet du document PDF.

### setTitle {#setTitle-java.lang.String-}
Définit les informations de titre du document PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Utilise des règles de validation strictes via la propriété {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
