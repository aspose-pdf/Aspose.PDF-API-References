---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a entrada de contorno na hierarquia de contorno de um documento PDF."
type: docs
weight: 3270
url: /pt/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Representa a entrada de contorno na hierarquia de contorno de um documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Inicializa uma nova instância desta classe usando o objeto de entrada de contorno do mecanismo interno. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Inicializa a instância do item de contorno usando o objeto de hierarquia raiz. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Adiciona item de contorno à coleção. |
| [clear](#clear--) | Limpa todos os itens da coleção. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Ainda não suportado. Sempre lança NotImplementedException |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copia as entradas de contorno para um System.Array, começando em um índice específico do System.Array. |
| [delete](#delete--) | Exclui este item de contorno da hierarquia de contorno do documento. |
| [delete](#delete-java.lang.String-) | Exclui este item de contorno da hierarquia de contorno do documento. |
| [get_Item](#get_Item-int-) | Obtém o item de contorno da coleção usando o índice. |
| [getAction](#getAction--) | Obtém a ação para este item de contorno. |
| [getBold](#getBold--) | Obtém a sinalização de negrito para o texto do título deste item de contorno |
| [getColor](#getColor--) | Obtém a cor para o texto do título deste item de contorno. |
| [getDestination](#getDestination--) | Obtém o destino para este item de contorno. |
| [getEngineDict](#getEngineDict--) | Somente interno |
| [getEngineObj](#getEngineObj--) | Somente interno |
| [getFirst](#getFirst--) | Obtém o item de contorno que representa o primeiro item de nível superior na hierarquia de contorno. |
| [getItalic](#getItalic--) | Obtém uma sinalização de itálico para o texto do título deste item de contorno |
| [getLast](#getLast--) | Obtém o item de contorno que representa o último item de nível superior na hierarquia de contorno. |
| [getLevel](#getLevel--) | Obtém o nível hierárquico do item de contorno. |
| [getNext](#getNext--) | Obtém o item de contorno que representa o próximo item relativo a este item na hierarquia de contorno. |
| [getOpen](#getOpen--) | Obtém o status aberto (true/false) para o item de contorno. |
| [getParent](#getParent--) | Obtém o objeto pai deste item de contorno na hierarquia de contorno. |
| [getPrev](#getPrev--) | Obtém o item de contorno que representa o item anterior relativo a este item na hierarquia de contorno. |
| [getSyncRoot](#getSyncRoot--) | Obtém o objeto que pode ser usado para sincronizar o acesso a esta coleção. |
| [getTitle](#getTitle--) | Obtém o título deste item de contorno. |
| [getVisibleCount](#getVisibleCount--) | Obtém o número total de itens de contorno em todos os níveis na hierarquia de contorno do documento. |
| [hasNext](#hasNext--) | Verifique se o item de contorno que representa o próximo item está relativo a este item na hierarquia de contorno. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Insere o item de contorno na coleção no local especificado. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [isSynchronized](#isSynchronized--) | Obtém o valor que indica se o acesso a esta coleção está sincronizado (thread safe). |
| [iterator](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [next](#next--) |  |
| [remove](#remove-int-) | Remove o item por índice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Ainda não suportado. Sempre lança NotImplementedException |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Define a ação para este item de contorno. |
| [setBold](#setBold-boolean-) | Define a marcação em negrito para o texto do título deste item de contorno |
| [setColor](#setColor-java.awt.Color-) | Define a cor para o texto do título deste item de contorno. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Define o destino para este item de contorno. |
| [setItalic](#setItalic-boolean-) | Define a marcação em itálico para o texto do título deste item de contorno |
| [setOpen](#setOpen-boolean-) | Define o status aberto (true/false) para o item de contorno. |
| [setTitle](#setTitle-java.lang.String-) | Define o título para este item de contorno. |
| [size](#size--) | Contagem de itens da coleção. Por favor, não confunda com VisibleCount: VisibleCount obtém o número de itens de contorno visíveis em todos os níveis. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Inicializa uma nova instância desta classe usando o objeto de entrada de contorno do mecanismo interno.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Inicializa a instância do item de contorno usando o objeto de hierarquia raiz.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Adiciona item de contorno à coleção.

### clear {#clear--}
```
public void clear()
```

Limpa todos os itens da coleção.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Ainda não suportado. Sempre lança NotImplementedException

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copia as entradas de contorno para um System.Array, começando em um índice específico do System.Array.

### delete {#delete--}
```
public void delete()
```

Exclui este item de contorno da hierarquia de contorno do documento.

### delete {#delete-java.lang.String-}
Exclui este item de contorno da hierarquia de contorno do documento.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Obtém o item de contorno da coleção usando o índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice dentro da coleção. |

**Returns:**
Objeto OutlineItemCollection.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtém a ação para este item de contorno.

**Returns:**
Valor PdfAction

### getBold {#getBold--}
```
public boolean getBold()
```

Obtém a sinalização de negrito para o texto do título deste item de contorno

**Returns:**
valor booleano

### getColor {#getColor--}
```
public Color getColor()
```

Obtém a cor para o texto do título deste item de contorno.

**Returns:**
Valor da cor

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Obtém o destino para este item de contorno.

**Returns:**
valor IAppointment

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Somente interno

**Returns:**
Objeto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Somente interno

**Returns:**
Objeto IPdfObject

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Obtém o item de contorno que representa o primeiro item de nível superior na hierarquia de contorno.

**Returns:**
Valor OutlineItemCollection

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Obtém uma sinalização de itálico para o texto do título deste item de contorno

**Returns:**
valor booleano

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Obtém o item de contorno que representa o último item de nível superior na hierarquia de contorno.

**Returns:**
Valor OutlineItemCollection

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtém o nível hierárquico do item de contorno.

**Returns:**
valor int

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Obtém o item de contorno que representa o próximo item relativo a este item na hierarquia de contorno.

**Returns:**
Valor OutlineItemCollection

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtém o status aberto (true/false) para o item de contorno.

**Returns:**
valor booleano

### getParent {#getParent--}
```
public Outlines getParent()
```

Obtém o objeto pai deste item de contorno na hierarquia de contorno.

**Returns:**
Valor Object

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Obtém o item de contorno que representa o item anterior relativo a este item na hierarquia de contorno.

**Returns:**
Valor OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém o objeto que pode ser usado para sincronizar o acesso a esta coleção.

**Returns:**
Valor Object

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém o título deste item de contorno.

**Returns:**
valor String

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Obtém o número total de itens de contorno em todos os níveis na hierarquia de contorno do documento.

**Returns:**
valor int

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Verifique se o item de contorno que representa o próximo item está relativo a este item na hierarquia de contorno.

**Returns:**
valor booleano

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Insere o item de contorno na coleção no local especificado.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém o valor que indica se o acesso a esta coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Retorna um enumerador que itera através da coleção.

**Returns:**
Um objeto System.Collections.IEnumerator que pode ser usado para iterar através da coleção.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Remove o item por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do item a ser excluído. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Ainda não suportado. Sempre lança NotImplementedException

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Define a ação para este item de contorno.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Define a marcação em negrito para o texto do título deste item de contorno

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setColor {#setColor-java.awt.Color-}
Define a cor para o texto do título deste item de contorno.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Define o destino para este item de contorno.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Define a marcação em itálico para o texto do título deste item de contorno

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Define o status aberto (true/false) para o item de contorno.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTitle {#setTitle-java.lang.String-}
Define o título para este item de contorno.

### size {#size--}
```
public int size()
```

Contagem de itens da coleção. Por favor, não confunda com VisibleCount: VisibleCount obtém o número de itens de contorno visíveis em todos os níveis.

**Returns:**
valor int
