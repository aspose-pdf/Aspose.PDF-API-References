---
title: "merge_documents"
second_title: "Aspose.PDF pour Rust via C++"
description: "Crée un nouveau document PDF en fusionnant les documents PDF fournis."
type: docs
url: /fr/rust-cpp/core/merge_documents/
---

_Crée un nouveau document PDF en fusionnant les documents PDF fournis._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Créer un nouveau PDF-document
    let pdf1 = Document::new()?;

    // Ouvrir un PDF-document nommé "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Créer un nouveau document PDF en fusionnant les documents PDF fournis
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Enregistrer le PDF-document précédemment ouvert avec un nouveau nom de fichier
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```