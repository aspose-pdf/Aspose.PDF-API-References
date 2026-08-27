---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para converter cada página de um arquivo pdf em imagens, suportando BMP, JPEG, PNG e TIFF agora. Conteúdo suportado em pdfs: imagens, formulário, comentário."
type: docs
weight: 390
url: /pt/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Representa uma classe para converter cada página de um arquivo PDF em imagens, suportando atualmente BMP, JPEG, PNG e TIFF. Conteúdo suportado em PDFs: imagens, formulários, comentários.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Inicializa um novo objeto {@code PdfConverter}. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Inicializa um novo objeto {@code PdfConverter}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Associa um documento PDF à instância {@link PdfConverter} para processamento adicional. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa um fluxo Pdf para conversão. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa um arquivo Pdf para conversão. |
| [close](#close--) | Fecha a instância de PdfConverter e libera os recursos. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Somente para uso interno |
| [dispose](#dispose--) | Fecha a instância de PdfConverter e libera os recursos. Este método está obsoleto, use close() em vez disso. |
| [doConvert](#doConvert--) | <p> Execute algumas tarefas iniciais para converter um documento pdf em imagens. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [getEndPage](#getEndPage--) | Obtém a posição final que você deseja converter. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtém o modo de apresentação do formulário. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Salva a imagem no stream com o formato de imagem padrão - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva a imagem no stream com o formato de imagem especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Salva a imagem no stream com o formato de imagem fornecido, tamanho e qualidade. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Salva a imagem no stream com o formato de imagem e qualidade especificados. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Salva a imagem no stream com o formato de imagem fornecido, tamanho e qualidade. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Salva a imagem no stream com o formato de imagem fornecido, dimensões e qualidade. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Salva a imagem no stream com o tamanho de página especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Salva a imagem no stream com o tamanho de página especificado. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Salva a imagem no stream com o tamanho de página, formato de imagem e qualidade especificados. |
| [getNextImage](#getNextImage-java.lang.String-) | Salva a imagem em arquivo com o formato de imagem padrão - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Salva a imagem em arquivo com o formato de imagem fornecido. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Salva a imagem em arquivo com o formato de imagem fornecido, tamanho da imagem e qualidade. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Salva a imagem em arquivo com o formato de imagem fornecido e qualidade. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Salva a imagem em arquivo com o formato de imagem fornecido e dimensões. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Salva a imagem em arquivo com o formato de imagem fornecido, dimensões e qualidade. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Salva a imagem em arquivo com o tamanho de página fornecido e formato de imagem padrão - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Salva a imagem em arquivo com o tamanho de página fornecido e formato de imagem. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Salva a imagem em arquivo com o tamanho de página fornecido, formato de imagem e qualidade. |
| [getPageCount](#getPageCount--) | Obtém a contagem de páginas. |
| [getPassword](#getPassword--) | Obtém a OwnerPassword do documento. |
| [getRenderingOptions](#getRenderingOptions--) | Obtém as opções de renderização. |
| [getResolution](#getResolution--) | Obtém a resolução durante a conversão. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 150. |
| [getStartPage](#getStartPage--) | Obtém a posição inicial que você deseja converter. O valor mínimo é 1. |
| [getUserPassword](#getUserPassword--) | Obtém a UserPassword do documento. |
| [hasNextImage](#hasNextImage--) | Indica se o arquivo PDF tem mais imagens ou não. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Obtém a flag que controla a visibilidade de áreas ocultas na página. O método está obsoleto. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Mescla a lista de fluxos de imagem em um único fluxo de imagem. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Mescla a lista de fluxos TIFF em um único fluxo TIFF de múltiplas frames. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Converte cada página de um documento PDF em imagens com e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converte cada página de um documento PDF em imagens com e salva as imagens em um único arquivo TIFF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [setEndPage](#setEndPage-int-) | Define a posição final que você deseja converter. use setEndPage(int) antes de setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Define o modo de apresentação do formulário. |
| [setPassword](#setPassword-java.lang.String-) | Define a OwnerPassword do documento. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Define o intervalo de páginas entre as quais você deseja converter. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Define as opções de renderização. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Define a resolução durante a conversão. Quanto maior a resolução, mais lenta será a velocidade de conversão. O valor padrão é 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setStartPage](#setStartPage-int-) | Define a posição inicial que você deseja converter. O valor mínimo é 1. use setEndPage(int) antes de setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Define a UserPassword do documento. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Inicializa um novo objeto {@code PdfConverter}.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Inicializa um novo objeto {@code PdfConverter}.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Associa um documento PDF à instância {@link PdfConverter} para processamento adicional.

### bindPdf {#bindPdf-java.io.InputStream-}
Associa um fluxo Pdf para conversão.

### bindPdf {#bindPdf-java.lang.String-}
Associa um arquivo Pdf para conversão.

### close {#close--}
```
public void close()
```

Fecha a instância de PdfConverter e libera os recursos.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Somente para uso interno

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fecha a instância de PdfConverter e libera os recursos. Este método está obsoleto, use close() em vez disso.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Execute algumas tarefas iniciais para converter um documento pdf em imagens. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Obtém a posição final que você deseja converter.

**Returns:**
valor int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtém o modo de apresentação do formulário.

**Returns:**
modo de apresentação de formulário. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Salva a imagem no stream com o formato de imagem padrão - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva a imagem no stream com o formato de imagem especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Salva a imagem no stream com o formato de imagem fornecido, tamanho e qualidade.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Salva a imagem no stream com o formato de imagem e qualidade especificados.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Salva a imagem no stream com o formato de imagem fornecido, tamanho e qualidade.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Salva a imagem no stream com o formato de imagem fornecido, dimensões e qualidade.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Salva a imagem no stream com o tamanho de página especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Salva a imagem no stream com o tamanho de página especificado.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Salva a imagem no stream com o tamanho de página, formato de imagem e qualidade especificados.

### getNextImage {#getNextImage-java.lang.String-}
Salva a imagem em arquivo com o formato de imagem padrão - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Salva a imagem em um arquivo com o formato de imagem fornecido. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Salva a imagem em um arquivo com o formato de imagem fornecido, tamanho da imagem e qualidade. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Salva a imagem em arquivo com o formato de imagem fornecido e qualidade.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Salva a imagem em um arquivo com o formato de imagem e dimensões fornecidos. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Salva a imagem em um arquivo com o formato de imagem, dimensões e qualidade fornecidos. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Salva a imagem em arquivo com o tamanho de página fornecido e formato de imagem padrão - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Salva a imagem em arquivo com o tamanho de página fornecido e formato de imagem.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Salva a imagem em arquivo com o tamanho de página fornecido, formato de imagem e qualidade.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtém a contagem de páginas.

**Returns:**
valor int

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtém a OwnerPassword do documento.

**Returns:**
valor String

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

Obtém a resolução durante a conversão. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 150.

**Returns:**
Elemento Resolution

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Obtém a posição inicial que você deseja converter. O valor mínimo é 1.

**Returns:**
valor int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Obtém a UserPassword do documento.

**Returns:**
valor String

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Indica se o arquivo PDF tem mais imagens ou não.

**Returns:**
Pode obter mais imagens ou não, true se puder, ou false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Obtém a flag que controla a visibilidade de áreas ocultas na página. O método está obsoleto.

**Returns:**
valor booleano

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Mescla a lista de fluxos de imagem em um único fluxo de imagem.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Mescla a lista de fluxos TIFF em um único fluxo TIFF de múltiplas frames.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte cada página de um documento PDF em imagens com dimensões e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens com tamanho de página e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Converte cada página de um documento PDF em imagens com e salva as imagens em um único arquivo TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converte cada página de um documento PDF em imagens com e salva as imagens em um único arquivo TIFF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converte cada página de um documento PDF em imagens e salva as imagens em um único fluxo TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\Test\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Define a posição final que você deseja converter. use setEndPage(int) antes de setStartPage(int)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Define o modo de apresentação do formulário.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | modo de apresentação de formulário. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Define a OwnerPassword do documento.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Define o intervalo de páginas entre as quais você deseja converter.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startPage |  | valor int |
| EndPage |  | valor int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Define as opções de renderização.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Define a resolução durante a conversão. Quanto maior a resolução, mais lenta será a velocidade de conversão. O valor padrão é 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Define a posição inicial que você deseja converter. O valor mínimo é 1. use setEndPage(int) antes de setStartPage(int)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setUserPassword {#setUserPassword-java.lang.String-}
Define a UserPassword do documento.
