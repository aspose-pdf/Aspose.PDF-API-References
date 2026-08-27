---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe representa um campo de botão de pressão."
type: docs
weight: 440
url: /pt/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Classe representa um campo de botão de pressão.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ButtonField](#ButtonField--) | Construtor de campo de botão para Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Construtor de campo de botão para Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Construtor de campo de botão para Generator. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Adiciona imagem aos recursos do campo e a desenha. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Adiciona imagem aos recursos do campo e a desenha. |
| [getAlternateCaption](#getAlternateCaption--) | Obtém a legenda alternativa do botão que deve ser exibida quando o botão do mouse é pressionado dentro de sua área ativa. |
| [getAlternateIcon](#getAlternateIcon--) | Obtém o ícone alternativo que deve ser exibido quando o botão do mouse é pressionado dentro de sua área ativa. |
| [getIconFit](#getIconFit--) | Obtém o objeto de ajuste de ícone que especifica como o ícone da anotação de widget deve ser exibido dentro de seu retângulo de anotação. |
| [getICPosition](#getICPosition--) | Obtém a posição da legenda do ícone. |
| [getNormalCaption](#getNormalCaption--) | Obtém a legenda normal. |
| [getNormalIcon](#getNormalIcon--) | Obtém o ícone normal do botão que deve ser exibido quando não está interagindo com o usuário. |
| [getRolloverCaption](#getRolloverCaption--) | Obtém a legenda de rollover do botão que deve ser exibida quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse. |
| [getRolloverIcon](#getRolloverIcon--) | Obtém o ícone de rollover do botão que deve ser exibido quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Define a legenda alternativa do botão que deve ser exibida quando o botão do mouse é pressionado dentro de sua área ativa. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Define o ícone alternativo que deve ser exibido quando o botão do mouse é pressionado dentro de sua área ativa. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Define a posição da legenda do ícone. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Define a legenda normal. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Define o ícone normal do botão que deve ser exibido quando não está interagindo com o usuário. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Define a legenda de rollover do botão que deve ser exibida quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Define o ícone de rollover do botão que será exibido quando o usuário mover o cursor para sua área ativa sem pressionar o botão do mouse. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Construtor de campo de botão para Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Construtor de campo de botão para Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Construtor de campo de botão para Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Adiciona imagem aos recursos do campo e a desenha.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Adiciona imagem aos recursos do campo e a desenha.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Obtém a legenda alternativa do botão que deve ser exibida quando o botão do mouse é pressionado dentro de sua área ativa.

**Returns:**
valor String

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Obtém o ícone alternativo que deve ser exibido quando o botão do mouse é pressionado dentro de sua área ativa.

**Returns:**
objeto XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Obtém o objeto de ajuste de ícone que especifica como o ícone da anotação de widget deve ser exibido dentro de seu retângulo de anotação.

**Returns:**
Objeto IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Obtém a posição da legenda do ícone.

**Returns:**
posição da legenda do ícone. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtém a legenda normal.

**Returns:**
valor String

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Obtém o ícone normal do botão que deve ser exibido quando não está interagindo com o usuário.

**Returns:**
objeto XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Obtém a legenda de rollover do botão que deve ser exibida quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse.

**Returns:**
valor String

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Obtém o ícone de rollover do botão que deve ser exibido quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse.

**Returns:**
objeto XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Define a legenda alternativa do botão que deve ser exibida quando o botão do mouse é pressionado dentro de sua área ativa.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Define o ícone alternativo que deve ser exibido quando o botão do mouse é pressionado dentro de sua área ativa.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Define a posição da legenda do ícone.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Define a legenda normal.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Define o ícone normal do botão que deve ser exibido quando não está interagindo com o usuário.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Define a legenda de rollover do botão que deve ser exibida quando o usuário move o cursor para sua área ativa sem pressionar o botão do mouse.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Define o ícone de rollover do botão que será exibido quando o usuário mover o cursor para sua área ativa sem pressionar o botão do mouse.
