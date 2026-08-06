---
title: "split_document"
second_title: "Aspose.PDF para Rust via C++"
description: "Cria vários novos PDF-documents extraindo páginas do PDF-document fonte."
type: docs
url: /pt/rust-cpp/core/split_document/
---

_Cria vários novos PDF-documents extraindo páginas do PDF-document fonte._

```rust
pub fn split_document(document: &Document, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document chamado "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Cria vários novos PDF-documents extraindo páginas do PDF-document fonte
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // Salvar cada parte dividida como um PDF-document separado
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```