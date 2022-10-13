---
title: License
second_title: Aspose.PDF for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 159
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

