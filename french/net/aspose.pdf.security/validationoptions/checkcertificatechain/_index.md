---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété ValidationOptions. Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation"
type: docs
weight: 20
url: /fr/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Remarques

Lorsque la propriété est définie, l'existence d'une chaîne de certificats sera vérifiée ; si elle est absente, le résultat de la vérification sera Undefined, ce qui correspond au comportement d'Adobe Acrobat. Si vous souhaitez simplement vérifier le statut de révocation en ligne, définissez le champ sur `false`. La valeur par défaut est `false`.

### Voir aussi

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


