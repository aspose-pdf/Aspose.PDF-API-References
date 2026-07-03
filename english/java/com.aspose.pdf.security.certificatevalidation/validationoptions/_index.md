---
title: ValidationOptions
linktitle: ValidationOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for validating a digital signature in a PDF document.
type: docs
weight: 30
url: /java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Represents options for validating a digital signature in a PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Creates an instance of {@link ValidationOptions} class. |

## Methods

| Method | Description |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Gets or sets a value indicating whether the certificate chain should be checked during the validation process. When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be {@link ValidationStatus#Undefined}, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in {@code false}. The default value is {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Gets or sets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers. |
| [getValidationMethod](#getValidationMethod--) | Gets or sets the method used to validate a certificate. |
| [getValidationMode](#getValidationMode--) | Gets or sets the mode of validation for digital signatures in a PDF document. The ValidationMode property determines the strictness of the validation process. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Gets or sets a value indicating whether the certificate chain should be checked during the validation process. When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be {@link ValidationStatus#Undefined}, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in {@code false}. The default value is {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Gets or sets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers. |
| [setValidationMethod](#setValidationMethod-int-) | Gets or sets the method used to validate a certificate. |
| [setValidationMode](#setValidationMode-int-) | Gets or sets the mode of validation for digital signatures in a PDF document. The ValidationMode property determines the strictness of the validation process. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Creates an instance of {@link ValidationOptions} class.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Gets or sets a value indicating whether the certificate chain should be checked during the validation process. When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be {@link ValidationStatus#Undefined}, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in {@code false}. The default value is {@code false}.

**Returns:**
boolean value

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Gets or sets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers.

**Returns:**
int value

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Gets or sets the method used to validate a certificate.

**Returns:**
ValidationMethod element

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Gets or sets the mode of validation for digital signatures in a PDF document. The ValidationMode property determines the strictness of the validation process.

**Returns:**
ValidationMode element

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Gets or sets a value indicating whether the certificate chain should be checked during the validation process. When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be {@link ValidationStatus#Undefined}, which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in {@code false}. The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Gets or sets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Gets or sets the method used to validate a certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ValidationMethod element |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Gets or sets the mode of validation for digital signatures in a PDF document. The ValidationMode property determines the strictness of the validation process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ValidationMode element |
