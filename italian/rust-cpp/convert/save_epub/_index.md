---
title: "save_epub"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva il PDF-document precedentemente aperto come EPUB-document."
type: docs
url: /it/rust-cpp/convert/save_epub/
---

_Converte e salva il PDF-document precedentemente aperto come documento EPUB._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // Converti e salva il PDF-document precedentemente aperto come documento Epub
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```