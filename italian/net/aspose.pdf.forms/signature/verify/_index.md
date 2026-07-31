---
title: "Signature.Verify"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Signature. Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false"
type: docs
weight: 170
url: /it/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false.

```csharp
public bool Verify()
```

### Valore di ritorno

true se il documento è valido.

### Vedi anche

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ValidationOptions | Le opzioni di verifica. |
| validationResult | ValidationResult& | Il risultato della convalida del certificato. |

### Valore di ritorno

true se il documento è valido.

### Vedi anche

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. La verifica viene eseguita utilizzando il certificato della chiave pubblica esterna.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | Il certificato della chiave pubblica per la verifica. |
| options | ValidationOptions | Le opzioni di verifica. |
| validationResult | ValidationResult& | Il risultato della convalida del certificato. |

### Valore di ritorno

true se il documento è valido.

### Vedi anche

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


