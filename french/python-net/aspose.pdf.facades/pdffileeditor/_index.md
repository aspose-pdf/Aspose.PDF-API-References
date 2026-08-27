---
title: "PdfFileEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Implémente des opérations de concaténation de fichiers PDF, de division, d'extraction de pages, de création de livret, etc."
type: docs
weight: 220
url: /fr/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc.

Le type PdfFileEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileEditor() | Initialise une nouvelle instance de la classe PdfFileEditor |
## Propriétés
| Nom | Description |
| :- | :- |
| conversion_log | Obtient le journal du processus de conversion. |
| merge_duplicate_layers | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est vraie. <br/>            Sinon, les couches portant le même nom seront enregistrées comme des couches distinctes dans le document résultant. |
| copy_outlines | Si vrai, les contours seront copiés. |
| copy_logical_structure | Si vrai, la structure logique du fichier est copiée lors de la concaténation. |
| merge_duplicate_outlines | Si vrai, les contours dupliqués sont fusionnés. |
| preserve_user_rights | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. Les droits d'utilisateur de tous les autres documents sont ignorés. |
| incremental_updates | Si vrai, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| optimize_size | Obtient ou définit le drapeau d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est activé.<br/>            Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes.<br/>            Valeur par défaut : false. |
| corrupted_items | Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à Concatenate() <br/>            une nouvelle entrée CorruptedItem est créée.<br/>            Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu.<br/>            Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| owner_password | Définit le mot de passe du propriétaire si le fichier PDF source d'entrée est chiffré.<br/>            Cette propriété n'est pas encore implémentée. |
| allow_concatenate_exceptions | Si défini sur true, des exceptions sont levées en cas d'erreur. Sinon, les exceptions ne sont pas levées et les méthodes renvoient false en cas d'échec. |
| close_concatenated_streams | Si défini sur true, les flux sont fermés après l'opération. |
| unique_suffix | Format du suffixe ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés.<br/>            Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres.<br/>            Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName" les noms seront :<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| keep_actions | Si true, les actions seront copiées depuis les documents source. Valeur par défaut : true. |
| keep_fields_unique | Si true, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés.<br/>            Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe peut être spécifié dans la propriété UniqueSuffix. |
| remove_signatures | Si true, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| use_disk_buffer | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |
| concatenation_packet_size | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
## Méthodes
| Nom | Description |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Concatène deux fichiers. |
| try_concatenate(src, dest) | Concatène des documents. |
| try_concatenate(input_files, output_file) | Concatène des fichiers en un seul fichier. |
| try_concatenate(input_stream, output_stream) | Concatène des fichiers |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatène deux fichiers. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatène des fichiers |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Ajoute des pages, qui sont choisies à partir d'un tableau de documents dans portStreams.<br/>            Le document résultant inclut firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Ajoute des pages, qui sont choisies à partir des documents portFiles. <br/>            Le document résultant inclut firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| try_delete(input_file, page_number, output_file) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, et les enregistre comme un nouveau fichier Pdf. |
| try_delete(input_stream, page_number, output_stream) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, et les enregistre comme un nouveau fichier Pdf. |
| try_extract(input_file, start_page, end_page, output_file) | Extrait des pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf. |
| try_extract(input_file, page_number, output_file) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier PDF. |
| try_extract(input_stream, page_number, output_stream) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier Pdf. |
| try_split_from_first(input_file, location, output_file) | Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier. |
| try_split_from_first(input_stream, location, output_stream) | Divise du début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie. |
| try_split_to_end(input_file, location, output_file) | Divise à partir de l'emplacement, et enregistre la partie arrière comme un nouveau fichier. |
| try_split_to_end(input_stream, location, output_stream) | Divise à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau flux de fichier Stream. |
| try_make_booklet(input_file, output_file) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| try_make_booklet(input_stream, output_stream) | Crée un livret à partir du InputStream vers le outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Crée un livret à partir du inputFile vers le outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Crée un livret personnalisé à partir du firstInputFile vers le outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Crée un livret personnalisé à partir du firstInputStream vers le outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crée un livret personnalisé à partir du firstInputFile vers le outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Crée un livret à partir du firstInputStream vers le outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Crée un document N-Up à partir du firstInputFile vers le outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Crée un document N-Up à partir du firstInputFile vers le outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| try_make_n_up(input_files, output_file, is_sidewise) | Crée un document N‑Up à partir des plusieurs fichiers PDF d’entrée vers outputFile. <br/>            Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison avec les pages <br/>            des fichiers d’entrée du même numéro de page. Les multiples pages sont empilées horizontalement <br/>            si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Crée un document N‑Up à partir des plusieurs flux PDF d’entrée vers outputStream.<br/>            Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison avec les pages <br/>            des flux d’entrée du même numéro de page. Les multiples pages sont empilées horizontalement <br/>            si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Crée un document N‑Up à partir du fichier d’entrée vers outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Redimensionne le contenu des pages du document. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Redimensionne le contenu des pages du document. <br/>            Réduit le contenu de la page et ajoute des marges.<br/>            La nouvelle taille du contenu est spécifiée en unités d’espace par défaut. |
| try_resize_contents(source, destination, pages, parameters) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges blanches sont ajoutées autour de la page. |
| concatenate(first_input_file, sec_input_file, output_file) | Concatène les fichiers et enregistre le résultat dans l’objet HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Concatène les fichiers et stocke le résultat dans l’objet HttpResponse. |
| concatenate(src, dest) | Concatène des documents. |
| concatenate(input_files, output_file) | Concatène les fichiers et enregistre le résultat dans l’objet HttpResposnse. |
| concatenate(input_stream, output_stream) | Concatène les fichiers et stocke le résultat dans l’objet HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatène les fichiers et enregistre le résultat dans l’objet HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatène les fichiers et stocke le résultat dans l’objet HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Ajoute des documents au document source et enregistre le résultat dans l’objet response. |
| append(input_file, port_files, start_page, end_page, output_file) | Ajoute des documents au document source et enregistre le résultat dans l’objet HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Ajoute des documents au document source et enregistre le résultat dans l’objet HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Ajoute des documents au document source et enregistre le résultat dans l’objet response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Insère le document dans un autre document et stocke le résultat dans l'objet de réponse. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Insère le document dans un autre document et stocke le résultat dans l'objet de réponse. |
| delete(input_file, page_number, output_file) | Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpResponse. |
| delete(input_stream, page_number, output_stream) | Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| extract(input_file, page_number, output_file) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Extrait les pages spécifiées du fichier source et stocke le résultat dans  l'objet HttpResponse. |
| extract(input_stream, page_number, output_stream) | Extrait les pages spécifiées du fichier source et stocke le résultat dans  l'objet HttpResponse. |
| split_from_first(input_file, location, output_file) | Divise le document de la première page jusqu'à l'emplacement et enregistre le résultat dans les objets HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Divise le document du début jusqu'à l'emplacement spécifié et stocke le résultat dans l'objet HttpResponse. |
| split_to_end(input_file, location, output_file) | Divise à partir de l'emplacement spécifié, et enregistre la partie arrière dans l'objet HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Divise à partir de l'emplacement spécifié, et enregistre la partie arrière dans l'objet HttpResponse. |
| make_booklet(input_file, output_file) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpResponse. |
| make_booklet(input_stream, output_stream) | Créer un livret à partir d'un fichier PDF et le stocke dans HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Créer un livret à partir d'un fichier PDF et le stocke dans HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Créer un livret à partir d'un fichier PDF et le stocke dans HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Créer un livret à partir d'un fichier PDF et le stocke dans HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Crée un document N‑Up à partir des plusieurs fichiers PDF d’entrée vers outputFile. <br/>            Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison avec les pages <br/>            des fichiers d’entrée du même numéro de page. Les multiples pages sont empilées horizontalement <br/>            si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| make_n_up(input_streams, output_stream, is_sidewise) | Crée un document N‑Up à partir des plusieurs flux PDF d’entrée vers outputStream.<br/>            Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison avec les pages <br/>            des flux d’entrée du même numéro de page. Les multiples pages sont empilées horizontalement <br/>            si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| make_n_up(input_file, output_file, x, y, page_size) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| split_to_pages(input_file, file_name_template) | Divise le fichier PDF en documents d'une seule page. |
| split_to_pages(input_stream, file_name_template) | Divise le fichier PDF en documents d'une seule page et l'enregistre dans le chemin spécifié. Le chemin est indiqué par le modèle de nom de champ. |
| resize_contents(source, destination, pages, parameters) | Redimensionne le contenu des pages du document. Si une page est réduite, des marges blanches sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensionne le contenu des pages du document. <br/>            Réduit le contenu de la page et ajoute des marges.<br/>            La nouvelle taille du contenu est spécifiée en unités d’espace par défaut. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensionne le contenu des pages du document. <br/>            Réduit le contenu de la page et ajoute des marges.<br/>            La nouvelle taille du contenu est spécifiée en unités d’espace par défaut. |
| resize_contents(source, destination, pages, parameters) | Redimensionne le contenu des pages du document. Si une page est réduite, des marges blanches sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| resize_contents(source, pages, parameters) | Redimensionne les pages du document. Des marges blanches sont ajoutées autour de la page réduite. |
| resize_contents(source, parameters) | Redimensionne les pages du document. Des marges blanches sont ajoutées autour de la page réduite. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensionne le contenu des pages du document.<br/>            Réduit le contenu de la page et ajoute des marges.<br/>            La nouvelle taille du contenu est spécifiée en pourcentage. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensionne le contenu des pages du document.<br/>            Réduit le contenu de la page et ajoute des marges.<br/>            La nouvelle taille du contenu est spécifiée en pourcentage. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensionne le contenu de la page et ajoute les marges spécifiées. <br/>            Les marges sont spécifiées en unités d'espace par défaut. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensionne le contenu de la page et ajoute les marges spécifiées. <br/>            Les marges sont spécifiées en unités d'espace par défaut. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensionne le contenu de la page et ajoute les marges spécifiées.<br/>            Les marges sont spécifiées en pourcentage de la taille initiale de la page. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensionne le contenu de la page et ajoute les marges spécifiées.<br/>            Les marges sont spécifiées en pourcentage de la taille initiale de la page. |
| add_page_break(src, dest, page_breaks) | Ajoute des sauts de page dans les pages du document. |
| add_page_break(src, dest, page_breaks) | Ajoute des sauts de page dans les pages du document. |
| add_page_break(src, dest, page_breaks) | Ajoute des sauts de page dans les pages du document. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

