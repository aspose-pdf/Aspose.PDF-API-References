---
title: "split_document"
second_title: "Aspose.PDF pour Rust via C++"
description: "Crée plusieurs nouveaux PDF-documents en extrayant des pages du PDF-document source."
type: docs
url: /fr/rust-cpp/core/split_document/
---

_Crée plusieurs nouveaux PDF-documents en extrayant des pages du PDF-document source._

```rust
pub fn split_document(document: &Document, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
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

    // Crée plusieurs nouveaux PDF-documents en extrayant des pages du PDF-document source
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // Enregistrer chaque partie découpée en tant que PDF-document séparé
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```