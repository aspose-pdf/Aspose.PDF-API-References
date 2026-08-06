---
title: "save_pptx"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-document aberto anteriormente como um documento PPTX."
type: docs
url: /pt/rust-cpp/convert/save_pptx/
---

_Converte e salva o PDF-document aberto anteriormente como um documento PPTX._

```rust
pub fn save_pptx(&self, filename: &str) -> Result<(), PdfError>
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

    // Converta e salve o PDF-document aberto anteriormente como PptX-document
    pdf.save_pptx("sample.pptx")?;

    Ok(())
}

```