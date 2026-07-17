---
title: TimestampSettings
linktitle: TimestampSettings
second_title: Aspose.PDF for Java API Reference
description: Represents the ocsp settings using during signing process.
type: docs
weight: 5360
url: /java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Represents the ocsp settings using during signing process.

## Constructors

| Constructor | Description |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Initializes a new instance of the {@code TimestampSettings} class. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Initializes a new instance of the {@code TimestampSettings} class. |

## Methods

| Method | Description |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Gets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Gets/sets the digest algorithm for internal hash functions. |
| [getServerUrl](#getServerUrl--) | Gets the timestamp server url. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Sets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Gets/sets the digest algorithm for internal hash functions. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Sets the timestamp server url. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Initializes a new instance of the {@code TimestampSettings} class.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Initializes a new instance of the {@code TimestampSettings} class.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Gets the basic authentication credentials, Username and password are combined into a string "username:password".

**Returns:**
String value

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Gets/sets the digest algorithm for internal hash functions.

**Returns:**
DigestHashAlgorithm element @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Gets the timestamp server url.

**Returns:**
String value

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Sets the basic authentication credentials, Username and password are combined into a string "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Gets/sets the digest algorithm for internal hash functions.

### setServerUrl {#setServerUrl-java.lang.String-}
Sets the timestamp server url.
