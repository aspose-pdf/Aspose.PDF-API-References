---
title: "remove_annotations"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort kommentarer från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_annotations/
---

_Tar bort kommentarer från PDF-dokumentet._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // Ta bort annotationer från PDF-dokument
    pdf.remove_annotations()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```