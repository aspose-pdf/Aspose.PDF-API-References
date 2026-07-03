---
title: CompromiseCheckResult
second_title: Aspose.PDF for Java API Reference
description: Represents a class for checking document digital signatures for compromise.
type: docs
weight: 10
url: /java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Represents a class for checking document digital signatures for compromise.

## Fields

| Field | Description |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Gets a collection of digital signatures that have been identified as compromised. This property contains the list of all compromised signatures detected in the document. |

## Methods

| Method | Description |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Gets the coverage state of digital signatures in a document. If it is equal to {@code SignaturesCoverage#Undefined}, then one of the signatures is compromised. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indicates whether there are any compromised digital signatures in the document. Returns true if at least one signature is compromised; otherwise, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Gets a collection of digital signatures that have been identified as compromised. This property contains the list of all compromised signatures detected in the document.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Gets the coverage state of digital signatures in a document. If it is equal to {@code SignaturesCoverage#Undefined}, then one of the signatures is compromised.

**Returns:**
SignaturesCoverage element

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indicates whether there are any compromised digital signatures in the document. Returns true if at least one signature is compromised; otherwise, false.

**Returns:**
boolean value
