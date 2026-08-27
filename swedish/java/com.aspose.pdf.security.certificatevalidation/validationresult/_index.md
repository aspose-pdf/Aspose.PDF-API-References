---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar resultatet av en valideringsprocess för ett certifikat. ValidationResult‑klassen tillhandahåller information om utfallet av en certifikatvalidering, inklusive dess."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Representerar resultatet av en valideringsprocess för ett certifikat. Klassen ValidationResult tillhandahåller information om utfallet av certifikatvalideringen, inklusive dess status och ett meddelande som beskriver eventuella problem som uppstod under valideringen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Skapar en instans av {@link ValidationResult}‑klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMessage](#getMessage--) | Representerar meddelandet som är kopplat till valideringsresultatet. Message‑egenskapen ger ytterligare sammanhang eller information om tillståndet för valideringsresultatet. |
| [getStatus](#getStatus--) | Hämtar statusen för valideringsprocessen för ett certifikat. Status‑egenskapen visar utfallet av certifikatvalideringen. Möjliga värden definieras i {@link ValidationStatus}‑enumerationen, såsom Valid, Invalid eller Undefined. Den ger en inblick i huruvida certifikatet klarade valideringskontrollerna eller inte. |
| [setMessage](#setMessage-java.lang.String-) | Representerar meddelandet som är kopplat till valideringsresultatet. Message‑egenskapen ger ytterligare sammanhang eller information om tillståndet för valideringsresultatet. |
| [setStatus](#setStatus-int-) | Hämtar statusen för valideringsprocessen för ett certifikat. Status‑egenskapen visar utfallet av certifikatvalideringen. Möjliga värden definieras i {@link ValidationStatus}‑enumerationen, såsom Valid, Invalid eller Undefined. Den ger en inblick i huruvida certifikatet klarade valideringskontrollerna eller inte. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Skapar en instans av {@link ValidationResult}‑klassen.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Representerar meddelandet som är kopplat till valideringsresultatet. Message‑egenskapen ger ytterligare sammanhang eller information om tillståndet för valideringsresultatet.

**Returns:**
String värde

### getStatus {#getStatus--}
```
public final int getStatus()
```

Hämtar statusen för valideringsprocessen för ett certifikat. Status‑egenskapen visar utfallet av certifikatvalideringen. Möjliga värden definieras i {@link ValidationStatus}‑enumerationen, såsom Valid, Invalid eller Undefined. Den ger en inblick i huruvida certifikatet klarade valideringskontrollerna eller inte.

**Returns:**
ValidationStatus‑element

### setMessage {#setMessage-java.lang.String-}
Representerar meddelandet som är kopplat till valideringsresultatet. Message‑egenskapen ger ytterligare sammanhang eller information om tillståndet för valideringsresultatet.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Hämtar statusen för valideringsprocessen för ett certifikat. Status‑egenskapen visar utfallet av certifikatvalideringen. Möjliga värden definieras i {@link ValidationStatus}‑enumerationen, såsom Valid, Invalid eller Undefined. Den ger en inblick i huruvida certifikatet klarade valideringskontrollerna eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ValidationStatus‑element |
