---
title: TimestampSettings
second_title: Aspose.PDF for Java API Reference
description: Represents the ocsp settings using during signing process.
type: docs
weight: 391
url: /java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object
```
public class TimestampSettings
```

Represents the ocsp settings using during signing process.
## Constructors

| Constructor | Description |
| --- | --- |
| [TimestampSettings(String serverUrl, String basicAuthCredentials)](#TimestampSettings-java.lang.String-java.lang.String-) | Initializes a new instance of the  TimestampSettings  class. |
| [TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)](#TimestampSettings-java.lang.String-java.lang.String-int-) | Initializes a new instance of the  TimestampSettings  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasicAuthCredentials()](#getBasicAuthCredentials--) | Gets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [getClass()](#getClass--) |  |
| [getDigestHashAlgorithm()](#getDigestHashAlgorithm--) | Gets/sets the digest algorithm for internal hash functions. |
| [getServerUrl()](#getServerUrl--) | Gets the timestamp server url. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasicAuthCredentials(String value)](#setBasicAuthCredentials-java.lang.String-) | Sets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [setDigestHashAlgorithm(int value)](#setDigestHashAlgorithm-int-) | Gets/sets the digest algorithm for internal hash functions. |
| [setServerUrl(String value)](#setServerUrl-java.lang.String-) | Sets the timestamp server url. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TimestampSettings(String serverUrl, String basicAuthCredentials) {#TimestampSettings-java.lang.String-java.lang.String-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials)
```


Initializes a new instance of the  TimestampSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverUrl | java.lang.String | The timestamp server url. |
| basicAuthCredentials | java.lang.String | The basic authentication credentials, username and password are combined into a string "username:password". |

### TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm) {#TimestampSettings-java.lang.String-java.lang.String-int-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)
```


Initializes a new instance of the  TimestampSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverUrl | java.lang.String | The timestamp server url. |
| basicAuthCredentials | java.lang.String | The basic authentication credentials, username and password are combined into a string "username:password". |
| digestHashAlgorithm | int | The hash algorithm name, if it is omitted then sha1 is used. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBasicAuthCredentials() {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```


Gets the basic authentication credentials, Username and password are combined into a string "username:password".

**Returns:**
java.lang.String - String value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigestHashAlgorithm() {#getDigestHashAlgorithm--}
```
public final int getDigestHashAlgorithm()
```


Gets/sets the digest algorithm for internal hash functions.

**Returns:**
int - DigestHashAlgorithm element
### getServerUrl() {#getServerUrl--}
```
public String getServerUrl()
```


Gets the timestamp server url.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBasicAuthCredentials(String value) {#setBasicAuthCredentials-java.lang.String-}
```
public void setBasicAuthCredentials(String value)
```


Sets the basic authentication credentials, Username and password are combined into a string "username:password".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setDigestHashAlgorithm(int value) {#setDigestHashAlgorithm-int-}
```
public final void setDigestHashAlgorithm(int value)
```


Gets/sets the digest algorithm for internal hash functions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | DigestHashAlgorithm element |

### setServerUrl(String value) {#setServerUrl-java.lang.String-}
```
public void setServerUrl(String value)
```


Sets the timestamp server url.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

