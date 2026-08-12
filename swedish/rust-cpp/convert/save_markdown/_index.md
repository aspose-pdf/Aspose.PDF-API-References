---
title: "save_markdown"
second_title: "Aspose.PDF för Rust via C++"
description: "Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett Markdown-dokument."
type: docs
url: /sv/rust-cpp/convert/save_markdown/
---

_Konverterar och sparar det tidigare öppnade PDF-dokumentet som ett Markdown-dokument._

```rust
pub fn save_markdown(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Konvertera och spara det tidigare öppnade PDF-dokumentet som Markdown-dokument
    pdf.save_markdown("sample.md")?;

    Ok(())
}
```