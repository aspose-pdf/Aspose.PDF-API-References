---
title: "page_to_pdf"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva a página especificada como um PDF-document."
type: docs
url: /pt/rust-cpp/convert/page_to_pdf/
---

_Converte e salva a página especificada como um PDF-document._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Converter e salvar a página especificada como PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```