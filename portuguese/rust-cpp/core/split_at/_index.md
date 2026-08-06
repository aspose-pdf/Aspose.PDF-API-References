---
title: "split_at"
second_title: "Aspose.PDF para Rust via C++"
description: "Divide o PDF-document atual em dois novos PDF-documents."
type: docs
url: /pt/rust-cpp/core/split_at/
---

_Divide o PDF-document atual em dois novos PDF-documents._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document chamado "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Divida o PDF-document atual em dois novos PDF-documents
    let (left, right) = pdf_split.split_at(2)?;

    // Salvar cada parte dividida como um PDF-document separado
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```