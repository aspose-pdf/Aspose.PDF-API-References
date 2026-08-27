---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe de opções de comparação de documentos PDF."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Representa uma classe de opções de comparação de documentos PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Cria uma instância da classe {@link ComparisonOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Obtém e define a ordem das operações de edição. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtém e define as áreas excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção. |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtém e define as áreas excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção. |
| [getExtractionArea](#getExtractionArea--) | Obtém e define a área retangular na qual o texto das páginas será comparado. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opções. |
| [isExcludeTables](#isExcludeTables--) | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com a opção {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . O valor padrão é {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Obtém e define a ordem das operações de edição. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtém e define as áreas excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtém e define as áreas excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção. |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com a opção {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . O valor padrão é {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Obtém e define a área retangular na qual o texto das páginas será comparado. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opções. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Cria uma instância da classe {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Obtém e define a ordem das operações de edição.

**Returns:**
Elemento EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtém e define as áreas excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção.

**Returns:**
array de instâncias de Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtém e define as áreas excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção.

**Returns:**
array de instâncias de Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Obtém e define a área retangular na qual o texto das páginas será comparado. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opções.

**Returns:**
Instância de Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com a opção {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . O valor padrão é {@code false}.

**Returns:**
valor booleano

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Obtém e define a ordem das operações de edição.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtém e define as áreas excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtém e define as áreas excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida juntamente com {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opção não pode ser definida juntamente com {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) opção.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida juntamente com a opção {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . O valor padrão é {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Obtém e define a área retangular na qual o texto das páginas será comparado. Esta opção não pode ser definida juntamente com {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opções.
