---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice-Methode. Jedes Gerät stellt eine Operation auf dem Dokument dar, z.B. können wir ein PDF-Dokument in ein anderes Format konvertieren.
type: docs
weight: 10
url: /de/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Jedes Gerät stellt eine Operation auf dem Dokument dar, z.B. können wir ein PDF-Dokument in ein anderes Format konvertieren.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Das zu verarbeitende Dokument. |
| fromPage | Int32 | Definiert die Seite, von der die Verarbeitung gestartet werden soll. |
| toPage | Int32 | Definiert die letzte Seite, die verarbeitet werden soll. |
| output | Stream | Definiert den Stream, in dem die Ergebnisse der Verarbeitung gespeichert werden. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [DocumentDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Verarbeitet das gesamte Dokument und speichert die Ergebnisse im Stream.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Das zu verarbeitende Dokument. |
| output | Stream | Definiert den Stream, in dem die Ergebnisse der Verarbeitung gespeichert werden. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [DocumentDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einer Datei.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Das zu verarbeitende Dokument. |
| outputFileName | String | Definiert die Datei, in der die Ergebnisse der Verarbeitung gespeichert werden. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [DocumentDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Verarbeitet bestimmte Seiten des Dokuments und speichert die Ergebnisse in einer Datei.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Das zu verarbeitende Dokument. |
| fromPage | Int32 | Die erste Seite, von der die Verarbeitung gestartet werden soll. |
| toPage | Int32 | Die letzte Seite der Verarbeitung. |
| outputFileName | String | Definiert die Datei, in der die Ergebnisse der Verarbeitung gespeichert werden. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [DocumentDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)