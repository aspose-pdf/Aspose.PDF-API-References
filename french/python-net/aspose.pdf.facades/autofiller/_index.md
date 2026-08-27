---
title: "AutoFiller"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de recevoir des données d'une base de données ou d'une autre source de données, de les placer dans les champs conçus du modèle pdf et enfin de générer un nouveau fichier pdf ou un flux.<br/>             Elle possède deux modes d'entrée du fichier modèle : entrée sous forme de flux ou fichier pdf.<br/>             Elle possède quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers.<br/>             Elle peut recevoir des données littérales contenues dans un System.Data.DataTable."
type: docs
weight: 20
url: /fr/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Représente une classe permettant de recevoir des données d'une base de données ou d'une autre source de données, de les placer dans les champs conçus du modèle pdf et enfin de générer un nouveau fichier pdf ou un flux.<br/>             Elle possède deux modes d'entrée du fichier modèle : entrée sous forme de flux ou fichier pdf.<br/>             Elle possède quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers.<br/>             Elle peut recevoir des données littérales contenues dans un System.Data.DataTable.

Le type AutoFiller expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| AutoFiller() | Initialise une nouvelle instance de la classe AutoFiller |
## Propriétés
| Nom | Description |
| :- | :- |
| output_stream | Obtient ou définit le OutputStream. L'un des quatre modes de sortie. Son cas d'utilisation classique est Response.OutputStream.<br/>            Veuillez vous référer à la démo en ligne. |
| output_streams | Obtient ou définit les nombreux Output Streams. L'un des quatre modes de sortie. |
| input_stream | Obtient ou définit le flux du modèle d'entrée. L'un des deux modes d'entrée. |
| input_file_name | Obtient ou définit le fichier modèle d'entrée. L'un des deux modes d'entrée. |
| output_file_name | Obtient ou définit le fichier de sortie unique fusionné. L'un des quatre modes de sortie. |
| generating_path | Obtient ou définit le Generating Path des petits fichiers pdf lorsqu'un grand nombre de petits pdf doit être généré. Cela fonctionne avec une autre propriété [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            L'un des quatre modes de sortie. |
| basic_file_name | Obtient ou définit le nom de fichier de base si de nombreux petits fichiers doivent être générés. Le fichier généré sera comme "BasicFileName0","BasicFileName1",...<br/>            Cela fonctionne avec une autre propriété [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Méthodes
| Nom | Description |
| :- | :- |
| save() | Enregistre tous les pdf. |
| save(dest_file) | Enregistre tous les pdf. |
| save(dest_stream) | Enregistre tous les pdf. |
| bind_pdf(src_file) | Lie un fichier Pdf. |
| bind_pdf(src_stream) | Lie un fichier Pdf. |
| bind_pdf(src_doc) | Lie un document Pdf. |
| close() | Ferme l'objet et les flux de sortie. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

