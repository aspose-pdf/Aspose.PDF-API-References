---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para editar a página de um arquivo PDF, incluindo rotação da página, zoom, movimentação da posição e alteração do tamanho da página."
type: docs
weight: 570
url: /pt/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Representa uma classe para editar a página de um arquivo PDF, incluindo rotação da página, zoom, movimentação da posição e alteração do tamanho da página.

## Campos

| Campo | Descrição |
| --- | --- |
| [BLINDH](#BLINDH) | Persianas Verticais |
| [BLINDV](#BLINDV) | Persianas Verticais |
| [BTWIPE](#BTWIPE) | Limpeza de Baixo-para-Cima |
| [DGLITTER](#DGLITTER) | Brilho Diagonal |
| [DISSOLVE](#DISSOLVE) | A página antiga se dissolve |
| [INBOX](#INBOX) | Caixa Interna |
| [LRGLITTER](#LRGLITTER) | Brilho Esquerda-Direita |
| [LRWIPE](#LRWIPE) | Limpeza Esquerda-Direita |
| [OUTBOX](#OUTBOX) | Caixa Externa |
| [RLWIPE](#RLWIPE) | Limpeza Direita-Esquerda |
| [SPLITHIN](#SPLITHIN) | Divisão Horizontal IN |
| [SPLITHOUT](#SPLITHOUT) | Divisão Horizontal Out |
| [SPLITVIN](#SPLITVIN) | Divisão Vertical In |
| [SPLITVOUT](#SPLITVOUT) | Divisão Vertical Out |
| [TBGLITTER](#TBGLITTER) | Brilho Superior-Inferior |
| [TBWIPE](#TBWIPE) | Limpeza Superior-Inferior |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Construtor da classe PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Construtor da classe PdfPageEditor. |

## Métodos

| Método | Descrição |
| --- | --- |
| [applyChanges](#applyChanges--) | Aplicar alterações feitas nas páginas do documento. |
| [getAlignment](#getAlignment--) | Obtém o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. Use getHorizontalAlignment em vez disso |
| [getDisplayDuration](#getDisplayDuration--) | Obtém a duração de exibição das páginas. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Retorna o tamanho da caixa especificada no documento. </p> <hr> <pre> O exemplo a seguir demonstra como obter a caixa de mídia da primeira página: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Retornar o tamanho da página. |
| [getPageRotation](#getPageRotation-int-) | <p> Retorna a rotação da página especificada. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Obtém a rotação das páginas, uma tabela hash contém o número da página e o grau de rotação, a chave representa o número da página, o valor da chave representa a rotação em graus. </p> |
| [getPages](#getPages--) | <p> Retorna o número total de páginas. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Obtém o tamanho da página do arquivo de saída. |
| [getPageSize](#getPageSize-int-) | <p> Retorna o tamanho da página especificada. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Obtém os números das páginas a serem editadas. Por padrão, cada página será editada. |
| [getRotation](#getRotation--) | Obtém a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270. O valor padrão é 0. |
| [getTransitionDuration](#getTransitionDuration--) | Obtém a duração do efeito de transição. |
| [getTransitionType](#getTransitionType--) | Obtém o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom. Use getVerticalAlignmentType em vez disso |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Obtém o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Obtém o coeficiente de zoom. Valor 1.0 corresponde a 100%. O valor padrão é 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Verifica se a caixa está definida na página. |
| [movePosition](#movePosition-float-float-) | <p> Move a origem de (0, 0) para o ponto especificado. A origem está no canto inferior esquerdo e a unidade é ponto(1 polegada = 72 pontos). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva o documento alterado em um fluxo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Salva o documento alterado em um arquivo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. Use setHorizontalAlignment em vez disso |
| [setDisplayDuration](#setDisplayDuration-int-) | Define a duração de exibição das páginas. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Define a rotação das páginas, uma tabela hash contém o número da página e o grau de rotação, a chave representa o número da página, o valor da chave representa a rotação em graus. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Define o tamanho da página do arquivo de saída. |
| [setProcessPages](#setProcessPages-int:A-) | Define os números das páginas a serem editadas. Por padrão, cada página será editada. |
| [setRotation](#setRotation-int-) | Define a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270. O valor padrão é 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Define a duração do efeito de transição. |
| [setTransitionType](#setTransitionType-int-) | Define o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Define o alinhamento vertical do conteúdo PDF original na página de resultado, o padrão é VerticalAlignmentType.Bottom. Use setVerticalAlignmentType em vez disso |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Define o alinhamento vertical do conteúdo PDF original na página de resultado, o padrão é VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Define o coeficiente de zoom. Valor 1.0 corresponde a 100%. Valor padrão é 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Persianas Verticais

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Persianas Verticais

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Limpeza de Baixo-para-Cima

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Brilho Diagonal

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

A página antiga se dissolve

### INBOX {#INBOX}
```
public static final int INBOX
```

Caixa Interna

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Brilho Esquerda-Direita

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Limpeza Esquerda-Direita

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Caixa Externa

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Limpeza Direita-Esquerda

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

Divisão Horizontal IN

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Divisão Horizontal Out

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

Divisão Vertical In

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Divisão Vertical Out

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Brilho Superior-Inferior

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Limpeza Superior-Inferior

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Construtor da classe PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Construtor da classe PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Aplicar alterações feitas nas páginas do documento.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Obtém o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. Use getHorizontalAlignment em vez disso

**Returns:**
Objeto AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Obtém a duração de exibição das páginas.

**Returns:**
valor int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left.

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Retorna o tamanho da caixa especificada no documento. </p> <hr> <pre> O exemplo a seguir demonstra como obter a caixa de mídia da primeira página: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Retornar o tamanho da página.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Retorna a rotação da página especificada. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| página |  | Índice da página. As páginas do documento são numeradas a partir de 1. |

**Returns:**
Rotação da página em graus.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Obtém a rotação das páginas, uma tabela hash contém o número da página e o grau de rotação, a chave representa o número da página, o valor da chave representa a rotação em graus. </p>

**Returns:**
{@code Map<Integer, Integer>} objeto

### getPages {#getPages--}
```
public int getPages()
```

<p> Retorna o número total de páginas. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Número de páginas.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Obtém o tamanho da página do arquivo de saída.

**Returns:**
Objeto PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Retorna o tamanho da página especificada. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| página |  | Índice da página. As páginas do documento são numeradas a partir de 1. |

**Returns:**
Resultado é uma instância de PageSize. Use as propriedades Width e Height do objeto retornado para obter a largura e a altura da página.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Obtém os números das páginas a serem editadas. Por padrão, cada página será editada.

**Returns:**
array de valores int

### getRotation {#getRotation--}
```
public int getRotation()
```

Obtém a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270. O valor padrão é 0.

**Returns:**
valor int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Obtém a duração do efeito de transição.

**Returns:**
valor int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Obtém o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação.

**Returns:**
valor int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Obtém o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom. Use getVerticalAlignmentType em vez disso

**Returns:**
Objeto VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Obtém o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom.

**Returns:**
Elemento VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Obtém o coeficiente de zoom. Valor 1.0 corresponde a 100%. O valor padrão é 1.0.

**Returns:**
valor float

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Verifica se a caixa está definida na página.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Move a origem de (0, 0) para o ponto especificado. A origem está no canto inferior esquerdo e a unidade é ponto(1 polegada = 72 pontos). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| moveX |  | Coordenada X. |
| moveY |  | Coordenada Y. |

### save {#save-java.io.OutputStream-}
<p> Salva o documento alterado em um fluxo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Salva o documento alterado em um arquivo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. Use setHorizontalAlignment em vez disso

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Define a duração de exibição das páginas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Define a rotação das páginas, uma tabela hash contém o número da página e o grau de rotação, a chave representa o número da página, o valor da chave representa a rotação em graus.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Define o tamanho da página do arquivo de saída.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Define os números das páginas a serem editadas. Por padrão, cada página será editada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de valores int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Define a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270. O valor padrão é 0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Define a duração do efeito de transição.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Define o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Define o alinhamento vertical do conteúdo PDF original na página de resultado, o padrão é VerticalAlignmentType.Bottom. Use setVerticalAlignmentType em vez disso

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Define o alinhamento vertical do conteúdo PDF original na página de resultado, o padrão é VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Define o coeficiente de zoom. Valor 1.0 corresponde a 100%. Valor padrão é 1.0. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float <hr> <pre> O exemplo a seguir demonstra como alterar o zoom das páginas do documento. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
