---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa as configurações OCSP usadas durante o processo de assinatura."
type: docs
weight: 5360
url: /pt/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Representa as configurações OCSP usadas durante o processo de assinatura.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Inicializa uma nova instância da classe {@code TimestampSettings}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Obtém as credenciais de autenticação básica, Username e password são combinados em uma string "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Obtém/define o algoritmo de digestão para funções de hash internas. |
| [getServerUrl](#getServerUrl--) | Obtém a URL do servidor de timestamp. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Define as credenciais de autenticação básica, Username e password são combinados em uma string "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Obtém/define o algoritmo de digestão para funções de hash internas. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Define a URL do servidor de timestamp. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Inicializa uma nova instância da classe {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Inicializa uma nova instância da classe {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Obtém as credenciais de autenticação básica, Username e password são combinados em uma string "username:password".

**Returns:**
valor String

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Obtém/define o algoritmo de digestão para funções de hash internas.

**Returns:**
Elemento DigestHashAlgorithm @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Obtém a URL do servidor de timestamp.

**Returns:**
valor String

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Define as credenciais de autenticação básica, Username e password são combinados em uma string "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Obtém/define o algoritmo de digestão para funções de hash internas.

### setServerUrl {#setServerUrl-java.lang.String-}
Define a URL do servidor de timestamp.
