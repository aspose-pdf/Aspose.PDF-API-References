---
title: "Campo"
linktitle: "Campo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe base para campos de formulário Acro."
type: docs
weight: 1380
url: /pt/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Classe base para campos de formulário Acro.

## Campos

| Campo | Descrição |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Cria um campo para uso no Generator. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Executa uma ação JavaScript especificada para o campo. |
| [flatten](#flatten--) | Remove este campo e coloca seu valor diretamente na página. |
| [get_Item](#get_Item-int-) | Obtém o subcampo contido neste campo por índice. |
| [get_Item](#get_Item-java.lang.String-) | Obtém o subcampo contido neste campo pelo nome do subcampo. |
| [getAlternateName](#getAlternateName--) | Obtém o nome alternativo do campo (Um nome de campo alternativo que deve ser usado no lugar do nome real do campo sempre que o campo for identificado na interface do usuário). O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Obtém o índice desta anotação na página. |
| [getMappingName](#getMappingName--) | Obtém o nome de mapeamento do campo que deve ser usado ao exportar dados de campos de formulário interativo do documento. |
| [getMaxFontSize](#getMaxFontSize--) | Tamanho máximo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| [getMinFontSize](#getMinFontSize--) | Tamanho mínimo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| [getPageIndex](#getPageIndex--) | Obtém o índice da página que contém este campo. |
| [getPartialName](#getPartialName--) | Obtém o nome parcial do campo. |
| [getRect](#getRect--) | Obtém o retângulo do campo. |
| [getSyncRoot](#getSyncRoot--) | Objeto de sincronização. |
| [getTabOrder](#getTabOrder--) | Obtém ou define a ordem de tabulação do campo. |
| [getValue](#getValue--) | Obtém o valor do campo. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Se verdadeiro, o tamanho da fonte será reduzido para ajustar o texto ao retângulo especificado. |
| [isGroup](#isGroup--) | Obtém o valor booleano que indica se este campo é um campo não terminal, ou seja, um grupo de campos. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Propriedade para suporte ao Generator. Usada quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma única vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento. |
| [isSynchronized](#isSynchronized--) | Retorna verdadeiro se o dicionário estiver sincronizado. |
| [iterator](#iterator--) | Retorna o enumerador dos campos contidos. |
| [recalculate](#recalculate--) | Recalcula todos os campos calculados no formulário. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Define o nome alternativo do campo (Um nome de campo alternativo que deve ser usado no lugar do nome real do campo sempre que o campo for identificado na interface do usuário). O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Define o índice desta anotação na página. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Se verdadeiro, o tamanho da fonte será reduzido para ajustar o texto ao retângulo especificado. |
| [setMappingName](#setMappingName-java.lang.String-) | Define o nome de mapeamento do campo que deve ser usado ao exportar dados de campos de formulário interativo do documento. |
| [setMaxFontSize](#setMaxFontSize-double-) | Tamanho máximo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| [setMinFontSize](#setMinFontSize-double-) | Tamanho mínimo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| [setPartialName](#setPartialName-java.lang.String-) | Define o nome parcial do campo. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Define a posição do campo. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Define o retângulo do campo. |
| [setSharedField](#setSharedField-boolean-) | Propriedade para suporte ao Generator. Usada quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma única vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento. |
| [setTabOrder](#setTabOrder-int-) | Obtém ou define a ordem de tabulação do campo. |
| [setValue](#setValue-java.lang.String-) | Define o valor. |
| [size](#size--) | Obtém o número de subcampos neste campo. (Por exemplo, número de itens em um campo de botão de opção). |
| [updateAppearances](#updateAppearances--) | Atualiza o valor das aparências. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Cria um campo para uso no Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia os subcampos deste campo para o array a partir do índice especificado.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia os subcampos deste campo para o array a partir do índice especificado.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Executa uma ação JavaScript especificada para o campo.

### flatten {#flatten--}
```
public void flatten()
```

Remove este campo e coloca seu valor diretamente na página.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtém o subcampo contido neste campo por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do subcampo solicitado. |

**Returns:**
Instância do campo.

### get_Item {#get_Item-java.lang.String-}
Obtém o subcampo contido neste campo pelo nome do subcampo.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Obtém o nome alternativo do campo (Um nome de campo alternativo que deve ser usado no lugar do nome real do campo sempre que o campo for identificado na interface do usuário). O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat.

**Returns:**
valor String

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Obtém o índice desta anotação na página.

**Returns:**
valor int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Obtém o nome de mapeamento do campo que deve ser usado ao exportar dados de campos de formulário interativo do documento.

**Returns:**
valor String

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Tamanho máximo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho.

**Returns:**
valor double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Tamanho mínimo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho.

**Returns:**
valor double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtém o índice da página que contém este campo.

**Returns:**
valor int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Obtém o nome parcial do campo.

**Returns:**
valor String

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtém o retângulo do campo.

**Returns:**
o retângulo do campo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objeto de sincronização.

**Returns:**
valor do objeto

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtém ou define a ordem de tabulação do campo.

**Returns:**
valor int

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor do campo.

**Returns:**
valor String

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Se verdadeiro, o tamanho da fonte será reduzido para ajustar o texto ao retângulo especificado.

**Returns:**
valor booleano

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Obtém o valor booleano que indica se este campo é um campo não terminal, ou seja, um grupo de campos.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Propriedade para suporte ao Generator. Usada quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma única vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Retorna verdadeiro se o dicionário estiver sincronizado.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Retorna o enumerador dos campos contidos.

**Returns:**
Objeto enumerador.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Recalcula todos os campos calculados no formulário.

**Returns:**
verdadeiro se o valor do campo foi alterado durante a recalculação.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Define o nome alternativo do campo (Um nome de campo alternativo que deve ser usado no lugar do nome real do campo sempre que o campo for identificado na interface do usuário). O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Define o índice desta anotação na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Se verdadeiro, o tamanho da fonte será reduzido para ajustar o texto ao retângulo especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMappingName {#setMappingName-java.lang.String-}
Define o nome de mapeamento do campo que deve ser usado ao exportar dados de campos de formulário interativo do documento.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Tamanho máximo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Tamanho mínimo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setPartialName {#setPartialName-java.lang.String-}
Define o nome parcial do campo.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Define a posição do campo.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Define o retângulo do campo.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Propriedade para suporte ao Generator. Usada quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma única vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Obtém ou define a ordem de tabulação do campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setValue {#setValue-java.lang.String-}
Define o valor.

### size {#size--}
```
public int size()
```

Obtém o número de subcampos neste campo. (Por exemplo, número de itens em um campo de botão de opção).

**Returns:**
valor int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Atualiza o valor das aparências.
