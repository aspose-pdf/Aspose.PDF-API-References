---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma anotação de som que contém áudio gravado do microfone do computador ou importado de um arquivo."
type: docs
weight: 4530
url: /pt/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Representa uma anotação de som que contém áudio gravado do microfone do computador ou importado de um arquivo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Cria nova anotação Sound na página especificada. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Cria nova anotação Sound na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getIcon](#getIcon--) | Obtém um ícone a ser usado na exibição da anotação. |
| [getSoundData](#getSoundData--) | Obtém um objeto de som que define o som a ser reproduzido quando a anotação é ativada. |
| [setIcon](#setIcon-int-) | Define um ícone a ser usado na exibição da anotação. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Cria nova anotação Sound na página especificada.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Cria nova anotação Sound na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Valor AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtém um ícone a ser usado na exibição da anotação.

**Returns:**
Valor SoundIcon @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Obtém um objeto de som que define o som a ser reproduzido quando a anotação é ativada.

**Returns:**
Valor SoundData

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Define um ícone a ser usado na exibição da anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor SoundIcon @see SoundIcon |
