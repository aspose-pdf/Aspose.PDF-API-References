---
title: DocMDPAccessPermissions
second_title: Aspose.PDF for Java API Reference
description: The access permissions granted for this document.
type: docs
weight: 91
url: /java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DocMDPAccessPermissions extends System.Enum
```

The access permissions granted for this document. Valid values are: 1 - No changes to the document are permitted; any change to the document invalidates the signature. 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature.
## Fields

| Field | Description |
| --- | --- |
| [NoChanges](#NoChanges) | 1 - No changes to the document are permitted; any change to the document invalidates the signature. |
| [FillingInForms](#FillingInForms) | 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. |
| [AnnotationModification](#AnnotationModification) | 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature. |
### NoChanges {#NoChanges}
```
public static final int NoChanges
```


1 - No changes to the document are permitted; any change to the document invalidates the signature.

### FillingInForms {#FillingInForms}
```
public static final int FillingInForms
```


2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature.

### AnnotationModification {#AnnotationModification}
```
public static final int AnnotationModification
```


3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature.

