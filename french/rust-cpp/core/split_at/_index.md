---
title: "split_at"
second_title: "Aspose.PDF pour Rust via C++"
description: "Divise le PDF-document actuel en deux nouveaux PDF-documents."
type: docs
url: /fr/rust-cpp/core/split_at/
---

_Divise le PDF-document actuel en deux nouveaux PDF-documents._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Ouvrir un PDF-document nommé "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Diviser le PDF-document actuel en deux nouveaux PDF-documents
    let (left, right) = pdf_split.split_at(2)?;

    // Enregistrer chaque partie découpée en tant que PDF-document séparé
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```