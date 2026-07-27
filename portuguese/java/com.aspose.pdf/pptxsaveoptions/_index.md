---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato SVG."
type: docs
weight: 3950
url: /pt/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Opções de salvamento para exportação para o formato SVG.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este manipulador pode ser usado para tratar eventos de progresso de conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, exemplo de código do manipulador que mostra o progresso no console é : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Obtém ou define a resolução da imagem (dpi). O padrão é 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Se definido como true, as imagens são separadas de todos os demais gráficos. |
| [getSlidesAsImages](#getSlidesAsImages--) | Se definido como true, todo o conteúdo é reconhecido como imagens (uma por página). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Alterna o reconhecimento de colunas de texto. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo. |
| [setImageResolution](#setImageResolution-int-) | Obtém ou define a resolução da imagem (dpi). O padrão é 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Alterna o reconhecimento de colunas de texto. |
| [setSeparateImages](#setSeparateImages-boolean-) | Se definido como true, as imagens são separadas de todos os demais gráficos. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Se definido como true, todo o conteúdo é reconhecido como imagens (uma por página). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Construtor

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este manipulador pode ser usado para tratar eventos de progresso de conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, exemplo de código do manipulador que mostra o progresso no console é : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
instância ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Obtém ou define a resolução da imagem (dpi). O padrão é 192 dpi.

**Returns:**
valor int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Se definido como true, as imagens são separadas de todos os demais gráficos.

**Returns:**
valor booleano

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Se definido como true, todo o conteúdo é reconhecido como imagens (uma por página).

**Returns:**
valor booleano

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Alterna o reconhecimento de colunas de texto.

**Returns:**
valor booleano

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Obtém ou define a resolução da imagem (dpi). O padrão é 192 dpi.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Alterna o reconhecimento de colunas de texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Se definido como true, as imagens são separadas de todos os demais gráficos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Se definido como true, todo o conteúdo é reconhecido como imagens (uma por página).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
