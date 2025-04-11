---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice metodu. Her cihaz, belgede bazı işlemleri temsil eder; örneğin, pdf belgesini başka bir formata dönüştürebiliriz.
type: docs
weight: 10
url: /tr/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Her cihaz, belgede bazı işlemleri temsil eder; örneğin, pdf belgesini başka bir formata dönüştürebiliriz.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | İşlenecek belge. |
| fromPage | Int32 | İşlemeye başlanacak sayfayı tanımlar. |
| toPage | Int32 | İşlenecek son sayfayı tanımlar. |
| output | Stream | İşlemenin sonuçlarının saklandığı akışı tanımlar. |

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Tüm belgeyi işler ve sonuçları akışa kaydeder.

```csharp
public void Process(Document document, Stream output)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | İşlenecek belge. |
| output | Stream | İşlemenin sonuçlarının saklandığı akışı tanımlar. |

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Tüm belgeyi işler ve sonuçları dosyaya kaydeder.

```csharp
public void Process(Document document, string outputFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | İşlenecek belge. |
| outputFileName | String | İşlemenin sonuçlarının saklandığı dosyayı tanımlar. |

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Belgenin belirli sayfalarını işler ve sonuçları dosyaya kaydeder.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | İşlenecek belge. |
| fromPage | Int32 | İşlemeye başlanacak ilk sayfa. |
| toPage | Int32 | İşlemenin son sayfası. |
| outputFileName | String | İşlemenin sonuçlarının saklandığı dosyayı tanımlar. |

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)