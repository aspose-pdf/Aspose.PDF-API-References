---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF för Rust via C++"
description: "Ta bort PDF/A-efterlevnad från ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/remove_pdfa_compliance/
---

_Ta bort PDF/A-efterlevnad från ett PDF-dokument._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ta bort PDF/A-efterlevnad från ett PDF-dokument
    pdf.remove_pdfa_compliance()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```