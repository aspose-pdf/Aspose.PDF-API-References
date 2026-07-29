---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Überprüfen digitaler Signaturen eines Dokuments auf Kompromittierung bereit."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Stellt eine Klasse zum Überprüfen digitaler Signaturen eines Dokuments auf Kompromittierung bereit.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Liefert eine Sammlung von digitalen Signaturen, die als kompromittiert identifiziert wurden. Diese Eigenschaft enthält die Liste aller im Dokument erkannten kompromittierten Signaturen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Liefert den Abdeckungsstatus digitaler Signaturen in einem Dokument. Ist er gleich {@code SignaturesCoverage#Undefined}, ist eine der Signaturen kompromittiert. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Gibt an, ob im Dokument digitale Signaturen kompromittiert sind. Gibt true zurück, wenn mindestens eine Signatur kompromittiert ist; andernfalls false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Liefert eine Sammlung von digitalen Signaturen, die als kompromittiert identifiziert wurden. Diese Eigenschaft enthält die Liste aller im Dokument erkannten kompromittierten Signaturen.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Liefert den Abdeckungsstatus digitaler Signaturen in einem Dokument. Ist er gleich {@code SignaturesCoverage#Undefined}, ist eine der Signaturen kompromittiert.

**Returns:**
SignaturesCoverage-Element

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Gibt an, ob im Dokument digitale Signaturen kompromittiert sind. Gibt true zurück, wenn mindestens eine Signatur kompromittiert ist; andernfalls false.

**Returns:**
boolescher Wert
