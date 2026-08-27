---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Referência da API Aspose.PDF para Java"
description: "As permissões de acesso concedidas para este documento. Valores válidos são: 1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura. 2 -."
type: docs
weight: 1010
url: /pt/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

As permissões de acesso concedidas para este documento. Valores válidos são: 1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura. 2 - Alterações permitidas são o preenchimento de formulários, a instanciação de modelos de página e a assinatura; outras alterações invalida a assinatura. 3 - Alterações permitidas são as mesmas da opção 2, além da criação, exclusão e modificação de anotações; outras alterações invalida a assinatura.

## Campos

| Campo | Descrição |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - As alterações permitidas são as mesmas que para 2, além da criação, exclusão e modificação de anotações; outras alterações invalidam a assinatura. |
| [FillingInForms](#FillingInForms) | 2 - As alterações permitidas são o preenchimento de formulários, a instanciação de modelos de página e a assinatura; outras alterações invalidam a assinatura. |
| [NoChanges](#NoChanges) | 1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - As alterações permitidas são as mesmas que para 2, além da criação, exclusão e modificação de anotações; outras alterações invalidam a assinatura.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - As alterações permitidas são o preenchimento de formulários, a instanciação de modelos de página e a assinatura; outras alterações invalidam a assinatura.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Nenhuma alteração no documento é permitida; qualquer alteração no documento invalida a assinatura.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
