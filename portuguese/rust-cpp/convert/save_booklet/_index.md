---
title: "save_booklet"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-document aberto anteriormente como um PDF-document em formato de folheto."
type: docs
url: /pt/rust-cpp/convert/save_booklet/
---

_Converte e salva o PDF-document aberto anteriormente como um PDF-document em formato de folheto._

```rust
pub fn save_booklet(&self, filename: &str) -> Result<(), PdfError>
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

    // Converta e salve o PDF-document aberto anteriormente como PDF-document em formato de folheto
    pdf.save_booklet("sample_booklet.pdf")?;

    Ok(())
}
```