---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice-metod. Varje enhet representerar någon operation på dokumentet, t.ex. vi kan konvertera pdf-dokument till ett annat format
type: docs
weight: 10
url: /sv/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Varje enhet representerar någon operation på dokumentet, t.ex. vi kan konvertera pdf-dokument till ett annat format.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska bearbetas. |
| fromPage | Int32 | Definierar sidan från vilken bearbetning ska börja. |
| toPage | Int32 | Definierar den sista sidan som ska bearbetas. |
| output | Stream | Definierar strömmen där resultaten av bearbetningen lagras. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [DocumentDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Bearbetar hela dokumentet och sparar resultaten i strömmen.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska bearbetas. |
| output | Stream | Definierar strömmen där resultaten av bearbetningen lagras. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [DocumentDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Bearbetar hela dokumentet och sparar resultaten i filen.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska bearbetas. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [DocumentDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Bearbetar vissa sidor av dokumentet och sparar resultaten i filen.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska bearbetas. |
| fromPage | Int32 | Den första sidan att börja bearbeta. |
| toPage | Int32 | Den sista sidan av bearbetningen. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [DocumentDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)