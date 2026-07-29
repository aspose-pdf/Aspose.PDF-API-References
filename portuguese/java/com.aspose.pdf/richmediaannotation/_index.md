---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que descreve RichMediaAnnotation, que permite incorporar dados de vídeo/áudio em documento PDF."
type: docs
weight: 4260
url: /pt/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Classe que descreve RichMediaAnnotation, que permite incorporar dados de vídeo/áudio em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa RichMediaAnnotation. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita visitante para esta anotação. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Adiciona dados nomeados personalizados (por exemplo, necessários para script flash). |
| [getActivateOn](#getActivateOn--) | Evento que ativa a aplicação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getContent](#getContent--) | Dados do conteúdo Rich Media. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Define ou obtém variáveis flash que são passadas ao reprodutor. |
| [getCustomPlayer](#getCustomPlayer--) | Define ou obtém reprodutor flash personalizado para reproduzir dados de vídeo/áudio. |
| [getType](#getType--) | Obtém ou define o tipo de conteúdo. Valores possíveis: Áudio, Vídeo. |
| [setActivateOn](#setActivateOn-int-) | Evento que ativa a aplicação. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Define fluxo de conteúdo. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Define ou obtém variáveis flash que são passadas ao reprodutor. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Define ou obtém reprodutor flash personalizado para reproduzir dados de vídeo/áudio. |
| [setPoster](#setPoster-java.io.InputStream-) | Define pôster da anotação. |
| [setType](#setType-int-) | Obtém ou define o tipo de conteúdo. Valores possíveis: Áudio, Vídeo. |
| [update](#update--) | Atualiza dados com parâmetros especificados. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita visitante para esta anotação.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Adiciona dados nomeados personalizados (por exemplo, necessários para script flash).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Evento que ativa a aplicação.

**Returns:**
Elemento ActivationEvent

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Dados do conteúdo Rich Media.

**Returns:**
objeto InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Define ou obtém variáveis flash que são passadas ao reprodutor.

**Returns:**
Objeto String

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Define ou obtém reprodutor flash personalizado para reproduzir dados de vídeo/áudio.

**Returns:**
objeto InputStream

### getType {#getType--}
```
public int getType()
```

Obtém ou define o tipo de conteúdo. Valores possíveis: Áudio, Vídeo.

**Returns:**
Valor ContentType @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Evento que ativa a aplicação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ActivationEvent |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Define fluxo de conteúdo.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Define ou obtém variáveis flash que são passadas ao reprodutor.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Define ou obtém reprodutor flash personalizado para reproduzir dados de vídeo/áudio.

### setPoster {#setPoster-java.io.InputStream-}
Define pôster da anotação.

### setType {#setType-int-}
```
public void setType(int value)
```

Obtém ou define o tipo de conteúdo. Valores possíveis: Áudio, Vídeo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ContentType |

### update {#update--}
```
public void update()
```

Atualiza dados com parâmetros especificados.
