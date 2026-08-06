---
title: "save_doc"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o PDF-document aberto anteriormente como um documento DOC."
type: docs
url: /pt/rust-cpp/convert/save_doc/
---

_Converte e salva o PDF-document aberto anteriormente como um documento DOC._

```rust
pub fn save_doc(&self, filename: &str) -> Result<(), PdfError>
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

    // Converta e salve o PDF-document aberto anteriormente como Doc-document
    pdf.save_doc("sample.doc")?;

    Ok(())
}

```