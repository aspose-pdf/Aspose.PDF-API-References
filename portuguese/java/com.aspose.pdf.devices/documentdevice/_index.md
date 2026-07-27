---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe abstrata para todos os dispositivos que são usados para processar todo o documento pdf."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Classe abstrata para todos os dispositivos que são usados para processar todo o documento pdf.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Cada dispositivo representa alguma operação no documento, por exemplo, podemos converter o documento pdf em outro formato. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Processa determinadas páginas do documento e salva os resultados em um arquivo. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Processa todo o documento e salva os resultados em um fluxo. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Processa todo o documento e salva os resultados em um arquivo. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Cada dispositivo representa alguma operação no documento, por exemplo. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Processa todo o documento e salva os resultados em um fluxo. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Cada dispositivo representa alguma operação no documento, por exemplo, podemos converter o documento pdf em outro formato.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Processa determinadas páginas do documento e salva os resultados em um arquivo.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Processa todo o documento e salva os resultados em um fluxo.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Processa todo o documento e salva os resultados em um arquivo.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Cada dispositivo representa alguma operação no documento, por exemplo.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Processa todo o documento e salva os resultados em um fluxo.
