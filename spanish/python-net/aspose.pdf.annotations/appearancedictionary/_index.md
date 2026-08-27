---
title: "AppearanceDictionary"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Diccionario de apariencia de anotación que especifica cómo se presentará visualmente la anotación en la página."
type: docs
weight: 60
url: /es/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Diccionario de apariencia de anotación que especifica cómo se presentará visualmente la anotación en la página.

El tipo AppearanceDictionary expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_fixed_size | Obtiene un valor que indica si el diccionario tiene un tamaño fijo. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | valores de D).state,<br/>            donde N - apariencia normal, R - apariencia al pasar el cursor, D - apariencia presionada y state - el nombre del estado<br/>            (p. ej., On, Off para casillas de verificación). |
| values | Obtiene la lista de los valores del diccionario. <br/>            La colección de resultados contiene la lista de objetos XForm. |
| is_synchronized | Obtiene un valor que indica si el acceso al diccionario está sincronizado (seguro para subprocesos). |
| sync_root | Obtiene un objeto que puede usarse para sincronizar el acceso al diccionario. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| add(key, value) | Agrega un elemento con la clave y el valor proporcionados. |
| add(key, value) | Agregar formulario X para la clave especificada. |
| copy_to(array, index) | Copia los elementos del diccionario a una Matriz, comenzando en un índice de Matriz específico. |
| contains_key(key) | Determina si este diccionario contiene la clave especificada. |
| remove(key) | Elimina la clave del diccionario. |
| try_get_value(key, value) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

