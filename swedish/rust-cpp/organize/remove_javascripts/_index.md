---
title: "remove_javascripts"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort Java-skript från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_javascripts/
---

_Tar bort Java-skript från PDF-dokumentet._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // Ta bort JavaScript från PDF-dokument
    pdf.remove_javascripts()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```