---
title: "Layer"
linktitle: "Layer"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma camada dentro de uma página PDF."
type: docs
weight: 2640
url: /pt/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Representa uma camada dentro de uma página PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe {@code Layer}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [delete](#delete--) | Exclui a camada atual do documento PDF. |
| [flatten](#flatten-boolean-) | Achata a camada especificada. |
| [getContents](#getContents--) | <p> Obtém o conteúdo da camada. </p> |
| [getDefaultState](#getDefaultState--) | Obtém o estado padrão da camada PDF. |
| [getId](#getId--) | Obtém o ID da camada. |
| [getLocked](#getLocked--) | Obtém um valor que indica se a camada está bloqueada. |
| [getName](#getName--) | Obtém o nome da camada. |
| [lock](#lock--) | Bloqueia a camada. |
| [save](#save-java.io.OutputStream-) | Salva a camada atual em um documento PDF. |
| [save](#save-java.lang.String-) | Salva a camada atual em um documento PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Define o estado padrão da camada PDF. |
| [unlock](#unlock--) | Desbloqueia a camada. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Inicializa uma nova instância da classe {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Exclui a camada atual do documento PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Achata a camada especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cleanupContentStream |  | Especifica se deve remover marcadores de grupo de conteúdo opcional do fluxo de conteúdo. Definir o parâmetro {@code cleanupContentStream} como false acelera o processo de achatamento. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Obtém o conteúdo da camada. </p>

**Returns:**
objeto {@code List<Operator>}

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Obtém o estado padrão da camada PDF.

**Returns:**
o estado padrão da camada PDF.

### getId {#getId--}
```
public String getId()
```

Obtém o ID da camada.

**Returns:**
valor String

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Obtém um valor que indica se a camada está bloqueada.

**Returns:**
valor booleano

### getName {#getName--}
```
public String getName()
```

Obtém o nome da camada.

**Returns:**
valor String

### lock {#lock--}
```
public final void lock()
```

Bloqueia a camada.

### save {#save-java.io.OutputStream-}
Salva a camada atual em um documento PDF.

### save {#save-java.lang.String-}
Salva a camada atual em um documento PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Define o estado padrão da camada PDF.

### unlock {#unlock--}
```
public final void unlock()
```

Desbloqueia a camada.
