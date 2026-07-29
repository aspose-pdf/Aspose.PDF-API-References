---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe ajuda a salvar as páginas do documento pdf, uma a uma, em uma única imagem tiff."
type: docs
weight: 210
url: /pt/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Esta classe ajuda a salvar as páginas do documento pdf, uma a uma, em uma única imagem tiff.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-int-int-) | Inicializa uma nova instância da classe {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Executa a binarização Bradley para o fluxo de entrada. |
| [getCropRectangle](#getCropRectangle--) | Obtém o retângulo que define a área que será convertida em uma imagem. O padrão é null, caso em que toda a imagem é convertida em uma página |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtém o modo de apresentação do formulário. |
| [getHeight](#getHeight--) | Obtém a altura de saída da imagem. |
| [getRenderingOptions](#getRenderingOptions--) | Obtém as opções de renderização. |
| [getResolution](#getResolution--) | Obtém a resolução da imagem. |
| [getSettings](#getSettings--) | Obtém as configurações para mapear PDF em imagem TIFF. |
| [getWidth](#getWidth--) | Obtém a largura de saída da imagem. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Converte determinadas páginas do documento em TIFF e as salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Converte determinadas páginas do documento em TIFF e as salva no fluxo de saída. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Executa alguma operação na página fornecida, por exemplo. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Define o retângulo que delimita a área que será convertida em uma imagem. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Obtém o modo de apresentação do formulário. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Define as opções de renderização. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Inicializa uma nova instância da classe {@code TiffDevice}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura de saída da imagem. |
| altura |  | Altura de saída da imagem. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inicializa uma nova instância da classe {@code TiffDevice} com configurações padrão.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Executa a binarização Bradley para o fluxo de entrada.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtém o retângulo que define a área que será convertida em uma imagem. O padrão é null, caso em que toda a imagem é convertida em uma página

**Returns:**
objeto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtém o modo de apresentação do formulário.

**Returns:**
Valor de FormPresentationMode @see FormPresentationMode

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
opções de renderização.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtém a resolução da imagem.

**Returns:**
Elemento Resolution

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Obtém as configurações para mapear PDF em imagem TIFF.

**Returns:**
Elemento TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtém a largura de saída da imagem.

**Returns:**
valor int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Converte determinadas páginas do documento em TIFF e as salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Converte determinadas páginas do documento em TIFF e as salva no fluxo de saída.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Executa alguma operação na página fornecida, por exemplo.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Define o retângulo que delimita a área que será convertida em uma imagem.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Obtém o modo de apresentação do formulário.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Define as opções de renderização.
