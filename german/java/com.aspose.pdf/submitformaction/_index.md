---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die die Aktion submit-form beschreibt."
type: docs
weight: 4690
url: /de/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Klasse, die die Aktion submit-form beschreibt.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Falls gesetzt, werden alle übermittelten Feldwerte, die Daten darstellen, in das Standardformat konvertiert. |
| [EMBED_FORM](#EMBED_FORM) | Falls gesetzt, ist der F‑Eintrag des übermittelten FDF eine Dateispezifikation, die einen eingebetteten Dateistream enthält, der die PDF‑Datei repräsentiert, aus der das FDF übermittelt wird. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Falls gesetzt, schließt das übermittelte FDF den F‑Eintrag aus. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Falls gesetzt, werden nur jene Markup‑Annotationen einbezogen, deren T‑Eintrag mit dem Namen des aktuellen Benutzers übereinstimmt. |
| [EXCLUDE](#EXCLUDE) | Falls nicht gesetzt, gibt das Fields‑Array an, welche Felder in die Übermittlung aufgenommen werden sollen. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Falls gesetzt, werden Feldnamen und -werte im HTML‑Formularformat übermittelt. |
| [GET_METHOD](#GET_METHOD) | Falls gesetzt, werden Feldnamen und -werte mittels einer HTTP‑GET‑Anfrage übermittelt. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Falls gesetzt, enthält die übermittelte FDF‑Datei alle Markup‑Annotationen im zugrunde liegenden PDF‑Dokument. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Falls gesetzt, enthält die übermittelte FDF‑Datei den Inhalt aller inkrementellen Updates. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Falls gesetzt, werden alle durch das Fields‑Array und das Include/Exclude‑Flag bezeichneten Felder übermittelt. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Falls gesetzt, werden die Koordinaten des Mausklicks, der die Submit‑Form‑Aktion ausgelöst hat, als Teil der Formulardaten übertragen. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Falls gesetzt, wird das Dokument als PDF übermittelt, wobei der MIME‑Inhaltstyp application/pdf verwendet wird. |
| [XFDF](#XFDF) | Falls gesetzt, werden Feldnamen und -werte als XFDF übermittelt. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Initialisiert das SubmitFormAction‑Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFlags](#getFlags--) | Liest die Flags der Submit‑Aktion. |
| [getUrl](#getUrl--) | Ziel‑URL. |
| [setFlags](#setFlags-int-) | Setzt die Flags der Submit‑Aktion. |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | Ziel‑URL. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Falls gesetzt, werden alle übermittelten Feldwerte, die Daten darstellen, in das Standardformat konvertiert.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Falls gesetzt, ist der F‑Eintrag des übermittelten FDF eine Dateispezifikation, die einen eingebetteten Dateistream enthält, der die PDF‑Datei repräsentiert, aus der das FDF übermittelt wird.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Falls gesetzt, schließt das übermittelte FDF den F‑Eintrag aus.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Falls gesetzt, werden nur jene Markup‑Annotationen einbezogen, deren T‑Eintrag mit dem Namen des aktuellen Benutzers übereinstimmt.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Falls nicht gesetzt, gibt das Fields‑Array an, welche Felder in die Übermittlung aufgenommen werden sollen.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Falls gesetzt, werden Feldnamen und -werte im HTML‑Formularformat übermittelt.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Falls gesetzt, werden Feldnamen und -werte mittels einer HTTP‑GET‑Anfrage übermittelt.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Falls gesetzt, enthält die übermittelte FDF‑Datei alle Markup‑Annotationen im zugrunde liegenden PDF‑Dokument.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Falls gesetzt, enthält die übermittelte FDF‑Datei den Inhalt aller inkrementellen Updates.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Falls gesetzt, werden alle durch das Fields‑Array und das Include/Exclude‑Flag bezeichneten Felder übermittelt.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Falls gesetzt, werden die Koordinaten des Mausklicks, der die Submit‑Form‑Aktion ausgelöst hat, als Teil der Formulardaten übertragen.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Falls gesetzt, wird das Dokument als PDF übermittelt, wobei der MIME‑Inhaltstyp application/pdf verwendet wird.

### XFDF {#XFDF}
```
public static final int XFDF
```

Falls gesetzt, werden Feldnamen und -werte als XFDF übermittelt.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Initialisiert das SubmitFormAction‑Objekt.

### getFlags {#getFlags--}
```
public int getFlags()
```

Liest die Flags der Submit‑Aktion.

**Returns:**
int-Wert

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

Ziel‑URL.

**Returns:**
FileSpecification-Wert

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Setzt die Flags der Submit‑Aktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
Ziel‑URL.
