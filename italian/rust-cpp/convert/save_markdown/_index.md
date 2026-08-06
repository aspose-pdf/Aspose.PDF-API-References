---
title: "save_markdown"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva il documento PDF precedentemente aperto come documento Markdown."
type: docs
url: /it/rust-cpp/convert/save_markdown/
---

_Converte e salva il documento PDF precedentemente aperto come documento Markdown._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva il documento PDF precedentemente aperto come documento Markdown
    pdf.save_markdown("sample.md")?;

    Ok(())
}
```