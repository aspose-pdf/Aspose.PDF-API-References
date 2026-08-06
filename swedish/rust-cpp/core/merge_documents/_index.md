---
title: "merge_documents"
second_title: "Aspose.PDF för Rust via C++"
description: "Skapar ett nytt PDF-dokument genom att slå samman de angivna PDF-dokumenten."
type: docs
url: /sv/rust-cpp/core/merge_documents/
---

_Skapar ett nytt PDF-dokument genom att slå samman de angivna PDF-dokumenten._

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
    // Skapa ett nytt PDF-dokument
    let pdf1 = Document::new()?;

    // Öppna ett PDF-dokument med namnet "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Skapa ett nytt PDF-dokument genom att slå samman de angivna PDF-dokumenten
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```