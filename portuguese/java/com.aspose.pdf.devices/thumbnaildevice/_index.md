---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um dispositivo de imagem que salva as páginas do documento pdf em imagem em miniatura."
type: docs
weight: 200
url: /pt/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Representa um dispositivo de imagem que salva as páginas do documento pdf em imagem em miniatura.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Inicializa uma nova instância da classe {@link ThumbnailDevice} com tamanho padrão da imagem miniatura (200x200 pixels). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Inicializa uma nova instância da classe {@link ThumbnailDevice}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Converte a página para imagem miniatura png e a salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Executa alguma operação na página fornecida, por exemplo. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Inicializa uma nova instância da classe {@link ThumbnailDevice} com tamanho padrão da imagem miniatura (200x200 pixels).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Inicializa uma nova instância da classe {@link ThumbnailDevice}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem miniatura. |
| altura |  | Altura de saída da imagem miniatura. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Converte a página para imagem miniatura png e a salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Executa alguma operação na página fornecida, por exemplo.
