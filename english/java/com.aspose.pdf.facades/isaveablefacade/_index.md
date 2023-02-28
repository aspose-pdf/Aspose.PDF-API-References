---
title: ISaveableFacade
second_title: Aspose.PDF for Java API Reference
description: Facade interface that defines methods common for all saveable facades.
type: docs
weight: 65
url: /java/com.aspose.pdf.facades/isaveablefacade/
---
**All Implemented Interfaces:**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public interface ISaveableFacade extends IFacade
```

Facade interface that defines methods common for all saveable facades.
## Methods

| Method | Description |
| --- | --- |
| [save(String destFile)](#save-java.lang.String-) | Saves the result PDF document to file. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the result PDF document to stream. |
### save(String destFile) {#save-java.lang.String-}
```
public abstract void save(String destFile)
```


Saves the result PDF document to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | String object |

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream destStream)
```


Saves the result PDF document to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | OutputStream object |

