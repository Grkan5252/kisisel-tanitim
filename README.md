# Kişisel Tanıtım Sayfam

Bu projeyi yazılıma giriş yapmak ve GitHub kullanımını öğrenmek amacıyla hazırladım.

## Kullandığım teknolojiler

- HTML
- CSS


## Neler içeriyor?

- Hakkımda, öğrenme hedefleri ve çalışma planı
- Sayfa içi gezinme bağlantıları
- Kısa bir öğrenme yazısı

## Nasıl açılır?

Proje dosyalarını indirin ve index.html dosyasını tarayıcıda açın.

## Öğrendiklerim

- Anlamlı HTML etiketleriyle sayfayı bölümlere ayırmak
- Sayfa içi bağlantılar oluşturmak
- Git ile değişiklikleri kaydetmek ve GitHub’a göndermek
- CSS seçicileriyle yazı renklerini, boyutlarını, iç ve dış boşlukları ve çerçeveleri düzenledim.


## İletişim formu

- Formda 4 alan bulunur (ad,e-posta,konu,mesaj).
- Dört alan da required ile zorunludur. E-posta alanında ayrıca type="email" ile biçim kontrolü yapılır.
- Bu form öğrenme amaçlıdır; mesajı kaydeden veya e-posta gönderen bir backend bağlantısı yoktur.
- GET yöntemiyle gönderilen bilgiler URL'nin sorgu bölümünde görünür.

## Tekrar notum
`git commit -m "Açıklama"`, hazırlama alanındaki değişiklikleri yerel Git geçmişine kaydeder.

`git add`, dosyanın o anki değişikliklerini bir sonraki commit için hazırlama alanına alır.

`git push`, commitle hazırlanan değişikleri git hafızasından alıp githuba yollamayı sağlar.

`id `, bir kimliktir. bir elemente verildiği zaman o id'li elemente sayfa içinden heryerden ulaşabiliriz.

`name` gönderilen mesajın alan adı'dır. 

`id ve name farkı` birisi elementi temsil eder, diğeri ise gönderilen verinin alan adını belirler . 

## Kutuları ve görselleri dar ekrana uyarlama

- Görsellerde `max-width: 100%`, görselin bulunduğu alandan geniş olmasını engeller; gerektiğinde küçülmesini sağlar. `height: auto`, en-boy oranını korur.
- Kutuları `width: 100%` ile kullanılabilir alana uyarladım, `max-width` ile genişliklerine üst sınır koydum ve `box-sizing: border-box` ile iç boşlukları ve çerçeveyi bu genişliğe dahil ettim.