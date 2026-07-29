---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la configuración OCSP utilizada durante el proceso de firma."
type: docs
weight: 5360
url: /es/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Representa la configuración OCSP utilizada durante el proceso de firma.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Inicializa una nueva instancia de la clase {@code TimestampSettings}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Obtiene las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Obtiene/establece el algoritmo de resumen para funciones hash internas. |
| [getServerUrl](#getServerUrl--) | Obtiene la URL del servidor de marca de tiempo. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Establece las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Obtiene/establece el algoritmo de resumen para funciones hash internas. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Establece la URL del servidor de marca de tiempo. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Inicializa una nueva instancia de la clase {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Inicializa una nueva instancia de la clase {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Obtiene las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password".

**Returns:**
valor String

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Obtiene/establece el algoritmo de resumen para funciones hash internas.

**Returns:**
DigestHashAlgorithm elemento @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Obtiene la URL del servidor de marca de tiempo.

**Returns:**
valor String

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Establece las credenciales de autenticación básica, el nombre de usuario y la contraseña se combinan en una cadena "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Obtiene/establece el algoritmo de resumen para funciones hash internas.

### setServerUrl {#setServerUrl-java.lang.String-}
Establece la URL del servidor de marca de tiempo.
