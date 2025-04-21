---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Remplit les champs de la zone de texte avec des valeurs textuelles et enregistre le document. Pertinent pour les documents signés. Remarque  Ne s'applique qu'à la zone de texte. Les noms et valeurs des champs sont sensibles à la casse.
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/form/fillfields/
---
## Méthode Form.FillFields

Remplit les champs de la zone de texte avec des valeurs textuelles et enregistre le document. Pertinent pour les documents signés. Remarque : Ne s'applique qu'à la zone de texte. Les noms et valeurs des champs sont sensibles à la casse.

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

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)