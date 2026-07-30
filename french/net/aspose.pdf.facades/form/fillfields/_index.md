---
title: "Form.FillFields"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Form méthode. Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document. Pertinent pour les documents signés. Remarque : ne s'applique qu'aux zones de texte. Le nom et les valeurs des champs sont sensibles à la casse."
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document. Pertinent pour les documents signés. Remarque : applicable uniquement aux zones de texte. Les noms et les valeurs des champs sont sensibles à la casse.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldNames | String[] | Noms des champs. |
| fieldValues | String[] | Nouvelles valeurs des champs. |
| output | Stream& | Flux où le document sera enregistré. |

### Valeur de retour

true si les champs ont été trouvés et remplis avec succès.

## Exemples

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


