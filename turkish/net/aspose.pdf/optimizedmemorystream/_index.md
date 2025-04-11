---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptimizedMemoryStream sınıfı. Daha fazla standart kapasite içerebilen bir MemoryStream tanımlar
type: docs
weight: 7990
url: /tr/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream sınıfı

Daha fazla standart kapasite içerebilen bir MemoryStream tanımlar

```csharp
public class OptimizedMemoryStream : Stream
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | `OptimizedMemoryStream` sınıfının yeni bir örneğini başlatır. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Belirtilen bayt dizisine dayalı olarak `OptimizedMemoryStream` sınıfının yeni bir örneğini başlatır. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | `OptimizedMemoryStream` sınıfının yeni bir örneğini başlatır. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Belirtilen bayt dizisine dayalı olarak `OptimizedMemoryStream` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Temel tamponların boyutunu alır veya ayarlar. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın okuma desteği olup olmadığını belirten bir değer alır. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın arama desteği olup olmadığını belirten bir değer alır. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın yazma desteği olup olmadığını belirten bir değer alır. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Dispose sırasında temel tamponları serbest bırakıp bırakmayacağını belirten bir değer alır veya ayarlar. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Türetilmiş bir sınıfta geçersiz kılındığında, akışın bayt cinsinden uzunluğunu alır. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akış içindeki konumu alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Fonksiyon geçersiz kılındı. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akıştan bir bayt dizisi okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonundaysa -1 döner. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akış içindeki konumu ayarlar. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın uzunluğunu ayarlar. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Mevcut akışı bir bayt dizisine dönüştürür. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışa bir bayt dizisi yazar ve bu akış içindeki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Akıştaki mevcut konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Belirtilen akışa yazar. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Bayt cinsinden varsayılan tampon boyutu değeri. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)