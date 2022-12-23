---
title: KeySize
second_title: Aspose.PDF for Java API Reference
description: Defines different key sizes which can be used to encrypt pdf documents.
type: docs
weight: 32
url: /java/com.aspose.pdf.facades/keysize/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class KeySize extends System.Enum
```

Defines different key sizes which can be used to encrypt pdf documents.
## Fields

| Field | Description |
| --- | --- |
| [x40](#x40) | 40 bit key. |
| [x128](#x128) | 128 bit key. |
| [x256](#x256) | 256 bit key. |
### x40 {#x40}
```
public static final int x40
```


40 bit key. Such key size is used with RC4 algorithm and provides low level of security. Nevertheless old versions of pdf documents can be encrypted only with such keys (v. 1.3 and lower);

### x128 {#x128}
```
public static final int x128
```


128 bit key. Both RC4 and AES algorithms can use such key size.

### x256 {#x256}
```
public static final int x256
```


256 bit key. Such key size can be used only with AES and is recognized with the last Adobe Reader versions (starting from v.9).

