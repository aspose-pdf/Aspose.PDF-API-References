---
title: "save_epub"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-documento previamente aberto como um EPUB-document."
type: docs
url: /pt/rust-cpp/convert/save_epub/
---

_Converte e salva o PDF-document aberto anteriormente como um documento EPUB._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converta e salve o PDF-document aberto anteriormente como Epub-document
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```