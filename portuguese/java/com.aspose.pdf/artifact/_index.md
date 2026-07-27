---
title: "Artefato"
linktitle: "Artefato"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um objeto PDF Artifact."
type: docs
weight: 190
url: /pt/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Classe que representa um objeto PDF Artifact.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Construtor do artefato com tipo e subtipo especificados |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Este construtor é usado quando o artefato é lido da página. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Construtor do artefato com tipo e subtipo especificados |

## Métodos

| Método | Descrição |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Inicie atualizações deletadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores do artefato são alterados sempre que uma propriedade do artefato é modificada. Isso causa a mudança do conteúdo da página a cada alteração do artefato. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite mudar o conteúdo da página apenas uma vez. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [dispose](#dispose--) | Descarta o artefato. Este método está obsoleto, use close() em vez disso. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Obtém o alinhamento horizontal do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Obtém o alinhamento vertical do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getBottomMargin](#getBottomMargin--) | Obtém a margem inferior do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getContents](#getContents--) | Obtém a coleção de operadores internos do artefato. |
| [getCustomSubtype](#getCustomSubtype--) | Obtém o nome do subtipo do artefato. Pode ser usado se o subtipo do artefato não for um subtipo padrão. |
| [getCustomType](#getCustomType--) | Obtém o nome do tipo do artefato. Pode ser usado se o tipo do artefato não for padrão. |
| [getForm](#getForm--) | Obtém o XForm do artefato (se o XForm for usado). |
| [getImage](#getImage--) | Obtém a imagem do artefato (se presente). |
| [getLeftMargin](#getLeftMargin--) | Obtém a margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getLines](#getLines--) | Linhas do artefato de texto multilinha. |
| [getOpacity](#getOpacity--) | Obtém a opacidade do artefato. Valores possíveis estão no intervalo 0..1. |
| [getPosition](#getPosition--) | Obtém a posição do artefato. Se esta propriedade for especificada, as margens e alinhamentos são ignorados. |
| [getRectangle](#getRectangle--) | Obtém o retângulo do artefato. |
| [getRightMargin](#getRightMargin--) | Obtém a margem direita do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getRotation](#getRotation--) | Obtém o ângulo de rotação do artefato. |
| [getSubtype](#getSubtype--) | Obtém o subtipo do artefato. Se o artefato tiver um subtipo não padrão, o nome do subtipo pode ser lido via CustomSubtype. |
| [getText](#getText--) | Obtém o texto do artefato. |
| [getTextState](#getTextState--) | Estado de texto para o texto do artefato. |
| [getTopMargin](#getTopMargin--) | Obtém a margem superior do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [getType](#getType--) | Obtém o tipo de artefato. |
| [getValue](#getValue-java.lang.String-) | Obtém o valor personalizado do artefato. |
| [isBackground](#isBackground--) | Se verdadeiro, o Artefato é colocado atrás do conteúdo da página. |
| [removeValue](#removeValue-java.lang.String-) | Remove o valor personalizado do artefato. |
| [saveUpdates](#saveUpdates--) | Salva todas as atualizações no artefato que foram feitas após a chamada BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtém o alinhamento horizontal do artefato. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define o alinhamento vertical do artefato. |
| [setBackground](#setBackground-boolean-) | Se verdadeiro, o Artefato é colocado atrás do conteúdo da página. |
| [setBottomMargin](#setBottomMargin-double-) | Define a margem inferior do artefato. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Define o nome do tipo de artefato. Pode ser usado se o tipo de artefato não for padrão. |
| [setImage](#setImage-java.io.InputStream-) | Define a imagem do artefato. |
| [setImage](#setImage-java.lang.String-) | Define a imagem do artefato. |
| [setLeftMargin](#setLeftMargin-double-) | Define a margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Define o texto e as propriedades de texto do artefato. Permite especificar várias linhas. |
| [setOpacity](#setOpacity-double-) | Define a opacidade do artefato. Valores possíveis estão no intervalo 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Define qual string será substituída pelo número da página. O valor padrão é #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Define a página PDF que é colocada na página do documento como artefato. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Define a posição do artefato. |
| [setRightMargin](#setRightMargin-double-) | Define a margem direita do artefato. |
| [setRotation](#setRotation-double-) | Define o ângulo de rotação do artefato. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Define o subtipo do artefato. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Define o texto do artefato. |
| [setText](#setText-java.lang.String-) | Define o texto do artefato. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Define o texto e as propriedades de texto do artefato. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Estado de texto para o texto do artefato. |
| [setTopMargin](#setTopMargin-double-) | Define a margem superior do artefato. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Define o tipo de artefato. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Define valor personalizado do artefato. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Construtor do artefato com tipo e subtipo especificados

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Este construtor é usado quando o artefato é lido da página.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Construtor do artefato com tipo e subtipo especificados

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Inicie atualizações deletadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores do artefato são alterados sempre que uma propriedade do artefato é modificada. Isso causa a mudança do conteúdo da página a cada alteração do artefato. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite mudar o conteúdo da página apenas uma vez. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Descarta o artefato. Este método está obsoleto, use close() em vez disso.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Obtém o alinhamento horizontal do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Obtém o alinhamento vertical do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
Valor de VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtém a margem inferior do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
margem inferior.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Obtém a coleção de operadores internos do artefato.

**Returns:**
lista de operadores internos do artefato.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Obtém o nome do subtipo do artefato. Pode ser usado se o subtipo do artefato não for um subtipo padrão.

**Returns:**
valor String

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Obtém o nome do tipo do artefato. Pode ser usado se o tipo do artefato não for padrão.

**Returns:**
Nome do artefato String

### getForm {#getForm--}
```
public XForm getForm()
```

Obtém o XForm do artefato (se o XForm for usado).

**Returns:**
objeto XForm

### getImage {#getImage--}
```
public XImage getImage()
```

Obtém a imagem do artefato (se presente).

**Returns:**
objeto XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtém a margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
margem esquerda do artefato.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Linhas do artefato de texto multilinha.

**Returns:**
Lista de Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtém a opacidade do artefato. Valores possíveis estão no intervalo 0..1.

**Returns:**
opacidade do artefato.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtém a posição do artefato. Se esta propriedade for especificada, as margens e alinhamentos são ignorados.

**Returns:**
posição do artefato.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo do artefato.

**Returns:**
objeto Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtém a margem direita do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
margem direita do artefato.

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtém o ângulo de rotação do artefato.

**Returns:**
ângulo de rotação do artefato.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Obtém o subtipo do artefato. Se o artefato tiver um subtipo não padrão, o nome do subtipo pode ser lido via CustomSubtype.

**Returns:**
subtipo do artefato. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Obtém o texto do artefato.

**Returns:**
valor String

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Estado de texto para o texto do artefato.

**Returns:**
instância TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtém a margem superior do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Returns:**
margem superior do artefato.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Obtém o tipo de artefato.

**Returns:**
valor do tipo de artefato. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Obtém o valor personalizado do artefato.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Se verdadeiro, o Artefato é colocado atrás do conteúdo da página.

**Returns:**
valor booleano

### removeValue {#removeValue-java.lang.String-}
Remove o valor personalizado do artefato.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Salva todas as atualizações no artefato que foram feitas após a chamada BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtém o alinhamento horizontal do artefato.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define o alinhamento vertical do artefato.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Se verdadeiro, o Artefato é colocado atrás do conteúdo da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Define a margem inferior do artefato.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | margem inferior. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Define o nome do tipo de artefato. Pode ser usado se o tipo de artefato não for padrão.

### setImage {#setImage-java.io.InputStream-}
Define a imagem do artefato.

### setImage {#setImage-java.lang.String-}
Define a imagem do artefato.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Define a margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | margem esquerda do artefato. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Define o texto e as propriedades de texto do artefato. Permite especificar várias linhas.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Define a opacidade do artefato. Valores possíveis estão no intervalo 0..1.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | opacidade do artefato. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Define qual string será substituída pelo número da página. O valor padrão é #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Define a página PDF que é colocada na página do documento como artefato.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Define a posição do artefato.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Define a margem direita do artefato.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | margem direita do artefato. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Define o ângulo de rotação do artefato.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | ângulo de rotação do artefato. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Define o subtipo do artefato.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Define o texto do artefato.

### setText {#setText-java.lang.String-}
Define o texto do artefato.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Define o texto e as propriedades de texto do artefato.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Estado de texto para o texto do artefato.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Define a margem superior do artefato.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | margem superior do artefato. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Define o tipo de artefato.

### setValue {#setValue-java.lang.String-java.lang.String-}
Define valor personalizado do artefato.
