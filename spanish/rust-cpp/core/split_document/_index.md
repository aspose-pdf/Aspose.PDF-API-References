---
title: "split_document"
second_title: "Aspose.PDF para Rust vía C++"
description: "Crea varios PDF-documentos nuevos extrayendo páginas del PDF-documento fuente."
type: docs
url: /es/rust-cpp/core/split_document/
---

_Crea varios PDF-documentos nuevos extrayendo páginas del PDF-documento fuente._

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
    // Abrir un PDF-documento llamado "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Crea varios PDF-documentos nuevos extrayendo páginas del PDF-documento fuente
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // Guardar cada parte dividida como un PDF-documento separado
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```