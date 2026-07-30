---
title: "Énumération LineJoin"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Operators.LineJoin. Le style de jointure de ligne doit spécifier la forme à utiliser aux coins des tracés qui sont dessinés."
type: docs
weight: 7590
url: /fr/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

Le style d'angle de ligne doit spécifier la forme à utiliser aux coins des chemins qui sont tracés.

```csharp
public enum LineJoin
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| MiterJoin | `0` | Jointure en onglet. Les bords extérieurs des tracés des deux segments doivent être prolongés jusqu'à ce qu'ils se rencontrent à un angle, comme dans un cadre photo. Si les segments se rencontrent à un angle trop aigu, tel que défini par le paramètre de limite d'onglet (voir 8.4.3.5, "Miter Limit"), une jointure en biseau doit être utilisée à la place. |
| RoundJoin | `1` | Joint arrondi. Un arc de cercle dont le diamètre est égal à la largeur de ligne doit être dessiné autour du point où les deux segments se rencontrent, reliant les bords extérieurs des traits des deux segments. Cette forme en forme de part de tarte doit être remplie, produisant un coin arrondi. |
| BevelJoin | `2` | Joint biseauté. Les deux segments doivent être terminés par des embouts plats (voir 8.4.3.3, « Line Cap Style ») et la encoche résultante au-delà des extrémités des segments doit être remplie avec un triangle. |

### Voir aussi

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


