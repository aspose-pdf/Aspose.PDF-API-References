---
title: Process
second_title: Aspose.PDF för .NET API Referens
description: Varje enhet representerar en operation på dokumentet t.ex. kan vi konvertera pdf-dokument till ett annat format.
type: docs
weight: 20
url: /sv/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Varje enhet representerar en operation på dokumentet, t.ex. kan vi konvertera pdf-dokument till ett annat format.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska behandlas. |
| fromPage | Int32 | Definierar sidan från vilken bearbetningen ska börja. |
| toPage | Int32 | Definierar den sista sidan som ska bearbetas. |
| output | Stream | Definierar ström där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* namnutrymme [Aspose.Pdf.Devices](../../documentdevice)
* hopsättning [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Bearbetar hela dokumentet och sparar resultat i stream.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska behandlas. |
| output | Stream | Definierar ström där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* namnutrymme [Aspose.Pdf.Devices](../../documentdevice)
* hopsättning [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Bearbetar hela dokumentet och sparar resultat i fil.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska behandlas. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* namnutrymme [Aspose.Pdf.Devices](../../documentdevice)
* hopsättning [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Bearbetar vissa sidor i dokumentet och sparar resultat i fil.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Document | Dokumentet som ska behandlas. |
| fromPage | Int32 | Den första sidan att börja bearbeta. |
| toPage | Int32 | Den sista sidan av bearbetningen. |
| outputFileName | String | Definierar filen där resultaten av bearbetningen lagras. |

### Se även

* class [Document](../../../aspose.pdf/document)
* class [DocumentDevice](../../documentdevice)
* namnutrymme [Aspose.Pdf.Devices](../../documentdevice)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->