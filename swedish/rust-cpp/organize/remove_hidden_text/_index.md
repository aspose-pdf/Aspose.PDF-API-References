---
title: "remove_hidden_text"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort dold text från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_hidden_text/
---

_Tar bort dold text från PDF-dokumentet._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // Ta bort dold text från PDF-dokument
    pdf.remove_hidden_text()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```