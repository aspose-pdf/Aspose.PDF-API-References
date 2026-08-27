---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma ação ir-para remota que é semelhante a uma ação ir-para comum, mas salta para um destino em outro arquivo PDF em vez do arquivo atual."
type: docs
weight: 1820
url: /pt/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

Representa uma ação ir-para remota que é semelhante a uma ação ir-para comum, mas salta para um destino em outro arquivo PDF em vez do arquivo atual.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Inicializa o objeto GoToRemoteAction. |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | Inicializa o objeto GoToRemoteAction. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFile](#getFile--) | Obtém a especificação do arquivo em que o destino está localizado. |
| [getNewWindow](#getNewWindow--) | Obtém uma bandeira que especifica se o documento de destino deve ser aberto em uma nova janela. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * Obtém o destino para o qual pular. / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Define a especificação do arquivo em que o destino está localizado. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Define uma bandeira que especifica se o documento de destino deve ser aberto em uma nova janela. |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
Inicializa o objeto GoToRemoteAction.

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
Inicializa o objeto GoToRemoteAction.

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtém a especificação do arquivo em que o destino está localizado.

**Returns:**
Objeto FileSpecification

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Obtém uma bandeira que especifica se o documento de destino deve ser aberto em uma nova janela.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * Obtém o destino para o qual pular. / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Define a especificação do arquivo em que o destino está localizado.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Define uma bandeira que especifica se o documento de destino deve ser aberto em uma nova janela.
