---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper-Methode. Erstellen und zurückgeben eines Dokuments mit dem Dateinamen. Dasselbe wie Dokument
type: docs
weight: 20
url: /de/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Erstellen und zurückgeben eines Dokuments mit *Dateinamen*. Dasselbe wie [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Name der PDF-Dokumentdatei. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Initialisieren und zurückgeben einer neuen Instanz der [`Document`](../../document/) Klasse zum Arbeiten mit verschlüsselten Dokumenten.

```csharp
public Document OpenFile(string filename, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Dokumentdateiname. |
| password | String | Benutzer- oder Eigentümerpasswort. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Initialisieren einer neuen Instanz der [`Document`](../../document/) Klasse zum Arbeiten mit verschlüsselten Dokumenten.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Dokumentdateiname. |
| password | String | Benutzer- oder Eigentümerpasswort. |
| isManagedStream | Boolean | Wenn auf `true` gesetzt, wird der innere Stream vor dem Verlassen geschlossen; andernfalls nicht. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Öffnen eines vorhandenen Dokuments aus einer Datei, die notwendige Konvertierungsoptionen bereitstellt, um ein PDF-Dokument zu erhalten.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Eingabedatei zur Konvertierung in ein PDF-Dokument. |
| options | LoadOptions | Stellt Eigenschaften für die Konvertierung von *filename* in ein PDF-Dokument dar. |

### Rückgabewert

Dokumentenobjekt

### Siehe auch

* Klasse [Document](../../document/)
* Klasse [LoadOptions](../../loadoptions/)
* Klasse [ComHelper](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)