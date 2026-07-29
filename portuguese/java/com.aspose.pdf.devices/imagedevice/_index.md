---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe abstrata para dispositivos de imagem."
type: docs
weight: 110
url: /pt/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Uma classe abstrata para dispositivos de imagem.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Inicializa uma nova instância da classe {@code JpegDevice} com as dimensões de imagem fornecidas e resolução padrão (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Converte a página em {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [getCropRectangle](#getCropRectangle--) | Obtém o retângulo que define a área que será convertida em uma imagem. O padrão é null, caso em que a página inteira é convertida em imagem. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtém o modo de apresentação do formulário. |
| [getHeight](#getHeight--) | Obtém a altura de saída da imagem. |
| [getRenderingOptions](#getRenderingOptions--) | Obtém as opções de renderização. |
| [getResolution](#getResolution--) | Obtém a resolução da imagem. |
| [getWidth](#getWidth--) | Obtém a largura de saída da imagem. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Indica se o desempenho dos processos de sombreamento é alto. Por padrão, é verdadeiro. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Define o retângulo que delimita a área que será convertida em uma imagem. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Define o modo de apresentação do formulário. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Define as opções de renderização. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Define se o desempenho dos processos de sombreamento é alto ou não. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Inicializa uma nova instância da classe {@code JpegDevice} com as dimensões de imagem fornecidas e resolução padrão (=150).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem. |
| altura |  | Altura de saída da imagem. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Inicializador abstrato para descendentes de {@code ImageDevice}, define a resolução para 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Converte a página em {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtém o retângulo que define a área que será convertida em uma imagem. O padrão é null, caso em que a página inteira é convertida em imagem.

**Returns:**
objeto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtém o modo de apresentação do formulário.

**Returns:**
Elemento FormPresentationMode @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtém a altura de saída da imagem.

**Returns:**
valor int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtém as opções de renderização.

**Returns:**
Elemento RenderingOptions

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtém a resolução da imagem.

**Returns:**
Elemento Resolution

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtém a largura de saída da imagem.

**Returns:**
valor int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Indica se o desempenho dos processos de sombreamento é alto. Por padrão, é verdadeiro.

**Returns:**
valor booleano

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Define o retângulo que delimita a área que será convertida em uma imagem.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Define o modo de apresentação do formulário.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento FormPresentationMode @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Define as opções de renderização.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Define se o desempenho dos processos de sombreamento é alto ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
