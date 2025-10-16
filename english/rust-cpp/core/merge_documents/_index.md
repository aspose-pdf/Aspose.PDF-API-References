---
title: "merge_documents"
second_title: Aspose.PDF for Rust via C++
description: "Creates a new PDF-document by merging the provided PDF-documents."
type: docs
url: /rust-cpp/core/merge_documents/
---

_Creates a new PDF-document by merging the provided PDF-documents._

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
    // Create a new PDF-document
    let pdf1 = Document::new()?;

    // Open a PDF-document named "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Create a new PDF-document by merging the provided PDF-documents
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Save the previously opened PDF-document with new filename
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```