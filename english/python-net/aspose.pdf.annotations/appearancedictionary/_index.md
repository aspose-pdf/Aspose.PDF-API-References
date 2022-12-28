---
title: AppearanceDictionary
second_title: Aspose.PDF for Python via .NET API Reference
description: Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.
type: docs
weight: 60
url: /python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.

The AppearanceDictionary type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_fixed_size|Gets a value indicating whether dictionary has a fixed size.|
|keys|Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N|R|D).state values,<br/>            where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state<br/>            (e.g. On, Off for checkboxes).|
|values|Gets the list of the dictionary values. <br/>            Result collection contains the list of XForm objects.|
|is_synchronized|Gets a value indicating whether access to the dictionary is synchronized (thread safe).|
|sync_root|Gets an object that can be used to synchronize access to the dictionary.|
## Methods
| Name | Description |
| :- | :- |
|add(key, value)|Adds an element with the provided key and value.|
|add(key, value)|Add X form for specifed key.|
|copy_to(array, index)|Copies the elements of the dictionary to an Array, starting at a particular Array index.|
|contains_key(key)|Determines does this dictionary contasins specified key.|
|remove(key)|Removes key from the dictionary.|
|try_get_value(key, value)|Tries to find key in the dictionary and retreives value if found.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

