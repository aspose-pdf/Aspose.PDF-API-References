---
title: License
second_title: Aspose.PDF for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 195
url: /java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | By default we using default jdk security. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | By default we are using default jre security. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


By default we using default jdk security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security.

**Returns:**
boolean - boolean value
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


By default we are using default jre security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security.

Notice also: According to JVM SecureRandom algorithm on some operating systems /dev/random waits for a certain amount of \\u201cnoise\\u201d to be generated on the host machine before returning a result. The library used for random number generation in Oracle\\u2019s JVM relies on /dev/random by default for UNIX platforms. Although /dev/random is more secure, it\\u2019s recommended to use /dev/urandom if the default JVM configuration have delays, or add devices that generate entropy for /dev/random.

The following java option can helps to avoid delays and override the securerandom.source setting. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalFIPSSecurity | boolean | boolean value |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licenses the component.

Tries to find the license in the following locations:

1. Explicit path.

2. The folder of the component jar file.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Can be a full or short file name or name of an embedded resource Use an empty string to switch to evaluation mode |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licenses the component.

A stream that contains the license.

Use this method to load a license from a stream.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | license Stream |

