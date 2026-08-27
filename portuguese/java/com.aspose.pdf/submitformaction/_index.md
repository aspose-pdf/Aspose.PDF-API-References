---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que descreve a ação submit-form."
type: docs
weight: 4690
url: /pt/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Classe que descreve a ação submit-form.

## Campos

| Campo | Descrição |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Se definido, quaisquer valores de campo enviados que representem datas deverão ser convertidos para o formato padrão. |
| [EMBED_FORM](#EMBED_FORM) | Se definido, a entrada F do FDF enviado deverá ser uma especificação de arquivo contendo um fluxo de arquivo incorporado que representa o arquivo PDF do qual o FDF está sendo enviado. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Se definido, o FDF enviado deverá excluir a entrada F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Se definido, deverá incluir apenas as anotações de marcação cuja entrada T corresponda ao nome do usuário atual. |
| [EXCLUDE](#EXCLUDE) | Se limpo, o array Fields especifica quais campos incluir na submissão. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Se definido, os nomes e valores dos campos deverão ser enviados no formato de Formulário HTML. |
| [GET_METHOD](#GET_METHOD) | Se definido, os nomes e valores dos campos deverão ser enviados usando uma requisição HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Se definido, o arquivo FDF enviado deverá incluir todas as anotações de marcação no documento PDF subjacente. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Se definido, o arquivo FDF enviado deverá incluir o conteúdo de todas as atualizações incrementais. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Se definido, todos os campos designados pelo array Fields e pela flag Incluir/Excluir deverão ser enviados. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Se definido, as coordenadas do clique do mouse que causou a ação submit-form deverão ser transmitidas como parte dos dados do formulário. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Se definido, o documento deverá ser enviado como PDF, usando o tipo de conteúdo MIME application/pdf. |
| [XFDF](#XFDF) | Se definido, os nomes e valores dos campos deverão ser enviados como XFDF. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Inicializa o objeto SubmitFormAction. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFlags](#getFlags--) | Obtém as flags da ação de envio. |
| [getUrl](#getUrl--) | URL de destino. |
| [setFlags](#setFlags-int-) | Define as flags da ação de envio. |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | URL de destino. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Se definido, quaisquer valores de campo enviados que representem datas deverão ser convertidos para o formato padrão.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Se definido, a entrada F do FDF enviado deverá ser uma especificação de arquivo contendo um fluxo de arquivo incorporado que representa o arquivo PDF do qual o FDF está sendo enviado.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Se definido, o FDF enviado deverá excluir a entrada F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Se definido, deverá incluir apenas as anotações de marcação cuja entrada T corresponda ao nome do usuário atual.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Se limpo, o array Fields especifica quais campos incluir na submissão.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Se definido, os nomes e valores dos campos deverão ser enviados no formato de Formulário HTML.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Se definido, os nomes e valores dos campos deverão ser enviados usando uma requisição HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Se definido, o arquivo FDF enviado deverá incluir todas as anotações de marcação no documento PDF subjacente.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Se definido, o arquivo FDF enviado deverá incluir o conteúdo de todas as atualizações incrementais.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Se definido, todos os campos designados pelo array Fields e pela flag Incluir/Excluir deverão ser enviados.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Se definido, as coordenadas do clique do mouse que causou a ação submit-form deverão ser transmitidas como parte dos dados do formulário.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Se definido, o documento deverá ser enviado como PDF, usando o tipo de conteúdo MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Se definido, os nomes e valores dos campos deverão ser enviados como XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Inicializa o objeto SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtém as flags da ação de envio.

**Returns:**
valor int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

URL de destino.

**Returns:**
Valor FileSpecification

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Define as flags da ação de envio.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
URL de destino.
