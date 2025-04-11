---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Metodo DocumentDevice. Ogni dispositivo rappresenta un'operazione sul documento, ad esempio possiamo convertire un documento pdf in un altro formato
type: docs
weight: 10
url: /it/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Ogni dispositivo rappresenta un'operazione sul documento, ad esempio possiamo convertire un documento pdf in un altro formato.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Il documento da elaborare. |
| fromPage | Int32 | Definisce la pagina da cui iniziare l'elaborazione. |
| toPage | Int32 | Definisce l'ultima pagina da elaborare. |
| output | Stream | Definisce lo stream in cui vengono memorizzati i risultati dell'elaborazione. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Elabora l'intero documento e salva i risultati nello stream.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Il documento da elaborare. |
| output | Stream | Definisce lo stream in cui vengono memorizzati i risultati dell'elaborazione. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Elabora l'intero documento e salva i risultati in un file.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Il documento da elaborare. |
| outputFileName | String | Definisce il file in cui vengono memorizzati i risultati dell'elaborazione. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Elabora determinate pagine del documento e salva i risultati in un file.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Il documento da elaborare. |
| fromPage | Int32 | La prima pagina da iniziare a elaborare. |
| toPage | Int32 | L'ultima pagina dell'elaborazione. |
| outputFileName | String | Definisce il file in cui vengono memorizzati i risultati dell'elaborazione. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)