---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Método DocumentDevice. Cada dispositivo representa alguma operação no documento, por exemplo, podemos converter um documento pdf em outro formato
type: docs
weight: 10
url: /pt/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Cada dispositivo representa alguma operação no documento, por exemplo, podemos converter um documento pdf em outro formato.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | O documento a ser processado. |
| fromPage | Int32 | Define a página a partir da qual iniciar o processamento. |
| toPage | Int32 | Define a última página a ser processada. |
| output | Stream | Define o stream onde os resultados do processamento são armazenados. |

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Processa o documento inteiro e salva os resultados em um stream.

```csharp
public void Process(Document document, Stream output)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | O documento a ser processado. |
| output | Stream | Define o stream onde os resultados do processamento são armazenados. |

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Processa o documento inteiro e salva os resultados em um arquivo.

```csharp
public void Process(Document document, string outputFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | O documento a ser processado. |
| outputFileName | String | Define o arquivo onde os resultados do processamento são armazenados. |

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Processa certas páginas do documento e salva os resultados em um arquivo.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | O documento a ser processado. |
| fromPage | Int32 | A primeira página a iniciar o processamento. |
| toPage | Int32 | A última página do processamento. |
| outputFileName | String | Define o arquivo onde os resultados do processamento são armazenados. |

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)