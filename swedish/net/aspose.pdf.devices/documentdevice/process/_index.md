---
title: "DocumentDevice.Process"
second_title: "Aspose.PDF för .NET API‑referens"
description: "DocumentDevice-metod. Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokument till ett annat format."
type: docs
weight: 10
url: /sv/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokument till ett annat format.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Dokumentet som ska bearbetas. |
| fromPage | Int32 | Definierar sidan från vilken bearbetning ska startas. |
| toPage | Int32 | Definierar den sista sidan som ska bearbetas. |
| utdata | Stream | Definierar strömmen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Bearbetar hela dokumentet och sparar resultatet i en ström.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Dokumentet som ska bearbetas. |
| utdata | Stream | Definierar strömmen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Bearbetar hela dokumentet och sparar resultatet i en fil.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Dokumentet som ska bearbetas. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Dokumentet som ska bearbetas. |
| fromPage | Int32 | Den första sidan att starta bearbetning på. |
| toPage | Int32 | Den sista sidan av bearbetning. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


