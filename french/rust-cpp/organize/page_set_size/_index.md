---
title: "page_set_size"
second_title: "Aspose.PDF pour Rust via C++"
description: "Définit la taille d'une page dans le document PDF."
type: docs
url: /fr/rust-cpp/organize/page_set_size/
---

_Définit la taille d'une page dans le document PDF._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document avec le nom de fichier
    let pdf = Document::open("sample.pdf")?;

    // Définir la taille d'une page dans le document PDF
    pdf.page_set_size(1, PageSize::A1)?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```