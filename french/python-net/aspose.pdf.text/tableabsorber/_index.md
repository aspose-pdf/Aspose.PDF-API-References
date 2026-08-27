---
title: "TableAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un objet absorbeur des éléments de tableau.<br/>            Effectue la recherche et fournit l'accès aux résultats de recherche via la collection [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/)."
type: docs
weight: 310
url: /fr/python-net/aspose.pdf.text/tableabsorber/
---

## TableAbsorber class

Représente un objet absorbeur des éléments de tableau.<br/>            Effectue la recherche et fournit l'accès aux résultats de recherche via la collection [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/).

Le type TableAbsorber expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| TableAbsorber(text_search_options) | Initialise une nouvelle instance de la classe TableAbsorber |
| TableAbsorber() | Initialise une nouvelle instance de [TableAbsorber](/pdf/python-net/aspose.pdf.text/tableabsorber/). |
## Propriétés
| Nom | Description |
| :- | :- |
| text_search_options | Obtient ou définit les options de recherche de texte. |
| table_list | Renvoie une IList en lecture seule contenant les tables qui ont été trouvées |
| use_flow_engine | * Activer une version alfa précoce du moteur de reconnaissance de tables alternatif qui pourrait être utilisé pour les tables de conversion <br/>            sans bordures.<br/>            Ne prend pas encore en charge la modification des tables et l'obtention des styles de texte. La valeur par défaut est false; |
## Méthodes
| Nom | Description |
| :- | :- |
| visit(page) | Extrait les tables sur la page spécifiée |
| remove(table) | Supprime une [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) de la page. |
| replace(page, old_table, new_table) | Remplace une [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) par [Table](/pdf/python-net/aspose.pdf/table/) sur la page. |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

