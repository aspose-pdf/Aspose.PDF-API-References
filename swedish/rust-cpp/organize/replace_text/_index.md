---
title: "replace_text"
second_title: "Aspose.PDF för Rust via C++"
description: "Ersätter text."
type: docs
url: /sv/rust-cpp/organize/replace_text/
---

_Ersätter text._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ersätt text i PDF-dokument
    pdf.replace_text("PDF", "TXT")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```