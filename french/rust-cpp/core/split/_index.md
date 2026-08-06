---
title: "split"
second_title: "Aspose.PDF pour Rust via C++"
description: "Crée plusieurs nouveaux documents PDF en extrayant les pages du document PDF actuel."
type: docs
url: /fr/rust-cpp/core/split/
---

_Crée plusieurs nouveaux documents PDF en extrayant les pages du document PDF actuel._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document nommé "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Créer plusieurs nouveaux documents PDF en extrayant les pages du document PDF actuel
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Enregistrer chaque partie découpée en tant que PDF-document séparé
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```