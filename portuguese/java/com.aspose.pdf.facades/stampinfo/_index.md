---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa informações de carimbo."
type: docs
weight: 710
url: /pt/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Classe que representa informações de carimbo.

## Métodos

| Método | Descrição |
| --- | --- |
| [getForm](#getForm--) | Obtém XForm do selo. |
| [getImage](#getImage--) | Obtém a imagem do selo. Pode ser nulo se o selo não contiver imagens (por exemplo, para selo de texto). |
| [getImageInternal](#getImageInternal--) | Obtém a imagem do selo. Pode ser nulo se o selo não contiver imagens (por exemplo, para selo de texto). |
| [getIndexOnPage](#getIndexOnPage--) | Obtém o índice do selo na página. |
| [getRectangle](#getRectangle--) | Obtém o retângulo onde o selo está colocado. |
| [getStampId](#getStampId--) | Obtém o identificador do selo. |
| [getStampType](#getStampType--) | Obtém o tipo do selo (imagem / formulário). |
| [getText](#getText--) | Obtém o texto no selo. |
| [getVisible](#getVisible--) | Obtém a visibilidade do selo. Se for false, o selo fica oculto (com HideStampById). O selo oculto pode ser restaurado por ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Obtém XForm do selo.

**Returns:**
objeto XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Obtém a imagem do selo. Pode ser nulo se o selo não contiver imagens (por exemplo, para selo de texto).

**Returns:**
objeto BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Obtém a imagem do selo. Pode ser nulo se o selo não contiver imagens (por exemplo, para selo de texto).

**Returns:**
Objeto de imagem

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Obtém o índice do selo na página.

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo onde o selo está colocado.

**Returns:**
Elemento retângulo

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtém o identificador do selo.

**Returns:**
valor int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Obtém o tipo do selo (imagem / formulário).

**Returns:**
Elemento StampType @see StampType

### getText {#getText--}
```
public String getText()
```

Obtém o texto no selo.

**Returns:**
valor String

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Obtém a visibilidade do selo. Se for false, o selo fica oculto (com HideStampById). O selo oculto pode ser restaurado por ShowStampById.

**Returns:**
valor booleano
