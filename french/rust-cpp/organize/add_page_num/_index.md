---
title: "add_page_num"
second_title: "Aspose.PDF pour Rust via C++"
description: "Ajoute le numéro de page à un PDF-document."
type: docs
url: /fr/rust-cpp/organize/add_page_num/
---

_Ajoute le numéro de page à un PDF-document._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Ajouter le numéro de page à un document PDF
    pdf.add_page_num()?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```