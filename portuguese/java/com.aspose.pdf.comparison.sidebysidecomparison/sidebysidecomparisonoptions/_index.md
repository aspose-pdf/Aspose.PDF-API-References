---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe de opções para comparar documentos com saída lado a lado."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Representa uma classe de opções para comparar documentos com saída lado a lado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Cria uma instância da classe {@link SideBySideComparisonOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Obtém e define a propriedade que determina se marcadores de alteração adicionais são exibidos. Se definido, exibe marcas de alteração que não estão na página atual, mas estão presentes em outra página. Se a alteração ocorrer entre palavras, a marca pode não estar posicionada exatamente em relação ao caractere de espaço em branco. O valor padrão é {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Obtém e define a área de comparação. Usado para a primeira página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções. |
| [getComparisonArea2](#getComparisonArea2--) | Obtém e define a área de comparação. Usado para a segunda página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções. |
| [getComparisonMode](#getComparisonMode--) | Obtém e define um modo de comparação. O valor padrão é {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Obtém a cor usada para marcar conteúdo excluído durante uma comparação lado a lado. Esta propriedade define a representação visual das exclusões no resultado da comparação. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtém e define as áreas de exclusão. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtém e define as áreas de exclusão. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). O valor padrão é {@code false}. |
| [getInsertColor](#getInsertColor--) | Obtém a cor usada para marcar conteúdo inserido durante uma comparação lado a lado. Esta propriedade define a representação visual da inserção no resultado da comparação. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Obtém e define a propriedade que determina se marcadores de alteração adicionais são exibidos. Se definido, exibe marcas de alteração que não estão na página atual, mas estão presentes em outra página. Se a alteração ocorrer entre palavras, a marca pode não estar posicionada exatamente em relação ao caractere de espaço em branco. O valor padrão é {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Obtém e define a área de comparação. Usado para a primeira página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Obtém e define a área de comparação. Usado para a segunda página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções. |
| [setComparisonMode](#setComparisonMode-int-) | Obtém e define um modo de comparação. O valor padrão é {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Define a cor usada para marcar conteúdo excluído durante uma comparação lado a lado. Esta propriedade define a representação visual das exclusões no resultado da comparação. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtém e define as áreas de exclusão. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtém e define as áreas de exclusão. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). O valor padrão é {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Define a cor usada para marcar conteúdo inserido durante uma comparação lado a lado. Esta propriedade define a representação visual da inserção no resultado da comparação. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Cria uma instância da classe {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Obtém e define a propriedade que determina se marcadores de alteração adicionais são exibidos. Se definido, exibe marcas de alteração que não estão na página atual, mas estão presentes em outra página. Se a alteração ocorrer entre palavras, a marca pode não estar posicionada exatamente em relação ao caractere de espaço em branco. O valor padrão é {@code false}.

**Returns:**
valor booleano

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Obtém e define a área de comparação. Usado para a primeira página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções.

**Returns:**
Instância de Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Obtém e define a área de comparação. Usado para a segunda página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções.

**Returns:**
Instância de Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Obtém e define um modo de comparação. O valor padrão é {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Elemento ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Obtém a cor usada para marcar conteúdo excluído durante uma comparação lado a lado. Esta propriedade define a representação visual das exclusões no resultado da comparação.

**Returns:**
a cor usada para marcar conteúdo excluído durante uma comparação lado a lado.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtém e define as áreas de exclusão. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
array de instâncias de Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtém e define as áreas de exclusão. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
array de instâncias de Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). O valor padrão é {@code false}.

**Returns:**
valor booleano

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Obtém a cor usada para marcar conteúdo inserido durante uma comparação lado a lado. Esta propriedade define a representação visual da inserção no resultado da comparação.

**Returns:**
a cor usada para marcar conteúdo inserido durante uma comparação lado a lado.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Obtém e define a propriedade que determina se marcadores de alteração adicionais são exibidos. Se definido, exibe marcas de alteração que não estão na página atual, mas estão presentes em outra página. Se a alteração ocorrer entre palavras, a marca pode não estar posicionada exatamente em relação ao caractere de espaço em branco. O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Obtém e define a área de comparação. Usado para a primeira página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Obtém e define a área de comparação. Usado para a segunda página ou documento no método de comparação. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opções.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Obtém e define um modo de comparação. O valor padrão é {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Define a cor usada para marcar conteúdo excluído durante uma comparação lado a lado. Esta propriedade define a representação visual das exclusões no resultado da comparação.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtém e define as áreas de exclusão. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtém e define as áreas de exclusão. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com a opção {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Define a cor usada para marcar conteúdo inserido durante uma comparação lado a lado. Esta propriedade define a representação visual da inserção no resultado da comparação.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
