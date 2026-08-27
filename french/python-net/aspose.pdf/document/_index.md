---
title: "Document"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant le document PDF"
type: docs
weight: 230
url: /fr/python-net/aspose.pdf/document/
---

## Document class

Classe représentant le document PDF

Le type Document expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Document(input) | Initialise une nouvelle instance de la classe Document |
| Document(input, password, is_managed_stream) | Initialise une nouvelle instance de la classe Document |
| Document(input, is_managed_stream) | Initialise une nouvelle instance de la classe Document |
| Document(filename) | Initialise une nouvelle instance de la classe Document |
| Document(input, password) | Initialise une nouvelle instance de la classe Document |
| Document() | Initialise un document vide. |
| Document(filename, options) | Initialise une nouvelle instance de la classe Document |
| Document(input, options) | Initialise une nouvelle instance de la classe Document |
| Document(filename, password) | Initialise une nouvelle instance de la classe Document |
| Document(filename, password, is_managed_stream) | Initialise une nouvelle instance de la classe Document |
## Propriétés
| Nom | Description |
| :- | :- |
| java_script | Collection de JavaScript au niveau du document. |
| is_licensed | Obtient l'état de licence du système. Retourne true si le système fonctionne en mode licencié et false sinon. |
| page_info | Obtient ou définit les informations de page (pour le générateur uniquement, non rempli lors de la lecture du document) |
| enable_signature_sanitization | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. Activé par défaut. |
| is_pdfa_compliant | Obtient si le document est conforme PDF/A. |
| is_pdf_ua_compliant | Obtient si le document est conforme PDF/UA. |
| is_xref_gaps_allowed | Obtient ou définit si le document est conforme PDF/A. |
| named_destinations | Collection de destinations nommées dans le document. |
| destinations | Obtient la collection de destinations.<br/>            Obsolète. Veuillez utiliser NamedDestinations. |
| pdf_format | Obtient le format PDF |
| embed_standard_fonts | Propriété qui indique que le document doit incorporer toutes les polices Type1 standard <br/>            qui ont le drapeau IsEmbedded défini sur true. Toutes les polices PDF peuvent être incorporées <br/>            dans le document simplement en définissant le drapeau IsEmbedded sur true, mais les polices Type1 standard PDF sont une exception à cette règle.<br/>            L'incorporation des polices Type1 standard nécessite beaucoup de temps, il est donc nécessaire<br/>            non seulement de définir le drapeau IsEmbedded sur true pour la police spécifiée, mais aussi de définir <br/>            un drapeau supplémentaire au niveau du document - EmbedStandardFonts = true;<br/>            Cette propriété ne peut être définie qu'une seule fois pour toutes les polices.<br/>            Par défaut false. |
| disable_font_license_verifications | De nombreuses opérations avec une police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. <br/>            Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation de cette police. <br/>            Ce drapeau est utilisé pour désactiver toutes les restrictions de licence pour toutes les polices dans le document PDF actuel.<br/>            Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui l'active <br/>            assume toute responsabilité des éventuelles violations de licence ou de loi. <br/>            Ainsi, il le fait à ses propres risques. <br/>            Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre <br/>            la loi sur le droit d'auteur. <br/>            Par défaut false. |
| font_utilities | IDocumentFontUtilities instance |
| collection | Obtient la collection du document. |
| version | Obtient une version du PDF à partir de l'en-tête du fichier PDF. |
| open_action | Obtient ou définit l'action effectuée à l'ouverture du document. |
| hide_tool_bar | Obtient ou définit le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif. |
| hide_menubar | Obtient ou définit le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif. |
| hide_window_ui | Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| fit_window | Obtient ou définit le drapeau indiquant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| center_window | Obtient ou définit le drapeau indiquant si la position de la fenêtre du document sera centrée à l'écran. |
| display_doc_title | Obtient ou définit le drapeau indiquant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| pages | Obtient ou définit la collection de pages du document.<br/>            Notez que les pages sont numérotées à partir de 1 dans la collection. |
| outlines | Obtient les repères du document. |
| actions | Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/définir les actions BeforClosing, BeforSaving, etc. |
| form | Obtient le formulaire Acro du document. |
| embedded_files | Obtient la collection de fichiers incorporés au document. |
| direction | Obtient ou définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| page_mode | Obtient ou définit le mode de page, indiquant comment le document doit être affiché à l'ouverture. |
| non_full_screen_page_mode | Obtient ou définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
| page_layout | Obtient ou définit la mise en page qui sera utilisée lorsque le document est ouvert. |
| duplex | Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| file_name | Nom du fichier PDF à l'origine de ce document |
| info | Obtient les informations du document. |
| metadata | Métadonnées du document.<br/>            (Un document PDF peut inclure des informations générales,<br/>             telles que le titre du document, l'auteur, ainsi que les dates de création et de modification.<br/>             Ces informations globales sur le document (par opposition à son contenu ou à sa structure) sont appelées métadonnées<br/>             et sont destinées à aider à la catalogisation et à la recherche de documents dans des bases de données externes.) |
| logical_structure | Obtient la structure logique du document. |
| handle_signature_change | Lancer une exception si le document est enregistré avec des modifications et possède une signature |
| crypto_algorithm | Obtient les paramètres de sécurité si le document est chiffré. <br/>            Si le document n'est pas chiffré, alors une exception correspondante sera levée dans .net 1.1<br/>            ou CryptoAlgorithm sera nul pour les autres versions de .net. |
| is_linearized | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| permissions | Obtient les autorisations du document. |
| is_encrypted | Obtient le statut de chiffrement du document. Vrai si le document est chiffré. |
| id | Obtient l'ID. |
| background | Obtient ou définit la couleur d'arrière-plan du document. |
| optimize_size | Obtient ou définit le drapeau d'optimisation. Lorsque des pages sont ajoutées au document, les flux de ressources égaux dans le fichier résultant sont<br/>            fusionnés en un seul objet PDF si ce drapeau est activé. <br/>            Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes.<br/>            Valeur par défaut : false. |
| allow_reuse_page_content | Permet de fusionner le contenu des pages pour optimiser la taille du document. Si utilisé, alors des pages différentes mais dupliquées peuvent référencer le même objet de contenu. Veuillez noter que ce mode peut entraîner des effets secondaires comme la modification du contenu d'une page lorsque une autre page est modifiée. |
| ignore_corrupted_objects | Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source. <br/>            Lorsque les pages du document source sont copiées dans le document de destination, le processus de copie s'arrête avec une exception <br/>            si certains objets dans les fichiers source sont corrompus lorsque ce drapeau est faux. <br/>            exemple : dest.Pages.Add(src.Pages);<br/>            Si ce drapeau est défini sur true, les objets corrompus seront remplacés par des valeurs vides.<br/>            Par défaut : true. |
| page_labels | Obtient les libellés de page dans le document. |
| enable_object_unload | Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire. <br/>            Cela permet de réduire l'utilisation de la mémoire mais peut avoir un effet négatif sur les performances. |
| tagged_content | Obtient l'accès au contenu TaggedPdf. |
## Méthodes
| Nom | Description |
| :- | :- |
| save(output) | Enregistre le document dans un flux. |
| save(output_file_name) | Enregistre le document dans le fichier spécifié. |
| save() | Enregistre le document dans un flux. |
| save(options) | Enregistre le document avec les options d'enregistrement. |
| save(output_file_name, format) | Enregistre le document sous un nouveau nom ainsi que le format de fichier. |
| save(output_stream, format) | Enregistre le document sous un nouveau nom ainsi que le format de fichier. |
| save(output_file_name, options) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| save(output_stream, options) | Enregistre le document dans un flux avec des options d'enregistrement. |
| export_annotations_to_xfdf(file_name) | Exporte toutes les annotations du document vers un fichier XFDF |
| export_annotations_to_xfdf(stream) | Exporter toutes les annotations du document dans le flux. |
| send_to(device, output) | Envoie l'intégralité du document au dispositif de document pour le traitement. |
| send_to(device, from_page, to_page, output) | Envoie les pages spécifiques du document au dispositif de document pour le traitement. |
| send_to(device, output_file_name) | Envoie l'intégralité du document au dispositif de document pour le traitement. |
| send_to(device, from_page, to_page, output_file_name) | Envoie l'intégralité du document au dispositif de document pour le traitement. |
| import_annotations_from_xfdf(file_name) | Importe les annotations du fichier XFDF vers le document. |
| import_annotations_from_xfdf(stream) | Importe les annotations du flux vers le document. |
| validate(output_log_file_name, format) | Valide le document dans le fichier spécifié. |
| validate(output_log_stream, format) | Valide le document dans le fichier spécifié. |
| validate(options) | Valide le document dans le fichier spécifié. |
| convert(output_log_file_name, format, action, transparency_action) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| convert(output_log_stream, format, action, transparency_action) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| convert(output_log_file_name, format, action) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| convert(options) | Convertit le document en utilisant les options de conversion spécifiées |
| convert(output_log_stream, format, action) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| convert(fixup, output_log, only_validation, parameters) | Convertit le document en appliquant le Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Convertit le document en appliquant le Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Convertit le fichier source au format source en fichier de destination au format de destination. |
| convert(src_stream, load_options, dst_file_name, save_options) | Convertit le flux au format source en fichier de destination au format de destination. |
| convert(src_file_name, load_options, dst_stream, save_options) | Convertit le flux au format source en fichier de destination au format de destination. |
| convert(src_stream, load_options, dst_stream, save_options) | Convertit le flux au format source en fichier de destination au format de destination. |
| flatten() | Supprime tous les champs du document et place leurs valeurs à la place. |
| flatten(flatten_settings) | Supprime tous les champs du document et place leurs valeurs à la place. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Crypte le document. Appelez ensuite Save pour obtenir la version chiffrée du document. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Crypte le document. Appelez ensuite Save pour obtenir la version chiffrée du document. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Crypte le document. Appelez ensuite Save pour obtenir la version chiffrée du document. |
| optimize_resources() | Optimise les ressources du document :<br/>            1. Les ressources qui ne sont pas utilisées sur les pages du document sont supprimées;<br/>            2. Les ressources égales sont regroupées en un seul objet; <br/>            3. Les objets inutilisés sont supprimés. |
| optimize_resources(strategy) | Optimise les ressources du document selon la stratégie d'optimisation définie. |
| bind_xml(file) | Lie le xml au document |
| bind_xml(xml_file, xsl_file) | Lie le xml au document |
| bind_xml(xml_stream, xsl_stream) | Lie le xml/xsl au document |
| bind_xml(stream) | Lie le xml/xsl au document |
| remove_pdfa_compliance() | Supprime la conformité pdfa du document |
| remove_pdf_ua_compliance() | Supprime la conformité pdfUa du document |
| set_title(title) | Définir le titre du document PDF |
| process_paragraphs() | Traiter les paragraphes pour le générateur. |
| remove_metadata() | Supprime les métadonnées du document. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Modifie les mots de passe du document. Cette action ne peut être effectuée qu'avec le mot de passe du propriétaire. |
| decrypt() | Déchiffre le document. Appelez ensuite Save pour obtenir la version déchiffrée du document. |
| optimize() | Linéariser le document afin de<br/>            - ouvrir la première page le plus rapidement possible ;<br/>            - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ;<br/>            - afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont transmises sur un canal lent (afficher d'abord les données les plus utiles) ;<br/>            - permettre l'interaction de l'utilisateur, comme suivre un lien, d'être effectuée même avant que la page entière ne soit reçue et affichée.<br/>            L'appel de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document n'est préparé qu'à avoir une structure optimisée,<br/>            appelez ensuite Save pour obtenir le document optimisé. |
| get_catalog_value(key) | Renvoie la valeur de l'élément du dictionnaire du catalogue. |
| free_memory() | Libère la mémoire |
| save_xml(file) | Enregistre le document au format XML. |
| get_object_by_id(id) | Obtient un objet avec l'ID spécifié dans le document. |
| repair() | Répare le document endommagé. |
| get_xmp_metadata(stream) | Obtient les métadonnées XMP du document. |
| set_xmp_metadata(stream) | Définit les métadonnées XMP du document. |
| check(do_repair) | Valide le document. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organise les nœuds d'arbre de page d'un document en un arbre équilibré.<br/>            Seulement si le document possède plus de nodesNumInSubtrees objets de page, sinon il ne fait rien. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

