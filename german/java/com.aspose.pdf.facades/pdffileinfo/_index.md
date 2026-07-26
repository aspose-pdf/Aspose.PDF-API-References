---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Zugriff auf Metainformationen eines PDF‑Dokuments dar."
type: docs
weight: 490
url: /de/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Stellt eine Klasse zum Zugriff auf Metainformationen eines PDF‑Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialisiert die Fassade. |
| [clearInfo](#clearInfo--) | Löscht alle Metainformationen des PDF-Dokuments. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [dispose](#dispose--) | Schließt alle von dieser Instanz verwendeten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getAuthor](#getAuthor--) | Liefert die Autor-Information des PDF-Dokuments. |
| [getCreationDate](#getCreationDate--) | Liefert die Erstellungsdatum-Information des PDF-Dokuments. |
| [getCreator](#getCreator--) | Liefert die Ersteller-Information des PDF-Dokuments. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Liefert die Berechtigungseinstellungen des PDF-Dokuments. |
| [getHeader](#getHeader--) | <p> Liefert die benutzerdefinierten Informationen des PDF-Dokuments. </p> |
| [getInputFile](#getInputFile--) | Liefert die Eingabedatei. |
| [getInputStream](#getInputStream--) | Liefert den Eingabestream. |
| [getKeywords](#getKeywords--) | Liefert die Schlüsselwort-Information des PDF-Dokuments. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Liefert benutzerdefinierte Informationen des PDF-Dokuments anhand des Eigenschaftsnamens. Wenn keine Eigenschaft mit dem Namen übereinstimmt, wird ein leerer String zurückgegeben. |
| [getModDate](#getModDate--) | Liefert die ModDate-Datum-Information des PDF-Dokuments. |
| [getNumberOfPages](#getNumberOfPages--) | Liefert die Anzahl der Dokumentseiten. |
| [getPageHeight](#getPageHeight-int-) | Liefert die Höhe der angegebenen Seite. |
| [getPageRotation](#getPageRotation-int-) | Liefert die Drehung der angegebenen Seite. |
| [getPageWidth](#getPageWidth-int-) | Liefert die Breite der angegebenen Seite. |
| [getPageXOffset](#getPageXOffset-int-) | Liefert den horizontalen Versatz des Anzeigebereichs der angegebenen Seite. |
| [getPageYOffset](#getPageYOffset-int-) | Liefert den vertikalen Versatz des Anzeigebereichs der angegebenen Seite. |
| [getPasswordType](#getPasswordType--) | Gibt den Typ des Passworts zurück, das beim Erstellen der PdfFileInfo‑Instanz übergeben wurde. Siehe mögliche Werte in {@code PasswordType}. Beachten Sie, dass das PDF‑Dokument sowohl mit dem Benutzer‑ (oder Öffnungs‑) Passwort als auch mit dem Besitzer‑ (oder Berechtigungs‑, Bearbeitungs‑) Passwort geöffnet werden kann. |
| [getPdfVersion](#getPdfVersion--) | Liefert die Versionsinformationen des PDF‑Dokuments. |
| [getProducer](#getProducer--) | Liefert die Produzenten‑Informationen des PDF‑Dokuments. |
| [getSubject](#getSubject--) | Liefert die Betreff‑Informationen des PDF‑Dokuments. |
| [getTitle](#getTitle--) | Liefert die Titel‑Informationen des PDF‑Dokuments. |
| [getUseStrictValidation](#getUseStrictValidation--) | Verwendet strenge Validierungsregeln über die {@code IsPdfFile}({@link #isPdfFile})‑Eigenschaft. |
| [hasCollection](#hasCollection--) | Gibt true zurück, wenn die aktuelle Eingabedatei eine ‚Portfolio‘‑Datei ist, die eine Sammlung von PDF‑Dateien enthält. |
| [hasEditPassword](#hasEditPassword--) | Gibt true zurück, wenn ein Passwort benötigt wird, um Berechtigungen oder die Sicherheitseigenschaft des Dokuments zu ändern. Beachten Sie, dass diese Eigenschaft nur gelesen werden kann, wenn im {@code PdfFileInfo}-Konstruktor ein gültiges Passwort übergeben wurde. Falls PasswordType auf Inaccessible gesetzt ist (bedeutet, dass ein ungültiges Passwort angegeben wurde), schlägt das Lesen dieser Eigenschaft mit {@code InvalidPasswordException} fehl. |
| [hasOpenPassword](#hasOpenPassword--) | Gibt true zurück, wenn ein Passwort zum Öffnen eines passwortgeschützten PDF‑Dokuments erforderlich ist. |
| [isEncrypted](#isEncrypted--) | Prüft, ob das PDF‑Dokument verschlüsselt ist. |
| [isPdfFile](#isPdfFile--) | Prüft, ob die Quell‑Eingabe eine gültige PDF‑Datei ist. |
| [save](#save-java.io.OutputStream-) | Speichert das PDF‑Dokument in die angegebene Datei. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Speichert das aktualisierte PDF‑Dokument in den angegebenen Stream. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Speichert das aktualisierte PDF‑Dokument in die angegebene Datei. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Ändert die explizit angegebenen Eigenschaften durch Setzen von Dateiinformationen, andere Eigenschaften bleiben erhalten. |
| [setAuthor](#setAuthor-java.lang.String-) | Setzt die Autor‑Informationen des PDF‑Dokuments. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Setzt die Erstellungsdatum‑Informationen des PDF‑Dokuments. |
| [setCreator](#setCreator-java.lang.String-) | Setzt die Ersteller‑Informationen des PDF‑Dokuments. |
| [setHeader](#setHeader-java.util.Map-) | Setzt die benutzerdefinierten Informationen des PDF‑Dokuments. |
| [setInputFile](#setInputFile-java.lang.String-) | Setzt die Eingabedatei. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Setzt den Eingabestream. |
| [setKeywords](#setKeywords-java.lang.String-) | Setzt die Schlüsselwort‑Informationen des PDF‑Dokuments. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Setzt benutzerdefinierte Informationen des PDF‑Dokuments. |
| [setModDate](#setModDate-java.lang.String-) | Setzt die ModDate‑Datumsinformationen des PDF‑Dokuments. |
| [setSubject](#setSubject-java.lang.String-) | Setzt die Betreff‑Informationen des PDF‑Dokuments. |
| [setTitle](#setTitle-java.lang.String-) | Setzt die Titelinformationen des PDF-Dokuments. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Verwendet strenge Validierungsregeln über die {@code IsPdfFile}({@link #isPdfFile})‑Eigenschaft. |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert eine neue Instanz der Klasse com.aspose.pdf.facades.PdfFileInfo mit Standardwerten.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialisiert die Fassade.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Löscht alle Metainformationen des PDF-Dokuments.

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Schließt alle von dieser Instanz verwendeten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Liefert die Autor-Information des PDF-Dokuments.

**Returns:**
String Wert

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Liefert die Erstellungsdatum-Information des PDF-Dokuments.

**Returns:**
String Wert

### getCreator {#getCreator--}
```
public String getCreator()
```

Liefert die Ersteller-Information des PDF-Dokuments.

**Returns:**
String Wert

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Liefert die Berechtigungseinstellungen des PDF-Dokuments.

**Returns:**
Die Berechtigungseinstellungen des PDF-Dokuments.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Liefert die benutzerdefinierten Informationen des PDF-Dokuments. </p>

**Returns:**
{@code Map<String, String>} Objekt

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Liefert die Eingabedatei.

**Returns:**
String Wert

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Liefert den Eingabestream.

**Returns:**
InputStream‑Objekt

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Liefert die Schlüsselwort-Information des PDF-Dokuments.

**Returns:**
String Wert

### getMetaInfo {#getMetaInfo-java.lang.String-}
Liefert benutzerdefinierte Informationen des PDF-Dokuments anhand des Eigenschaftsnamens. Wenn keine Eigenschaft mit dem Namen übereinstimmt, wird ein leerer String zurückgegeben.

### getModDate {#getModDate--}
```
public String getModDate()
```

Liefert die ModDate-Datum-Information des PDF-Dokuments.

**Returns:**
String Wert

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Liefert die Anzahl der Dokumentseiten.

**Returns:**
int-Wert

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Liefert die Höhe der angegebenen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNum |  | Seitennummer. |

**Returns:**
Die Höhe der Seite.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Liefert die Drehung der angegebenen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNum |  | Seitennummer. |

**Returns:**
Die Drehung der Seite. Der Wert kann 0,90,180,270 sein.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Liefert die Breite der angegebenen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNum |  | Seitennummer. |

**Returns:**
Die Breite der Seite.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Liefert den horizontalen Versatz des Anzeigebereichs der angegebenen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNum |  | Seitennummer. |

**Returns:**
Der horizontale Versatz von der linken Seite der Seite.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Liefert den vertikalen Versatz des Anzeigebereichs der angegebenen Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNum |  | Seitennummer. |

**Returns:**
Der vertikale Versatz des Anzeigeabschnitts der Seite.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Gibt den Typ des Passworts zurück, das beim Erstellen der PdfFileInfo‑Instanz übergeben wurde. Siehe mögliche Werte in {@code PasswordType}. Beachten Sie, dass das PDF‑Dokument sowohl mit dem Benutzer‑ (oder Öffnungs‑) Passwort als auch mit dem Besitzer‑ (oder Berechtigungs‑, Bearbeitungs‑) Passwort geöffnet werden kann.

**Returns:**
PasswordType-Element @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Liefert die Versionsinformationen des PDF‑Dokuments.

**Returns:**
Die Versionszeichenfolge.

### getProducer {#getProducer--}
```
public String getProducer()
```

Liefert die Produzenten‑Informationen des PDF‑Dokuments.

**Returns:**
String Wert

### getSubject {#getSubject--}
```
public String getSubject()
```

Liefert die Betreff‑Informationen des PDF‑Dokuments.

**Returns:**
String Wert

### getTitle {#getTitle--}
```
public String getTitle()
```

Liefert die Titel‑Informationen des PDF‑Dokuments.

**Returns:**
String Wert

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Verwendet strenge Validierungsregeln über die {@code IsPdfFile}({@link #isPdfFile})‑Eigenschaft.

**Returns:**
boolescher Wert

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Gibt true zurück, wenn die aktuelle Eingabedatei eine ‚Portfolio‘‑Datei ist, die eine Sammlung von PDF‑Dateien enthält.

**Returns:**
boolescher Wert

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Gibt true zurück, wenn ein Passwort benötigt wird, um Berechtigungen oder die Sicherheitseigenschaft des Dokuments zu ändern. Beachten Sie, dass diese Eigenschaft nur gelesen werden kann, wenn im {@code PdfFileInfo}-Konstruktor ein gültiges Passwort übergeben wurde. Falls PasswordType auf Inaccessible gesetzt ist (bedeutet, dass ein ungültiges Passwort angegeben wurde), schlägt das Lesen dieser Eigenschaft mit {@code InvalidPasswordException} fehl.

**Returns:**
boolescher Wert

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Gibt true zurück, wenn ein Passwort zum Öffnen eines passwortgeschützten PDF‑Dokuments erforderlich ist.

**Returns:**
boolescher Wert

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Prüft, ob das PDF‑Dokument verschlüsselt ist.

**Returns:**
boolescher Wert

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Prüft, ob die Quell‑Eingabe eine gültige PDF‑Datei ist.

**Returns:**
boolescher Wert

### save {#save-java.io.OutputStream-}
Speichert das PDF‑Dokument in die angegebene Datei.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Speichert das aktualisierte PDF‑Dokument in den angegebenen Stream.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Speichert das aktualisierte PDF‑Dokument in die angegebene Datei.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Ändert die explizit angegebenen Eigenschaften durch Setzen von Dateiinformationen, andere Eigenschaften bleiben erhalten.

### setAuthor {#setAuthor-java.lang.String-}
Setzt die Autor‑Informationen des PDF‑Dokuments.

### setCreationDate {#setCreationDate-java.lang.String-}
Setzt die Erstellungsdatum‑Informationen des PDF‑Dokuments.

### setCreator {#setCreator-java.lang.String-}
Setzt die Ersteller‑Informationen des PDF‑Dokuments.

### setHeader {#setHeader-java.util.Map-}
Setzt die benutzerdefinierten Informationen des PDF‑Dokuments.

### setInputFile {#setInputFile-java.lang.String-}
Setzt die Eingabedatei.

### setInputStream {#setInputStream-java.io.InputStream-}
Setzt den Eingabestream.

### setKeywords {#setKeywords-java.lang.String-}
Setzt die Schlüsselwort‑Informationen des PDF‑Dokuments.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Setzt benutzerdefinierte Informationen des PDF‑Dokuments.

### setModDate {#setModDate-java.lang.String-}
Setzt die ModDate‑Datumsinformationen des PDF‑Dokuments.

### setSubject {#setSubject-java.lang.String-}
Setzt die Betreff‑Informationen des PDF‑Dokuments.

### setTitle {#setTitle-java.lang.String-}
Setzt die Titelinformationen des PDF-Dokuments.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Verwendet strenge Validierungsregeln über die {@code IsPdfFile}({@link #isPdfFile})‑Eigenschaft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
