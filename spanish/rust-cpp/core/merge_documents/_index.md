---
title: "merge_documents"
second_title: "Aspose.PDF para Rust vía C++"
description: "Crea un PDF-document nuevo fusionando los PDF-documents proporcionados."
type: docs
url: /es/rust-cpp/core/merge_documents/
---

_Crea un PDF-document nuevo fusionando los PDF-documents proporcionados._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crear un nuevo PDF-documento
    let pdf1 = Document::new()?;

    // Abrir un PDF-documento llamado "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Crear un PDF-document nuevo fusionando los PDF-documents proporcionados
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```