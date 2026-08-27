---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em png."
type: docs
weight: 160
url: /pt/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em png.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PngDevice](#PngDevice--) | Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão. |
| [PngDevice](#PngDevice-int-int-) | Inicializa uma nova instância da classe {@code PngDevice} com dimensões de imagem fornecidas, resolução padrão (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Obtém ou define se a imagem tem fundo transparente. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte a página para png e a salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte a página para png e a salva no fluxo de saída. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Converte a página em BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Converte a página em BufferedImage com binarização Bradley. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Obtém ou define se a imagem tem fundo transparente. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Inicializa uma nova instância da classe {@code PngDevice} com dimensões de imagem fornecidas, resolução padrão (=150).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem. |
| altura |  | Altura de saída da imagem. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code PngDevice} com resolução padrão.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Obtém ou define se a imagem tem fundo transparente.

**Returns:**
valor booleano

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte a página para png e a salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte a página para png e a salva no fluxo de saída.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Converte a página em BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Converte a página em BufferedImage com binarização Bradley.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Obtém ou define se a imagem tem fundo transparente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
