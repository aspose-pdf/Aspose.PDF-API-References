---
title: "merge_documents"
second_title: "Aspose.PDF für Rust über C++"
description: "Erstellt ein neues PDF-document durch Zusammenführen der bereitgestellten PDF-documents."
type: docs
url: /de/rust-cpp/core/merge_documents/
---

_Erstellt ein neues PDF-document durch Zusammenführen der bereitgestellten PDF-documents._

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
    // Erstelle ein neues PDF-Dokument
    let pdf1 = Document::new()?;

    // Öffne ein PDF-document mit dem Namen "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Erstelle ein neues PDF-document durch Zusammenführen der bereitgestellten PDF-documents
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```