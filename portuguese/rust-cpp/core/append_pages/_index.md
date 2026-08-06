---
title: "append_pages"
second_title: "Aspose.PDF para Rust via C++"
description: "Anexa páginas selecionadas de outro PDF-document."
type: docs
url: /pt/rust-cpp/core/append_pages/
---

_Anexa páginas selecionadas de outro PDF-document._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir o PDF-document principal
    let pdf = Document::open("sample1page.pdf")?;

    // Abrir outro documento PDF para anexar
    let another_pdf = Document::open("sample.pdf")?;

    // Anexar páginas específicas (1 e 3) de outro PDF-document
    pdf.append_pages(&another_pdf, "1,3")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```