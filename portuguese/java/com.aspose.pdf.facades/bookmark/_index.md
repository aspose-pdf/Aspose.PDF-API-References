---
title: "Marcador"
linktitle: "Marcador"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um marcador."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Representa um marcador.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Bookmark](#Bookmark--) | Inicializa uma nova instância da classe {@code Bookmark}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAction](#getAction--) | Obtém a ação vinculada ao marcador. Se PageNumber estiver presente, a ação não pode ser especificada. O tipo de ação inclui: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Obtém a bandeira de negrito do título do marcador. |
| [getChildItem](#getChildItem--) | Obtém os filhos do marcador. Obsoleto("Use a propriedade getChildItems() em vez desta.") |
| [getChildItems](#getChildItems--) | Obtém os filhos do marcador. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Ainda não suportado. O nome da ação correspondente à execução de um item de menu no visualizador Acrobat. |
| [getDestination](#getDestination--) | Obtém a página de destino do marcador. Necessário se a ação for definida como "". |
| [getItalicFlag](#getItalicFlag--) | Obtém a bandeira de itálico do título do marcador. |
| [getLevel](#getLevel--) | Obtém o nível hierárquico do marcador. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Obtém a coordenada inferior da exibição da página. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Obtém a coordenada esquerda da exibição da página. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Obtém a coordenada direita da exibição da página. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Obtém a coordenada superior da exibição da página. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Obtém o fator de zoom da exibição da página. |
| [getPageDisplay](#getPageDisplay--) | Obtém o tipo da página de destino do marcador de exibição. |
| [getPageNumber](#getPageNumber--) | Obtém o número da página de destino do marcador. |
| [getRemoteFile](#getRemoteFile--) | Obtém o arquivo (caminho) necessário para a ação "GoToR" do marcador. |
| [getTitle](#getTitle--) | Obtém o título do marcador. |
| [getTitleColor](#getTitleColor--) | Obtém a cor do título do marcador. |
| [isOpen](#isOpen--) | Obtém o estado do marcador (aberto, fechado). |
| [setAction](#setAction-java.lang.String-) | Define a ação vinculada ao marcador. Se PageNumber for apresentado, a ação não pode ser especificada. O tipo de ação inclui: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Define a marcação em negrito do título do marcador. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Define os filhos do marcador. Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Define os filhos do marcador. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Ainda não suportado. Define o nome da ação correspondente para executar um item de menu no visualizador Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | Define a página de destino do marcador. Necessário se a ação for definida como "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Define a marcação em itálico do título do marcador. |
| [setLevel](#setLevel-int-) | Define o nível hierárquico do marcador. |
| [setOpen](#setOpen-boolean-) | Define o estado do marcador (aberto, fechado). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Define a coordenada inferior da exibição da página. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Define a coordenada esquerda da exibição da página. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Define a coordenada direita da exibição da página. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Define a coordenada superior da exibição da página. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Define o fator de zoom da exibição da página. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Define o tipo da página de destino do marcador de exibição. |
| [setPageNumber](#setPageNumber-int-) | Define o número da página de destino do marcador. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Define o arquivo (caminho) necessário para a ação "GoToR" do marcador. |
| [setTitle](#setTitle-java.lang.String-) | Define o título do marcador. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Define a cor do título do marcador. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | converter para OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Inicializa uma nova instância da classe {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

Obtém a ação vinculada ao marcador. Se PageNumber estiver presente, a ação não pode ser especificada. O tipo de ação inclui: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
valor String

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Obtém a bandeira de negrito do título do marcador.

**Returns:**
valor booleano

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Obtém os filhos do marcador. Obsoleto("Use a propriedade getChildItems() em vez desta.")

**Returns:**
Elemento Bookmarks

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Obtém os filhos do marcador.

**Returns:**
Itens filhos do marcador.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Ainda não suportado. O nome da ação correspondente à execução de um item de menu no visualizador Acrobat.

**Returns:**
array de valores int

### getDestination {#getDestination--}
```
public String getDestination()
```

Obtém a página de destino do marcador. Necessário se a ação for definida como "".

**Returns:**
valor String

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Obtém a bandeira de itálico do título do marcador.

**Returns:**
valor booleano

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtém o nível hierárquico do marcador.

**Returns:**
valor int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Obtém a coordenada inferior da exibição da página.

**Returns:**
valor int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Obtém a coordenada esquerda da exibição da página.

**Returns:**
valor int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Obtém a coordenada direita da exibição da página.

**Returns:**
valor int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Obtém a coordenada superior da exibição da página.

**Returns:**
valor int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Obtém o fator de zoom da exibição da página.

**Returns:**
valor int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Obtém o tipo da página de destino do marcador de exibição.

**Returns:**
valor String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtém o número da página de destino do marcador.

**Returns:**
valor int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Obtém o arquivo (caminho) necessário para a ação "GoToR" do marcador.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém o título do marcador.

**Returns:**
valor String

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Obtém a cor do título do marcador.

**Returns:**
Elemento de cor

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Obtém o estado do marcador (aberto, fechado).

**Returns:**
valor booleano

### setAction {#setAction-java.lang.String-}
Define a ação vinculada ao marcador. Se PageNumber for apresentado, a ação não pode ser especificada. O tipo de ação inclui: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Define a marcação em negrito do título do marcador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Define os filhos do marcador. Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Define os filhos do marcador.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Ainda não suportado. Define o nome da ação correspondente para executar um item de menu no visualizador Acrobat.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de valores int |

### setDestination {#setDestination-java.lang.String-}
Define a página de destino do marcador. Necessário se a ação for definida como "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Define a marcação em itálico do título do marcador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Define o nível hierárquico do marcador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Define o estado do marcador (aberto, fechado).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Define a coordenada inferior da exibição da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Define a coordenada esquerda da exibição da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Define a coordenada direita da exibição da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Define a coordenada superior da exibição da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Define o fator de zoom da exibição da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Define o tipo da página de destino do marcador de exibição.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Define o número da página de destino do marcador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Define o arquivo (caminho) necessário para a ação "GoToR" do marcador.

### setTitle {#setTitle-java.lang.String-}
Define o título do marcador.

### setTitleColor {#setTitleColor-java.awt.Color-}
Define a cor do título do marcador.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
converter para OutlineItemCollection
