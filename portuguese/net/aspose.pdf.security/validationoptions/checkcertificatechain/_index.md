---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Propriedade ValidationOptions. Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação"
type: docs
weight: 20
url: /pt/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Obtém ou define um valor que indica se a cadeia de certificados deve ser verificada durante o processo de validação.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Observações

Quando a propriedade é definida, a existência de uma cadeia de certificados será verificada; se estiver ausente, o resultado da verificação será Undefined, o que corresponde ao comportamento do Adobe Acrobat. Se você apenas deseja verificar o status de revogação online, defina o campo como `false`. O valor padrão é `false`.

### Veja Também

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


