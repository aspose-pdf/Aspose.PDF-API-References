---
title: ValidationResult
linktitle: ValidationResult
second_title: Aspose.PDF for Java API Reference
description: Represents the result of a validation process for a certificate. The ValidationResult class provides information about the outcome of validating a certificate, including its.
type: docs
weight: 40
url: /java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Represents the result of a validation process for a certificate. The ValidationResult class provides information about the outcome of validating a certificate, including its status and a message describing any issues encountered during the validation.

## Constructors

| Constructor | Description |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Creates an instance of {@link ValidationResult} class. |

## Methods

| Method | Description |
| --- | --- |
| [getMessage](#getMessage--) | Represents the message associated with the validation result. The Message property provides additional context or information about the state of the validation result. |
| [getStatus](#getStatus--) | Gets the status of the validation process for a certificate. The Status property indicates the outcome of the certificate validation. Possible values are defined in the {@link ValidationStatus} enumeration, such as Valid, Invalid, or Undefined. It provides an insight into whether the certificate passed the validation checks or not. |
| [setMessage](#setMessage-java.lang.String-) | Represents the message associated with the validation result. The Message property provides additional context or information about the state of the validation result. |
| [setStatus](#setStatus-int-) | Gets the status of the validation process for a certificate. The Status property indicates the outcome of the certificate validation. Possible values are defined in the {@link ValidationStatus} enumeration, such as Valid, Invalid, or Undefined. It provides an insight into whether the certificate passed the validation checks or not. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Creates an instance of {@link ValidationResult} class.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Represents the message associated with the validation result. The Message property provides additional context or information about the state of the validation result.

**Returns:**
String value

### getStatus {#getStatus--}
```
public final int getStatus()
```

Gets the status of the validation process for a certificate. The Status property indicates the outcome of the certificate validation. Possible values are defined in the {@link ValidationStatus} enumeration, such as Valid, Invalid, or Undefined. It provides an insight into whether the certificate passed the validation checks or not.

**Returns:**
ValidationStatus element

### setMessage {#setMessage-java.lang.String-}
Represents the message associated with the validation result. The Message property provides additional context or information about the state of the validation result.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Gets the status of the validation process for a certificate. The Status property indicates the outcome of the certificate validation. Possible values are defined in the {@link ValidationStatus} enumeration, such as Valid, Invalid, or Undefined. It provides an insight into whether the certificate passed the validation checks or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ValidationStatus element |
