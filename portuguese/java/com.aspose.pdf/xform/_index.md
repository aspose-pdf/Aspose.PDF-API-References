---
title: "XForm"
linktitle: "XForm"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa XForm"
type: docs
weight: 5590
url: /pt/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Classe que representa XForm

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Libera memória |
| [containsOwnResources](#containsOwnResources--) | Retorna True se contém Recursos Próprios |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Cria um novo XForm no documento. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Cria um XForm que duplica o conteúdo da página. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Libera memória |
| [freeMemory](#freeMemory--) | Limpa os dados em cache |
| [getBBox](#getBBox--) | Obtém a caixa delimitadora do formulário. |
| [getContents](#getContents--) | Obtém os operadores do formulário. |
| [getEngineObj](#getEngineObj--) | Somente interno |
| [getIT](#getIT--) | Obtém o IT do formulário. O IT do formulário é um nome que descreve a intenção do XObject. |
| [getMatrix](#getMatrix--) | Obtém a matriz do formulário. |
| [getName](#getName--) | Obtém o nome do formulário. O nome do formulário é o nome usado para referenciar o formulário no dicionário XObejct nos recursos da página. |
| [getOpi](#getOpi--) | Obtém a Interface de Pré-impressão Aberta (OPI). |
| [getRectangle](#getRectangle--) | Obtém o retângulo do formulário. |
| [getResources](#getResources--) | Retorna os recursos do Form X-Object. Se o Form não possuir recursos e allowCreate for true, os Resources serão criados automaticamente para o formulário. |
| [getResources](#getResources-boolean-) | Retorna os recursos do Form X-Object |
| [getResourcesField](#getResourcesField--) | Obtém os recursos do Form XObject. |
| [getSubtype](#getSubtype--) | Obtém o Subtipo do formulário. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Define a caixa delimitadora do formulário. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Define a matriz do formulário. |
| [setName](#setName-java.lang.String-) | Define o nome do formulário. O nome do formulário é o nome usado para referenciar o formulário no dicionário XObejct nos recursos da página. |

### close {#close--}
```
public final void close()
```

Libera memória

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Retorna True se contém Recursos Próprios

**Returns:**
valor booleano

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Cria um novo XForm no documento.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Cria um XForm que duplica o conteúdo da página.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Libera memória

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Limpa os dados em cache

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Obtém a caixa delimitadora do formulário.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Obtém os operadores do formulário.

**Returns:**
Objeto OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Somente interno

**Returns:**
Objeto IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

Obtém o IT do formulário. O IT do formulário é um nome que descreve a intenção do XObject.

**Returns:**
valor String

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Obtém a matriz do formulário.

**Returns:**
Matriz

### getName {#getName--}
```
public String getName()
```

Obtém o nome do formulário. O nome do formulário é o nome usado para referenciar o formulário no dicionário XObejct nos recursos da página.

**Returns:**
String

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Obtém a Interface de Pré-impressão Aberta (OPI).

**Returns:**
Instância Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo do formulário.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Retorna os recursos do Form X-Object. Se o Form não possuir recursos e allowCreate for true, os Resources serão criados automaticamente para o formulário.

**Returns:**
Instância Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Retorna os recursos do Form X-Object

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| allowCreate |  | Se o Form não possuir recursos e allowCreate for true, os Resources serão criados automaticamente para o formulário. |

**Returns:**
Instância Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Obtém os recursos do Form XObject.

**Returns:**
Instância Resources. Se o Form não possuir recursos, os Resources serão criados automaticamente para o formulário.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Obtém o Subtipo do formulário.

**Returns:**
valor String

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Define a caixa delimitadora do formulário.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Define a matriz do formulário.

### setName {#setName-java.lang.String-}
Define o nome do formulário. O nome do formulário é o nome usado para referenciar o formulário no dicionário XObejct nos recursos da página.
