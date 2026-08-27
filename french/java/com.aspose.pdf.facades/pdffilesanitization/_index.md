---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'API de désinfection et de récupération. Utilisez‑la si vous ne pouvez pas créer/ouvrir les documents d'une autre manière."
type: docs
weight: 510
url: /fr/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Représente l'API de désinfection et de récupération. Utilisez‑la si vous ne pouvez pas créer/ouvrir les documents d'une autre manière.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Initialise une nouvelle instance. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Lie un flux Pdf pour la désinfection. |
| [bindPdf](#bindPdf-java.lang.String-) | Lie un fichier Pdf pour la désinfection. |
| [close](#close--) | Ferme la façade. |
| [getLog](#getLog--) | Après que le fichier a été enregistré, vous pouvez vérifier ce qui a été fait avec le fichier. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Permet de générer un nouveau xref et un nouveau trailer pour le document. |
| [getUseTrimBottom](#getUseTrimBottom--) | Permet de supprimer les données après les données pdf |
| [getUseTrimTop](#getUseTrimTop--) | Permet de supprimer les données avant les données pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Supprime l'ancien xref avec le trailer et crée un nouveau xref avec le trailer. |
| [recover](#recover--) | Récupère le document. Utilisez les propriétés pour personnaliser. |
| [save](#save-java.io.OutputStream-) | Enregistre le PDF résultant dans le flux. |
| [save](#save-java.lang.String-) | Enregistre le PDF résultant dans un fichier. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Permet de générer un nouveau xref et un nouveau trailer pour le document. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Permet de supprimer les données après les données pdf |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Permet de supprimer les données avant les données pdf. |
| [trimBottom](#trimBottom--) | Supprime les données après le dernier %%EOF. |
| [trimTop](#trimTop--) | Supprime les données avant %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Initialise une nouvelle instance.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Initialise la façade.

### bindPdf {#bindPdf-java.io.InputStream-}
Lie un flux Pdf pour la désinfection.

### bindPdf {#bindPdf-java.lang.String-}
Lie un fichier Pdf pour la désinfection.

### close {#close--}
```
public void close()
```

Ferme la façade.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Après que le fichier a été enregistré, vous pouvez vérifier ce qui a été fait avec le fichier.

**Returns:**
liste d'éléments String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Permet de générer un nouveau xref et un nouveau trailer pour le document.

**Returns:**
valeur booléenne

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Permet de supprimer les données après les données pdf

**Returns:**
valeur booléenne

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Permet de supprimer les données avant les données pdf.

**Returns:**
valeur booléenne

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Supprime l'ancien xref avec le trailer et crée un nouveau xref avec le trailer.

### recover {#recover--}
```
public final void recover()
```

Récupère le document. Utilisez les propriétés pour personnaliser.

### save {#save-java.io.OutputStream-}
Enregistre le PDF résultant dans le flux.

### save {#save-java.lang.String-}
Enregistre le PDF résultant dans un fichier.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Permet de générer un nouveau xref et un nouveau trailer pour le document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Permet de supprimer les données après les données pdf

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Permet de supprimer les données avant les données pdf.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Supprime les données après le dernier %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Supprime les données avant %PDF.
