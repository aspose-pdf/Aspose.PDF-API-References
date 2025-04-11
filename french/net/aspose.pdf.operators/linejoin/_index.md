---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Enum LineJoin d'Aspose.Pdf. Le style de jointure de ligne doit spécifier la forme à utiliser aux coins des chemins qui sont tracés
type: docs
weight: 7450
url: /fr/net/aspose.pdf.operators/linejoin/
---
## Énumération LineJoin

Le style de jointure de ligne doit spécifier la forme à utiliser aux coins des chemins qui sont tracés.

```csharp
public enum LineJoin
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| MiterJoin | `0` | Jointure en miter. Les bords extérieurs des traits pour les deux segments doivent être prolongés jusqu'à ce qu'ils se rencontrent à un angle, comme dans un cadre photo. Si les segments se rencontrent à un angle trop aigu tel que défini par le paramètre de limite de miter (voir 8.4.3.5, "Limite de Miter"), une jointure en biseau doit être utilisée à la place. |
| RoundJoin | `1` | Jointure arrondie. Un arc de cercle avec un diamètre égal à la largeur de la ligne doit être dessiné autour du point où les deux segments se rencontrent, reliant les bords extérieurs des traits pour les deux segments. Cette figure en forme de part de tarte doit être remplie, produisant un coin arrondi. |
| BevelJoin | `2` | Jointure en biseau. Les deux segments doivent être terminés par des capuchons à plat (voir 8.4.3.3, "Style de Capuchon de Ligne") et la entaille résultante au-delà des extrémités des segments doit être remplie par un triangle. |

### Voir aussi

* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)