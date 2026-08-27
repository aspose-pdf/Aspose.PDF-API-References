---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe de opções para extrair gráficos vetoriais da página do documento pdf."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Representa uma classe de opções para extrair gráficos vetoriais da página do documento pdf.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Cria uma instância da classe SvgExtractionOptions. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Obtém e define a opção de agrupar automaticamente subcaminhos em imagens. Esta opção exclui a opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Obtém e define a opção de extrair cada subcaminho de um documento PDF em imagens SVG separadas. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Obtém e define o retângulo delimitador que define a área de extração para extração de SVG. |
| [getGroupStrength](#getGroupStrength--) | Obtém e define uma opção A força de agrupar subcaminhos em imagens. Permite configurar o grau de agrupamento dos subcaminhos. O intervalo de valores vai de 0 a 1. Um valor 0 corresponde à opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) habilitada. Um valor 1 criará uma única imagem para todos os caminhos vetoriais na página. A opção tem efeito quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) está false. O valor padrão é {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Obtém ou define a largura mínima do traço que será usada no SVG resultante. Se o PDF usar uma largura de traço mais fina, ela será substituída por esta largura. O valor padrão é 0,5. O valor é expresso em unidades de espaço de usuário transformadas da página PDF convertida. Por padrão, 1 unidade de espaço de usuário corresponde a 1/72 polegada (0,35 mm), mas isso pode ser sobrescrito pelo documento PDF. Transformações podem afetar a largura mínima real no SVG gerado. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Obtém e define uma opção para definir se verifica estritamente se os subcaminhos estão dentro do retângulo especificado em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se definido como false, então subcaminhos que não estejam completamente incluídos em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serão extraídos. O valor padrão é {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Obtém e define um sinalizador que determina se os XFrom encontrados nas páginas devem ser desempacotados ou não. Elementos XFrom podem acabar em arquivos SVG diferentes. Apenas XForms que são renderizados por instruções Do do conteúdo da página são desempacotados. XForms aninhados não são desempacotados. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Obtém e define a opção de desempacotar apenas o XForm correspondente ao predicado especificado. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Obtém e define a opção de agrupar automaticamente subcaminhos em imagens. Esta opção exclui a opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Obtém e define a opção de extrair cada subcaminho de um documento PDF em imagens SVG separadas. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Obtém e define o retângulo delimitador que define a área de extração para extração de SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Obtém e define uma opção A força de agrupar subcaminhos em imagens. Permite configurar o grau de agrupamento dos subcaminhos. O intervalo de valores vai de 0 a 1. Um valor 0 corresponde à opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) habilitada. Um valor 1 criará uma única imagem para todos os caminhos vetoriais na página. A opção tem efeito quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) está false. O valor padrão é {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Obtém ou define a largura mínima do traço que será usada no SVG resultante. Se o PDF usar uma largura de traço mais fina, ela será substituída por esta largura. O valor padrão é 0,5. O valor é expresso em unidades de espaço de usuário transformadas da página PDF convertida. Por padrão, 1 unidade de espaço de usuário corresponde a 1/72 polegada (0,35 mm), mas isso pode ser sobrescrito pelo documento PDF. Transformações podem afetar a largura mínima real no SVG gerado. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Obtém e define uma opção para definir se verifica estritamente se os subcaminhos estão dentro do retângulo especificado em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se definido como false, então subcaminhos que não estejam completamente incluídos em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serão extraídos. O valor padrão é {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Obtém e define um sinalizador que determina se os XFrom encontrados nas páginas devem ser desempacotados ou não. Elementos XFrom podem acabar em arquivos SVG diferentes. Apenas XForms que são renderizados por instruções Do do conteúdo da página são desempacotados. XForms aninhados não são desempacotados. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Obtém e define a opção de desempacotar apenas o XForm correspondente ao predicado especificado. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Cria uma instância da classe SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Obtém e define a opção de agrupar automaticamente subcaminhos em imagens. Esta opção exclui a opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
valor booleano

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Obtém e define a opção de extrair cada subcaminho de um documento PDF em imagens SVG separadas.

**Returns:**
valor booleano

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Obtém e define o retângulo delimitador que define a área de extração para extração de SVG.

**Returns:**
Instância de Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Obtém e define uma opção A força de agrupar subcaminhos em imagens. Permite configurar o grau de agrupamento dos subcaminhos. O intervalo de valores vai de 0 a 1. Um valor 0 corresponde à opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) habilitada. Um valor 1 criará uma única imagem para todos os caminhos vetoriais na página. A opção tem efeito quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) está false. O valor padrão é {@code 0.8}.

**Returns:**
valor double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Obtém ou define a largura mínima do traço que será usada no SVG resultante. Se o PDF usar uma largura de traço mais fina, ela será substituída por esta largura. O valor padrão é 0,5. O valor é expresso em unidades de espaço de usuário transformadas da página PDF convertida. Por padrão, 1 unidade de espaço de usuário corresponde a 1/72 polegada (0,35 mm), mas isso pode ser sobrescrito pelo documento PDF. Transformações podem afetar a largura mínima real no SVG gerado.

**Returns:**
valor double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Obtém e define uma opção para definir se verifica estritamente se os subcaminhos estão dentro do retângulo especificado em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se definido como false, então subcaminhos que não estejam completamente incluídos em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serão extraídos. O valor padrão é {@code True}.

**Returns:**
valor booleano

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Obtém e define um sinalizador que determina se os XFrom encontrados nas páginas devem ser desempacotados ou não. Elementos XFrom podem acabar em arquivos SVG diferentes. Apenas XForms que são renderizados por instruções Do do conteúdo da página são desempacotados. XForms aninhados não são desempacotados.

**Returns:**
valor booleano

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Obtém e define a opção de desempacotar apenas o XForm correspondente ao predicado especificado.

**Returns:**
instância interna de Predicate da instância XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Obtém e define a opção de agrupar automaticamente subcaminhos em imagens. Esta opção exclui a opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Obtém e define a opção de extrair cada subcaminho de um documento PDF em imagens SVG separadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Obtém e define o retângulo delimitador que define a área de extração para extração de SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Obtém e define uma opção A força de agrupar subcaminhos em imagens. Permite configurar o grau de agrupamento dos subcaminhos. O intervalo de valores vai de 0 a 1. Um valor 0 corresponde à opção {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) habilitada. Um valor 1 criará uma única imagem para todos os caminhos vetoriais na página. A opção tem efeito quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) está false. O valor padrão é {@code 0.8}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Obtém ou define a largura mínima do traço que será usada no SVG resultante. Se o PDF usar uma largura de traço mais fina, ela será substituída por esta largura. O valor padrão é 0,5. O valor é expresso em unidades de espaço de usuário transformadas da página PDF convertida. Por padrão, 1 unidade de espaço de usuário corresponde a 1/72 polegada (0,35 mm), mas isso pode ser sobrescrito pelo documento PDF. Transformações podem afetar a largura mínima real no SVG gerado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Obtém e define uma opção para definir se verifica estritamente se os subcaminhos estão dentro do retângulo especificado em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se definido como false, então subcaminhos que não estejam completamente incluídos em {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serão extraídos. O valor padrão é {@code True}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Obtém e define um sinalizador que determina se os XFrom encontrados nas páginas devem ser desempacotados ou não. Elementos XFrom podem acabar em arquivos SVG diferentes. Apenas XForms que são renderizados por instruções Do do conteúdo da página são desempacotados. XForms aninhados não são desempacotados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Obtém e define a opção de desempacotar apenas o XForm correspondente ao predicado especificado.
