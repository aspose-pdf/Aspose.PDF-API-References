---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Referência da API Aspose.PDF para Java"
description: "Este enum representa os tipos de senha conhecidos usados para documentos PDF protegidos por senha."
type: docs
weight: 3520
url: /pt/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Este enum representa os tipos de senha conhecidos usados para documentos PDF protegidos por senha.

## Campos

| Campo | Descrição |
| --- | --- |
| [Inaccessible](#Inaccessible) | O documento PDF está protegido por senha, mas as senhas de usuário e de proprietário não estão vazias e nenhuma das senhas foi definida ou a senha fornecida estava incorreta. |
| [None](#None) | O documento PDF não está protegido por senha. |
| [Owner](#Owner) | O documento PDF foi aberto usando a senha de alteração de permissões (acesso total). |
| [User](#User) | O documento PDF foi aberto usando a senha de abertura do documento (acesso restrito). |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

O documento PDF está protegido por senha, mas as senhas de usuário e de proprietário não estão vazias e nenhuma das senhas foi definida ou a senha fornecida estava incorreta.

### None {#None}
```
public static final PasswordType None
```

O documento PDF não está protegido por senha.

### Owner {#Owner}
```
public static final PasswordType Owner
```

O documento PDF foi aberto usando a senha de alteração de permissões (acesso total).

### User {#User}
```
public static final PasswordType User
```

O documento PDF foi aberto usando a senha de abertura do documento (acesso restrito).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
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
public static PasswordType [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
