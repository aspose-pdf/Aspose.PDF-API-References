---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen für die Validierung einer digitalen Signatur in einem PDF‑Dokument dar."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Stellt Optionen für die Validierung einer digitalen Signatur in einem PDF‑Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Erstellt eine Instanz der {@link ValidationOptions} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Legt fest oder gibt einen Wert zurück, der angibt, ob die Zertifikatskette während des Validierungsprozesses überprüft werden soll. Wenn die Eigenschaft gesetzt ist, wird das Vorhandensein einer Zertifikatskette geprüft; ist sie nicht vorhanden, ist das Ergebnis der Überprüfung {@link ValidationStatus#Undefined}, was dem Verhalten von Adobe Acrobat entspricht. Wenn Sie lediglich den Widerrufsstatus online prüfen möchten, setzen Sie das Feld auf {@code false}. Der Standardwert ist {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Legt die Timeout-Dauer in Millisekunden für netzwerkbezogene Vorgänge während des Validierungsprozesses fest oder gibt sie zurück. Die Eigenschaft RequestTimeout definiert die maximale Zeit, die das System auf eine Netzwerkantwort warten soll, wenn es auf Online-Ressourcen wie den Widerrufsstatus oder OCSP-Server zugreift. |
| [getValidationMethod](#getValidationMethod--) | Liest oder setzt die Methode, die zur Validierung eines Zertifikats verwendet wird. |
| [getValidationMode](#getValidationMode--) | Liest oder setzt den Validierungsmodus für digitale Signaturen in einem PDF-Dokument. Die Eigenschaft ValidationMode bestimmt die Strenge des Validierungsprozesses. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Legt fest oder gibt einen Wert zurück, der angibt, ob die Zertifikatskette während des Validierungsprozesses überprüft werden soll. Wenn die Eigenschaft gesetzt ist, wird das Vorhandensein einer Zertifikatskette geprüft; ist sie nicht vorhanden, ist das Ergebnis der Überprüfung {@link ValidationStatus#Undefined}, was dem Verhalten von Adobe Acrobat entspricht. Wenn Sie lediglich den Widerrufsstatus online prüfen möchten, setzen Sie das Feld auf {@code false}. Der Standardwert ist {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Legt die Timeout-Dauer in Millisekunden für netzwerkbezogene Vorgänge während des Validierungsprozesses fest oder gibt sie zurück. Die Eigenschaft RequestTimeout definiert die maximale Zeit, die das System auf eine Netzwerkantwort warten soll, wenn es auf Online-Ressourcen wie den Widerrufsstatus oder OCSP-Server zugreift. |
| [setValidationMethod](#setValidationMethod-int-) | Liest oder setzt die Methode, die zur Validierung eines Zertifikats verwendet wird. |
| [setValidationMode](#setValidationMode-int-) | Liest oder setzt den Validierungsmodus für digitale Signaturen in einem PDF-Dokument. Die Eigenschaft ValidationMode bestimmt die Strenge des Validierungsprozesses. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Erstellt eine Instanz der {@link ValidationOptions} Klasse.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Legt fest oder gibt einen Wert zurück, der angibt, ob die Zertifikatskette während des Validierungsprozesses überprüft werden soll. Wenn die Eigenschaft gesetzt ist, wird das Vorhandensein einer Zertifikatskette geprüft; ist sie nicht vorhanden, ist das Ergebnis der Überprüfung {@link ValidationStatus#Undefined}, was dem Verhalten von Adobe Acrobat entspricht. Wenn Sie lediglich den Widerrufsstatus online prüfen möchten, setzen Sie das Feld auf {@code false}. Der Standardwert ist {@code false}.

**Returns:**
boolescher Wert

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Legt die Timeout-Dauer in Millisekunden für netzwerkbezogene Vorgänge während des Validierungsprozesses fest oder gibt sie zurück. Die Eigenschaft RequestTimeout definiert die maximale Zeit, die das System auf eine Netzwerkantwort warten soll, wenn es auf Online-Ressourcen wie den Widerrufsstatus oder OCSP-Server zugreift.

**Returns:**
int-Wert

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Liest oder setzt die Methode, die zur Validierung eines Zertifikats verwendet wird.

**Returns:**
ValidationMethod-Element

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Liest oder setzt den Validierungsmodus für digitale Signaturen in einem PDF-Dokument. Die Eigenschaft ValidationMode bestimmt die Strenge des Validierungsprozesses.

**Returns:**
ValidationMode-Element

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Legt fest oder gibt einen Wert zurück, der angibt, ob die Zertifikatskette während des Validierungsprozesses überprüft werden soll. Wenn die Eigenschaft gesetzt ist, wird das Vorhandensein einer Zertifikatskette geprüft; ist sie nicht vorhanden, ist das Ergebnis der Überprüfung {@link ValidationStatus#Undefined}, was dem Verhalten von Adobe Acrobat entspricht. Wenn Sie lediglich den Widerrufsstatus online prüfen möchten, setzen Sie das Feld auf {@code false}. Der Standardwert ist {@code false}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Legt die Timeout-Dauer in Millisekunden für netzwerkbezogene Vorgänge während des Validierungsprozesses fest oder gibt sie zurück. Die Eigenschaft RequestTimeout definiert die maximale Zeit, die das System auf eine Netzwerkantwort warten soll, wenn es auf Online-Ressourcen wie den Widerrufsstatus oder OCSP-Server zugreift.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Liest oder setzt die Methode, die zur Validierung eines Zertifikats verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ValidationMethod-Element |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Liest oder setzt den Validierungsmodus für digitale Signaturen in einem PDF-Dokument. Die Eigenschaft ValidationMode bestimmt die Strenge des Validierungsprozesses.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ValidationMode-Element |
