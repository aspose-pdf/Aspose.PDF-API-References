---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um dispositivo de imagem que ajuda a salvar páginas de documentos pdf em bmp."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Representa um dispositivo de imagem que ajuda a salvar páginas de documentos pdf em bmp.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão. |
| [BmpDevice](#BmpDevice-int-int-) | Inicializa uma nova instância da classe {@code BmpDevice} com dimensões de imagem fornecidas, resolução padrão (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renderiza a página nos gráficos |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte a página para bmp e a salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Somente para uso interno! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Inicializa uma nova instância da classe {@code BmpDevice} com dimensões de imagem fornecidas, resolução padrão (=150).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem. |
| altura |  | Altura de saída da imagem. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code BmpDevice} com resolução padrão.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
renderiza a página nos gráficos

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte a página para bmp e a salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Somente para uso interno!
