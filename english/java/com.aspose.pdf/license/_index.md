---
title: License
linktitle: License
second_title: Aspose.PDF for Java API Reference
description: Provides methods to license the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the.
type: docs
weight: 2670
url: /java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Provides methods to license the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic");

## Constructors

| Constructor | Description |
| --- | --- |
| [License](#License--) | Initializes a new instance of this class. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic"); |

## Methods

| Method | Description |
| --- | --- |
| [clearLicense](#clearLicense--) | Clears the current license. |
| [getLicenseInfo](#getLicenseInfo--) | Gets the current license information. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | By default, we are using default jdk security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | By default, we are using default jre security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security. <p> Notice also: According to JVM SecureRandom algorithm on some operating systems /dev/random waits for a certain amount of “noise” to be generated on the host machine before returning a result. The library used for random number generation in Oracle’s JVM relies on /dev/random by default for UNIX platforms. Although /dev/random is more secure, it’s recommended to use /dev/urandom if the default JVM configuration have delays, or add devices that generate entropy for /dev/random. <p> The following java option can helps to avoid delays and override the securerandom.source setting. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licenses the component. A stream that contains the license. Use this method to load a license from a stream. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licenses the component. Tries to find the license in the following locations: 1. Explicit path. 2. The folder of the component jar file. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Initializes a new instance of this class. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Clears the current license.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Gets the current license information.

**Returns:**
LicenseInfo instance

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

By default, we are using default jdk security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security.

**Returns:**
boolean value

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

By default, we are using default jre security. Default value == false. In some cases customized java environment can't support required algorithms, so we can suggest to use internal build-in FIPS security. <p> Notice also: According to JVM SecureRandom algorithm on some operating systems /dev/random waits for a certain amount of “noise” to be generated on the host machine before returning a result. The library used for random number generation in Oracle’s JVM relies on /dev/random by default for UNIX platforms. Although /dev/random is more secure, it’s recommended to use /dev/urandom if the default JVM configuration have delays, or add devices that generate entropy for /dev/random. <p> The following java option can helps to avoid delays and override the securerandom.source setting. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalFIPSSecurity |  | boolean value |

### setLicense {#setLicense-java.io.InputStream-}
Licenses the component. A stream that contains the license. Use this method to load a license from a stream. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licenses the component. Tries to find the license in the following locations: 1. Explicit path. 2. The folder of the component jar file. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. License license = new License(); license.setLicense("MyLicense.lic");
