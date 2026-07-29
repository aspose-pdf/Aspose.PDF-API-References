---
title: "SetDash"
linktitle: "SetDash"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur d (définit le motif de tirets de ligne)."
type: docs
weight: 610
url: /fr/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Classe représentant l'opérateur d (définit le motif de tirets de ligne).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Crée l'opérateur de définition du motif de tirets. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getPattern](#getPattern--) | Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés. Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales. |
| [getPhase](#getPhase--) | Phase de tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru en boucle, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase de tirets, le tracé du chemin doit commencer, et le tableau de tirets doit être utilisé de manière cyclique à partir de ce point. |
| [setPattern](#setPattern-int:A-) | Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés. Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales. |
| [setPhase](#setPhase-int-) | Phase de tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru en boucle, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase de tirets, le tracé du chemin doit commencer, et le tableau de tirets doit être utilisé de manière cyclique à partir de ce point. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Obtient la représentation sous forme de chaîne de l'opérateur. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Crée l'opérateur de définition du motif de tirets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| motif |  | Tableau qui définit le motif de tirets. |
| phase |  | Phase de tirets. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés. Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales.

**Returns:**
tableau d'int

### getPhase {#getPhase--}
```
public int getPhase()
```

Phase de tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru en boucle, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase de tirets, le tracé du chemin doit commencer, et le tableau de tirets doit être utilisé de manière cyclique à partir de ce point.

**Returns:**
valeur int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés. Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau d'int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Phase de tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru en boucle, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase de tirets, le tracé du chemin doit commencer, et le tableau de tirets doit être utilisé de manière cyclique à partir de ce point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand

### toString {#toString--}
```
public String toString()
```

Obtient la représentation sous forme de chaîne de l'opérateur.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
