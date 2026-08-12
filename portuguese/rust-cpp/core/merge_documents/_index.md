---
title: "merge_documents"
second_title: "Aspose.PDF para Rust via C++"
description: "Cria um novo PDF-document mesclando os PDF-documents fornecidos."
type: docs
url: /pt/rust-cpp/core/merge_documents/
---

_Cria um novo PDF-document mesclando os PDF-documents fornecidos._

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
    // Crie um novo PDF-document
    let pdf1 = Document::new()?;

    // Abrir um PDF-document chamado "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Criar um novo PDF-document mesclando os PDF-documents fornecidos
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```