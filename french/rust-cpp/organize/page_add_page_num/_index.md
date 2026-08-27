---
title: "page_add_page_num"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute le numéro de page sur la page."
type: docs
url: /fr/rust-cpp/organize/page_add_page_num/
---

_Ajoute le numéro de page sur la page._

```rust
pub fn page_add_page_num(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter le numéro de page sur la page
    pdf.page_add_page_num(1)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_add_page_num.pdf")?;

    Ok(())
}

```