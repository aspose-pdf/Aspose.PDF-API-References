---
title: Form
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing form object.
type: docs
weight: 110
url: /python-net/aspose.pdf.forms/form/
---

## Form class

Class representing form object.

The Form type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_synchronized|Returns true if object is thread-safe.|
|sync_root|Returns synchronization object.|
|auto_recalculate|If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.|
|auto_restore_form|If set, absent form fields will be automatically created if they present in annotations.|
|default_resources|Gets default resources placed on this form.|
|default_appearance|Gets or sets default appearance of the form (object which describes default font, text size and color for fields on the form).|
|xfa|Gets XFA data of the form (if presents).|
|ignore_needs_rendering|If this property is true the value of NeedsRendering key will be ignored during conversion <br/>            XFA form to Standard form. It is false by default.|
|remove_permission|If this property is true the "Perms" dictionary will be removed from the pdf document after conversion <br/>            dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of <br/>            mandatory fields in Adobe Acrobat reader.<br/>            It is false by default.|
|emulate_requierd_groups|If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers<br/>            This property was introduced because absences of analogues for the exclGroup during conversion Xfa representation of forms <br/>            to standard.<br/>            It is false by default.|
|type|Gets type of the form. Possible values are: Standard, Static, Dynamic.|
|fields|Gets list of all fields in lowest level of hierarhical form.|
|signatures_exist|If set, the document contains at least one signature field.|
|signatures_append_only|If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, <br/>            as opposed to an incremental update.|
|sign_dependent_elements_rendering_mode_when_converted|Forms can contain signing information, i.e. can be signed or unsigned.<br/>              And form's view sometimes must depend on whether form is signed or not.<br/>              This property tells to form's converter (f.e. during conversion XFA form to Standard form)<br/>              whether result form must be rendered as signed or as unsigned.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets field of the form by field index.|
## Methods
| Name | Description |
| :- | :- |
|delete(field)|Delete field from the form.|
|delete(field_name)|Deletes field from the form by its name.|
|add(field, page_number)|Adds field on the form.|
|add(field)|Adds field on the form.|
|add(field, partial_name, page_number)|Adds new field to the form; If this field is already placed on other or this form, the copy of field is created.|
|has_field(field)|Check if the form already has specified field.|
|has_field(field_name)|Determines if the field with specified name already added to the Form.|
|copy_to(array, index)|Copies fields placed on the form into array.|
|flatten()|Removes all form fields and place their values directly on the page.|
|add_field_appearance(field, page_number, rect)|Adds additional appearance of the field to specified page of the document in the specified location.|
|get_fields_in_rect(rect)|Returns fields inside of specified rectangle.|

### See Also

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

