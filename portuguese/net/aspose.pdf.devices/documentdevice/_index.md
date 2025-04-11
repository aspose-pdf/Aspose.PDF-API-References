---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DocumentDevice. Classe abstrata para todos os dispositivos que são usados para processar o documento PDF inteiro
type: docs
weight: 3570
url: /pt/net/aspose.pdf.devices/documentdevice/
---
## Classe DocumentDevice

Classe abstrata para todos os dispositivos que são usados para processar o documento PDF inteiro.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Processa o documento inteiro e salva os resultados no stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Processa o documento inteiro e salva os resultados no arquivo. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Realiza alguma operação na página dada, por exemplo, converte a página em uma imagem gráfica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Cada dispositivo representa alguma operação no documento, por exemplo, podemos converter o documento PDF em outro formato. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Processa certas páginas do documento e salva os resultados no arquivo. |

### Veja Também

* classe [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)