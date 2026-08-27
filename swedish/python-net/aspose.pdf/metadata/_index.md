---
title: "Metadata"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Tillhandahåller åtkomst till XMP-metadataström."
type: docs
weight: 930
url: /sv/python-net/aspose.pdf/metadata/
---

## Metadata class

Tillhandahåller åtkomst till XMP-metadataström.

Typen Metadata exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_fixed_size | Kontrollerar om samlingen har fast storlek. |
| nycklar | Hämtar samling av metadata-nycklar. |
| värden | Hämtar värden i metadata. |
| is_synchronized | Kontrollerar om samlingen är synkroniserad. |
| sync_root | Hämtar samlingens synkroniseringsobjekt. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | Registrerar namnrymdens URI. |
| register_namespace_uri(prefix, namespace_uri, schema_description) | Registrerar namnrymdens URI. |
| add(key, value) | Lägger till värde i metadata. |
| add(key, value) | Lägger till värde i metadata. |
| add(prefix, value) | Lägger till pdf‑extension i metadata. |
| get_namespace_uri_by_prefix(prefix) | Returnerar namnrymdens URI för prefix. |
| get_prefix_by_namespace_uri(namespace_uri) | Returnerar prefix för namnrymdens URI. |
| contains(key) | Kontrollerar om nyckeln finns i metadata. |
| remove(key) | Tar bort post från metadata. |
| contains_key(key) | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| try_get_value(key, value) | Försöker hitta nyckeln i ordboken och hämtar värdet om det hittas. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

