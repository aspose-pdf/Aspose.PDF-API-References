---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà ValidationOptions. Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida"
type: docs
weight: 20
url: /it/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Ottiene o imposta un valore che indica se la catena di certificati deve essere verificata durante il processo di convalida.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Osservazioni

Quando la proprietà è impostata, verrà verificata l'esistenza di una catena di certificati; se è assente, il risultato della verifica sarà Undefined, che corrisponde al comportamento di Adobe Acrobat. Se desideri solo verificare lo stato di revoca online, imposta il campo su `false`. Il valore predefinito è `false`.

### Vedi anche

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


