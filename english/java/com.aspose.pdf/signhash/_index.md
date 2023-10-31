---
title: Signature.SignHash
second_title: Aspose.PDF for Java API Reference
description: Delegate for custom sign the document hash Beta.
type: docs
weight: 10
url: /java/com.aspose.pdf/signature.signhash/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class Signature.SignHash extends System.MulticastDelegate
```

Delegate for custom sign the document hash (Beta).
## Constructors

| Constructor | Description |
| --- | --- |
| [SignHash()](#SignHash--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(byte[] hash)](#invoke-byte---) | Delegate for custom sign the document hash (Beta). |
| [beginInvoke(byte[] hash, System.AsyncCallback callback, Object state)](#beginInvoke-byte---com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### SignHash() {#SignHash--}
```
public SignHash()
```


### invoke(byte[] hash) {#invoke-byte---}
```
public abstract byte[] invoke(byte[] hash)
```


Delegate for custom sign the document hash (Beta).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hash | byte[] | Input hash of the document. |

**Returns:**
byte[] - Output signature.
### beginInvoke(byte[] hash, System.AsyncCallback callback, Object state) {#beginInvoke-byte---com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(byte[] hash, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hash | byte[] |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final byte[] endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
byte[]
