---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Referência da API Aspose.PDF para Java"
description: "Executa modificações de conteúdo apenas no modo APPEND. Este modo permite evitar a análise desnecessária e pesada do conteúdo antes que alguma alteração seja feita no conteúdo. Ele apenas adiciona novos."
type: docs
weight: 800
url: /pt/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Executa modificações de conteúdo apenas no modo APPEND. Este modo permite evitar a análise desnecessária e pesada do conteúdo antes de qualquer alteração ser feita. Ele apenas adiciona novos operadores ao final ou ao início do conteúdo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Inicializa nova instância do contents appender com página anexada |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Inicializa nova instância do contents appender com Form XObject. |

## Métodos

| Método | Descrição |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Anexa operadores ao final do conteúdo |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Anexa operador ao final do conteúdo |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Anexa operadores ao final do conteúdo |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Anexa operadores ao início do conteúdo |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Anexa operador ao início do conteúdo |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Anexa operadores ao início do conteúdo |
| [getBeginCode](#getBeginCode--) | String contendo operadores para inserir no início da página. |
| [getBeginOperators](#getBeginOperators--) | <p> retorna operadores iniciais </p> |
| [getEndCode](#getEndCode--) | String contendo operadores para anexar ao final da página. |
| [getEndOperators](#getEndOperators--) | <p> retorna operadores finais </p> |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento |
| [setBeginCode](#setBeginCode-java.lang.String-) | String contendo operadores para inserir no início da página. |
| [setEndCode](#setEndCode-java.lang.String-) | String contendo operadores para inserir no início da página. |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização dos dados de conteúdo. O conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| [updateData](#updateData--) | Esta é a nova versão de UpdateData, que evita a decodificação do conteúdo existente. |
| [updateDataOld](#updateDataOld--) | Deve ser chamado para aplicar as alterações |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Inicializa nova instância do contents appender com página anexada

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Inicializa nova instância do contents appender com Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Anexa operadores ao final do conteúdo

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Anexa operador ao final do conteúdo

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Anexa operadores ao final do conteúdo

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Anexa operadores ao início do conteúdo

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Anexa operador ao início do conteúdo

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Anexa operadores ao início do conteúdo

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

String contendo operadores para inserir no início da página.

**Returns:**
Objeto String

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> retorna operadores iniciais </p>

**Returns:**
objeto {@code List<Operator>}

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

String contendo operadores para anexar ao final da página.

**Returns:**
Objeto String

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> retorna operadores finais </p>

**Returns:**
objeto {@code List<Operator>}

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Retoma a atualização do documento

### setBeginCode {#setBeginCode-java.lang.String-}
String contendo operadores para inserir no início da página.

### setEndCode {#setEndCode-java.lang.String-}
String contendo operadores para inserir no início da página.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime a atualização dos dados de conteúdo. O conteúdo não é atualizado até que ResumeUpdate seja chamado.

### updateData {#updateData--}
```
public void updateData()
```

Esta é a nova versão de UpdateData, que evita a decodificação do conteúdo existente.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Deve ser chamado para aplicar as alterações
