---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Referência da API Aspose.PDF para Java"
description: "Encapsula elementos de conteúdo não assinado extraídos de um documento PDF. Esta classe fornece acesso a páginas, campos de formulário, XForms e anotações que fazem parte do não assinado."
type: docs
weight: 50
url: /pt/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Encapsula elementos de conteúdo não assinado extraídos de um documento PDF. Esta classe fornece acesso a páginas, campos de formulário, XForms e anotações que fazem parte do conteúdo não assinado dentro do documento.

## Métodos

| Método | Descrição |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Obtém um dicionário de anotações modificadas que podem ter sido alteradas ou adicionadas. |
| [getForms](#getForms--) | Obtém campos de formulário que foram alterados ou adicionados incrementalmente. |
| [getPages](#getPages--) | Obtém uma lista de páginas cujo conteúdo está não assinado ou foi alterado incrementalmente. A página é considerada modificada e os XForms não são verificados e não aparecem na lista de XForms. |
| [getXForms](#getXForms--) | Obtém um dicionário de objetos XForm modificados que podem ter sido alterados, embora a própria página não tenha sido alterada (não está na lista de Pages). |
| [setXForms](#setXForms-java.util.HashMap-) | Um dicionário de objetos XForm modificados que podem ter sido alterados, embora a própria página não tenha sido alterada (não está na lista de Pages). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Obtém um dicionário de anotações modificadas que podem ter sido alteradas ou adicionadas.

**Returns:**
Um dicionário de anotações modificadas que podem ter sido alteradas ou adicionadas.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Obtém campos de formulário que foram alterados ou adicionados incrementalmente.

**Returns:**
Campos de formulário que foram alterados ou adicionados incrementalmente.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Obtém uma lista de páginas cujo conteúdo está não assinado ou foi alterado incrementalmente. A página é considerada modificada e os XForms não são verificados e não aparecem na lista de XForms.

**Returns:**
Uma lista de páginas cujo conteúdo está não assinado ou foi alterado incrementalmente.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Obtém um dicionário de objetos XForm modificados que podem ter sido alterados, embora a própria página não tenha sido alterada (não está na lista de Pages).

**Returns:**
Um dicionário de objetos XForm modificados que podem ter sido alterados, embora a própria página não tenha sido alterada (não está na lista de Pages).

### setXForms {#setXForms-java.util.HashMap-}
Um dicionário de objetos XForm modificados que podem ter sido alterados, embora a própria página não tenha sido alterada (não está na lista de Pages).
