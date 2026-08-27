---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per la convalida di una firma digitale in un documento PDF."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Rappresenta le opzioni per la convalida di una firma digitale in un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Crea un'istanza della classe {@link ValidationOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida. Quando la proprietà è impostata, verrà controllata l'esistenza di una catena di certificati; se è assente, il risultato della verifica sarà {@link ValidationStatus#Undefined}, che corrisponde al comportamento di Adobe Acrobat. Se si desidera solo verificare lo stato di revoca online, impostare il campo su {@code false}. Il valore predefinito è {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Ottiene o imposta la durata del timeout, in millisecondi, per le operazioni di rete durante il processo di convalida. La proprietà RequestTimeout definisce il tempo massimo che il sistema deve attendere per una risposta di rete quando accede a risorse online, come lo stato di revoca o i server OCSP. |
| [getValidationMethod](#getValidationMethod--) | Ottiene o imposta il metodo utilizzato per convalidare un certificato. |
| [getValidationMode](#getValidationMode--) | Ottiene o imposta la modalità di convalida per le firme digitali in un documento PDF. La proprietà ValidationMode determina il rigore del processo di convalida. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida. Quando la proprietà è impostata, verrà controllata l'esistenza di una catena di certificati; se è assente, il risultato della verifica sarà {@link ValidationStatus#Undefined}, che corrisponde al comportamento di Adobe Acrobat. Se si desidera solo verificare lo stato di revoca online, impostare il campo su {@code false}. Il valore predefinito è {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Ottiene o imposta la durata del timeout, in millisecondi, per le operazioni di rete durante il processo di convalida. La proprietà RequestTimeout definisce il tempo massimo che il sistema deve attendere per una risposta di rete quando accede a risorse online, come lo stato di revoca o i server OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Ottiene o imposta il metodo utilizzato per convalidare un certificato. |
| [setValidationMode](#setValidationMode-int-) | Ottiene o imposta la modalità di convalida per le firme digitali in un documento PDF. La proprietà ValidationMode determina il rigore del processo di convalida. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Crea un'istanza della classe {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida. Quando la proprietà è impostata, verrà controllata l'esistenza di una catena di certificati; se è assente, il risultato della verifica sarà {@link ValidationStatus#Undefined}, che corrisponde al comportamento di Adobe Acrobat. Se si desidera solo verificare lo stato di revoca online, impostare il campo su {@code false}. Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Ottiene o imposta la durata del timeout, in millisecondi, per le operazioni di rete durante il processo di convalida. La proprietà RequestTimeout definisce il tempo massimo che il sistema deve attendere per una risposta di rete quando accede a risorse online, come lo stato di revoca o i server OCSP.

**Returns:**
valore int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Ottiene o imposta il metodo utilizzato per convalidare un certificato.

**Returns:**
Elemento ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Ottiene o imposta la modalità di convalida per le firme digitali in un documento PDF. La proprietà ValidationMode determina il rigore del processo di convalida.

**Returns:**
Elemento ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida. Quando la proprietà è impostata, verrà controllata l'esistenza di una catena di certificati; se è assente, il risultato della verifica sarà {@link ValidationStatus#Undefined}, che corrisponde al comportamento di Adobe Acrobat. Se si desidera solo verificare lo stato di revoca online, impostare il campo su {@code false}. Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Ottiene o imposta la durata del timeout, in millisecondi, per le operazioni di rete durante il processo di convalida. La proprietà RequestTimeout definisce il tempo massimo che il sistema deve attendere per una risposta di rete quando accede a risorse online, come lo stato di revoca o i server OCSP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Ottiene o imposta il metodo utilizzato per convalidare un certificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Ottiene o imposta la modalità di convalida per le firme digitali in un documento PDF. La proprietà ValidationMode determina il rigore del processo di convalida.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ValidationMode |
