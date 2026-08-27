---
title: "merge_documents"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Crea un nuovo PDF-document unendo i PDF-documents forniti."
type: docs
url: /it/rust-cpp/core/merge_documents/
---

_Crea un nuovo PDF-document unendo i PDF-documents forniti._

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
    // Crea un nuovo PDF-document
    let pdf1 = Document::new()?;

    // Apri un PDF-document chiamato "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Crea un nuovo PDF-document unendo i PDF-documents forniti
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```