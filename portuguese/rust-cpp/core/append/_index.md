---
title: "append"
second_title: "Aspose.PDF para Rust via C++"
description: "Anexa páginas de outro PDF-document."
type: docs
url: /pt/rust-cpp/core/append/
---

_Anexa páginas de outro PDF-document._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir o PDF-document principal
    let pdf = Document::open("sample.pdf")?;

    // Abrir outro documento PDF para anexar
    let another_pdf = Document::open("sample1page.pdf")?;

    // Anexar páginas de outro documento PDF
    pdf.append(&another_pdf)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```