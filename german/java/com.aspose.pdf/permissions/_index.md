---
title: "Berechtigungen"
linktitle: "Berechtigungen"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Binäres Flag. Diese Aufzählung stellt die Benutzerberechtigungen für ein PDF dar."
type: docs
weight: 3830
url: /de/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Binäres Flag. Diese Aufzählung stellt die Benutzerberechtigungen für ein PDF dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Security handlers of revision 3 or greater) Dokument zusammenstellen (einfügen, drehen oder Seiten löschen und Lesezeichen oder Miniaturbilder erstellen), selbst wenn {@code ModifyContent} nicht gesetzt ist. |
| [ExtractContent](#ExtractContent) | (Security handlers of revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken). (Security handlers of revision 3 or greater) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren durch Vorgänge, die nicht von {@code ExtractContentWithDisabilities} gesteuert werden. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Security handlers of revision 3 or greater) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken). |
| [FillForm](#FillForm) | (Security handlers of revision 3 or greater) Vorhandene interaktive Formularfelder ausfüllen (einschließlich Signaturfelder), selbst wenn {@code ModifyTextAnnotations} nicht gesetzt ist. |
| [ModifyContent](#ModifyContent) | Den Inhalt des Dokuments durch Vorgänge ändern, die nicht von {@code ModifyTextAnnotations}, {@code FillForm} und 11 gesteuert werden. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, wenn {@code ModifyContent} ebenfalls gesetzt ist, interaktive Formularfelder erstellen oder ändern (einschließlich Signaturfelder). |
| [PrintDocument](#PrintDocument) | (Security handlers of revision 2) Dokument drucken. (Security handlers of revision 3 or greater) Dokument drucken (möglicherweise nicht in höchster Qualitätsstufe, abhängig davon, ob {@code PrintingQuality} ebenfalls gesetzt ist). |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) Drucken Sie das Dokument in eine Darstellung, aus der eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Wenn dieses Bit gelöscht ist (und Bit 3 gesetzt ist), ist das Drucken auf eine Low-Level-Darstellung des Aussehens beschränkt, möglicherweise von verminderter Qualität. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Security handlers of revision 3 or greater) Dokument zusammenstellen (einfügen, drehen oder Seiten löschen und Lesezeichen oder Miniaturbilder erstellen), selbst wenn {@code ModifyContent} nicht gesetzt ist.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Security handlers of revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken). (Security handlers of revision 3 or greater) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren durch Vorgänge, die nicht von {@code ExtractContentWithDisabilities} gesteuert werden.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Security handlers of revision 3 or greater) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Security handlers of revision 3 or greater) Vorhandene interaktive Formularfelder ausfüllen (einschließlich Signaturfelder), selbst wenn {@code ModifyTextAnnotations} nicht gesetzt ist.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Den Inhalt des Dokuments durch Vorgänge ändern, die nicht von {@code ModifyTextAnnotations}, {@code FillForm} und 11 gesteuert werden.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, wenn {@code ModifyContent} ebenfalls gesetzt ist, interaktive Formularfelder erstellen oder ändern (einschließlich Signaturfelder).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Security handlers of revision 2) Dokument drucken. (Security handlers of revision 3 or greater) Dokument drucken (möglicherweise nicht in höchster Qualitätsstufe, abhängig davon, ob {@code PrintingQuality} ebenfalls gesetzt ist).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Security handlers of revision 3 or greater) Drucken Sie das Dokument in eine Darstellung, aus der eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Wenn dieses Bit gelöscht ist (und Bit 3 gesetzt ist), ist das Drucken auf eine Low-Level-Darstellung des Aussehens beschränkt, möglicherweise von verminderter Qualität.
