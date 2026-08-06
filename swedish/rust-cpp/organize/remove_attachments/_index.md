---
title: "remove_attachments"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort bilagor från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_attachments/
---

_Tar bort bilagor från PDF-dokumentet._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // Ta bort bilagor från PDF-dokument
    pdf.remove_attachments()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```