---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le style de jointure de ligne doit spécifier la forme à utiliser aux coins des tracés qui sont dessinés."
type: docs
weight: 370
url: /fr/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

Le style de jointure de ligne doit spécifier la forme à utiliser aux coins des tracés qui sont dessinés.

## Champs

| Champ | Description |
| --- | --- |
| [BevelJoin](#BevelJoin) | Jointure en biseau. Les deux segments doivent être terminés par des caps plats (voir 8.4.3.3, "Line Cap Style") et l'encoche résultante au-delà des extrémités des segments doit être remplie avec un triangle. |
| [MiterJoin](#MiterJoin) | Jointure en onglet. Les bords extérieurs des traits des deux segments doivent être prolongés jusqu'à ce qu'ils se rencontrent à un angle, comme dans un cadre photo. Si les segments se rencontrent à un angle trop aigu, tel que défini par le paramètre de limite d'onglet (voir 8.4.3.5, "Miter Limit"), une jointure en biseau doit être utilisée à la place. |
| [RoundJoin](#RoundJoin) | Jointure arrondie. Un arc de cercle d'un diamètre égal à la largeur de ligne doit être tracé autour du point où les deux segments se rencontrent, reliant les bords extérieurs des traits des deux segments. Cette forme en secteur de tarte doit être remplie, produisant un coin arrondi. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Jointure en biseau. Les deux segments doivent être terminés par des caps plats (voir 8.4.3.3, "Line Cap Style") et l'encoche résultante au-delà des extrémités des segments doit être remplie avec un triangle.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Jointure en onglet. Les bords extérieurs des traits des deux segments doivent être prolongés jusqu'à ce qu'ils se rencontrent à un angle, comme dans un cadre photo. Si les segments se rencontrent à un angle trop aigu, tel que défini par le paramètre de limite d'onglet (voir 8.4.3.5, "Miter Limit"), une jointure en biseau doit être utilisée à la place.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Jointure arrondie. Un arc de cercle d'un diamètre égal à la largeur de ligne doit être tracé autour du point où les deux segments se rencontrent, reliant les bords extérieurs des traits des deux segments. Cette forme en secteur de tarte doit être remplie, produisant un coin arrondi.
