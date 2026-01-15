Company Brochure Generator

Company Brochure Generator, bir şirketin web sitesi açılış (landing) sayfasını analiz ederek; potansiyel müşteriler, yatırımcılar ve işe alım adayları için kısa, anlaşılır ve profesyonel bir şirket broşürü oluşturan yapay zekâ tabanlı bir uygulamadır.

Bu proje hem bulut tabanlı büyük dil modelleri (GPT) hem de yerel modeller (Ollama) ile çalışacak şekilde tasarlanmıştır ve canlı (streaming) çıktı üretir.

Özellikler

Şirket web sitesi (URL) analizi

Markdown formatında broşür üretimi

Model seçimi (GPT / Ollama)

Canlı cevap üretimi (streaming)

Gradio tabanlı kullanıcı arayüzü

Kullanıcı adı / şifre ile erişim (opsiyonel)

Deneysel ve genişletilebilir mimari

Nasıl Çalışır?

Kullanıcı:

Şirket adını girer

Açılış sayfası URL’sini girer

Kullanılacak LLM modelini seçer

Uygulama:

Web sayfası içeriğini alır

İçeriği analiz eder

Hedef kitleye uygun bir şirket broşürü oluşturur

Çıktı:

Canlı olarak ekranda görüntülenir

Okunabilir ve profesyonel bir formatta sunulur

Kullanılan Teknolojiler

Python

Gradio (arayüz ve streaming)

OpenAI API (GPT-4.1-mini)

Ollama (llama3.2:latest)

Generator ve yield tabanlı streaming mimarisi

Arayüz

Tek bir arayüz üzerinden:

Mesaj girişi

Model seçimi

Canlı sonuç görüntüleme

Demo amaçlı örnek girdiler kullanıcıya hazır olarak sunulmaktadır.

Güvenlik Notu

Projede Gradio’nun yerleşik kimlik doğrulama (authentication) mekanizması desteklenmektedir.
Demo ve local kullanım için uygundur.
Production ortamlar için ortam değişkenleri (.env) kullanılması önerilir.

Kullanım Alanları

Startup ve şirket tanıtımları

Yatırımcı sunumları

Hızlı şirket özetleri

MVP / POC çalışmaları

Yapay zekâ destekli içerik üretimi

Notlar

Proje deneysel bir Ar-Ge yaklaşımıyla geliştirilmiştir.

Kod yapısı yeni modeller eklemeye uygundur.

Eğitim, demo ve prototipleme amaçları için idealdir.

Katkı ve Geri Bildirim

Katkılara ve geri bildirimlere açıktır.
Pull request veya issue açabilirsiniz.