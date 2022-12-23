---
title: DocMDPSignature
second_title: Aspose.PDF for Java API Reference
description: Represents the class of document MDP modification detection and prevention signature type.
type: docs
weight: 90
url: /java/com.aspose.pdf/docmdpsignature/
---
**Inheritance:**
java.lang.Object
```
public final class DocMDPSignature
```

Represents the class of document MDP (modification detection and prevention) signature type.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocMDPSignature(Signature signature, int accessPermissions)](#DocMDPSignature-com.aspose.pdf.Signature-int-) | Initializes a new instance of the  DocMDPSignature  class. |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Returns the signature object that used during signing. |
| [getAccessPermissions()](#getAccessPermissions--) | Returns the access permissions granted for this document. |
### DocMDPSignature(Signature signature, int accessPermissions) {#DocMDPSignature-com.aspose.pdf.Signature-int-}
```
public DocMDPSignature(Signature signature, int accessPermissions)
```


Initializes a new instance of the  DocMDPSignature  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [Signature](../../com.aspose.pdf/signature) | The signature object that used during signing. |
| accessPermissions | int | The access permissions granted for this document. |

### getSignature() {#getSignature--}
```
public Signature getSignature()
```


Returns the signature object that used during signing.

**Returns:**
[Signature](../../com.aspose.pdf/signature) - Signature object
### getAccessPermissions() {#getAccessPermissions--}
```
public int getAccessPermissions()
```


Returns the access permissions granted for this document.

**Returns:**
int - DocMDPAccessPermissions element
