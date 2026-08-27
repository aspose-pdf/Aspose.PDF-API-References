---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em jpeg."
type: docs
weight: 130
url: /pt/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em jpeg.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-int-) | Inicializa uma nova instância da classe {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | Inicializa uma nova instância da classe {@code JpegDevice} com dimensões de imagem fornecidas, resolução padrão (=150) e qualidade máxima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima. |

## Métodos

| Método | Descrição |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte a página em jpeg e a salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte a página em jpeg e a salva no fluxo de saída. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Inicializa uma nova instância da classe {@code JpegDevice}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| qualidade |  | Especifica o nível de compressão de uma imagem. A faixa de valores úteis para a qualidade vai de 0 a 100. Quanto menor o número especificado, maior a compressão e, portanto, menor a qualidade da imagem. Zero resultaria na imagem de menor qualidade e 100 na de maior qualidade. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Inicializa uma nova instância da classe {@code JpegDevice} com dimensões de imagem fornecidas, resolução padrão (=150) e qualidade máxima.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem. |
| altura |  | Altura de saída da imagem. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Inicializa uma nova instância da classe {@code JpegDevice} com resolução padrão e qualidade máxima.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte a página em jpeg e a salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte a página em jpeg e a salva no fluxo de saída.
