---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine API für Bereinigung und Wiederherstellung dar. Verwenden Sie sie, wenn Sie Dokumente nicht auf andere Weise erstellen/öffnen können."
type: docs
weight: 510
url: /de/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Stellt eine API für Bereinigung und Wiederherstellung dar. Verwenden Sie sie, wenn Sie Dokumente nicht auf andere Weise erstellen/öffnen können.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Initialisiert eine neue Instanz. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Bindet einen PDF-Stream zum Bereinigen. |
| [bindPdf](#bindPdf-java.lang.String-) | Bindet eine PDF-Datei zum Bereinigen. |
| [close](#close--) | Schließt die Fassade. |
| [getLog](#getLog--) | Nachdem die Datei gespeichert wurde, können Sie prüfen, was mit der Datei geschehen ist. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Ermöglicht das Erzeugen eines neuen xref und Trailers für das Dokument. |
| [getUseTrimBottom](#getUseTrimBottom--) | Ermöglicht das Entfernen von Daten nach den PDF-Daten. |
| [getUseTrimTop](#getUseTrimTop--) | Ermöglicht das Entfernen von Daten vor den PDF-Daten. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Entfernt das alte xref mit Trailer und erstellt ein neues xref mit Trailer. |
| [recover](#recover--) | Stellt das Dokument wieder her. Verwenden Sie Eigenschaften zur Anpassung. |
| [save](#save-java.io.OutputStream-) | Speichert das Ergebnis-PDF in einen Stream. |
| [save](#save-java.lang.String-) | Speichert das Ergebnis-PDF in einer Datei. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Ermöglicht das Erzeugen eines neuen xref und Trailers für das Dokument. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Ermöglicht das Entfernen von Daten nach den PDF-Daten. |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Ermöglicht das Entfernen von Daten vor den PDF-Daten. |
| [trimBottom](#trimBottom--) | Entfernt Daten nach dem letzten %%EOF. |
| [trimTop](#trimTop--) | Entfernt Daten vor %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Initialisiert eine neue Instanz.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.io.InputStream-}
Bindet einen PDF-Stream zum Bereinigen.

### bindPdf {#bindPdf-java.lang.String-}
Bindet eine PDF-Datei zum Bereinigen.

### close {#close--}
```
public void close()
```

Schließt die Fassade.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Nachdem die Datei gespeichert wurde, können Sie prüfen, was mit der Datei geschehen ist.

**Returns:**
Liste von String-Elementen

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Ermöglicht das Erzeugen eines neuen xref und Trailers für das Dokument.

**Returns:**
boolescher Wert

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Ermöglicht das Entfernen von Daten nach den PDF-Daten.

**Returns:**
boolescher Wert

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Ermöglicht das Entfernen von Daten vor den PDF-Daten.

**Returns:**
boolescher Wert

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Entfernt das alte xref mit Trailer und erstellt ein neues xref mit Trailer.

### recover {#recover--}
```
public final void recover()
```

Stellt das Dokument wieder her. Verwenden Sie Eigenschaften zur Anpassung.

### save {#save-java.io.OutputStream-}
Speichert das Ergebnis-PDF in einen Stream.

### save {#save-java.lang.String-}
Speichert das Ergebnis-PDF in einer Datei.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Ermöglicht das Erzeugen eines neuen xref und Trailers für das Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Ermöglicht das Entfernen von Daten nach den PDF-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Ermöglicht das Entfernen von Daten vor den PDF-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Entfernt Daten nach dem letzten %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Entfernt Daten vor %PDF.
