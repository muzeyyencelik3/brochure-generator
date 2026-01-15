# brochure-generator
A tool that generates company brochures by analyzing landing pages using GPT or Ollama.

Broşür Oluşturucu (Company Brochure Generator)

Bu proje, bir şirketin web sitesi açılış sayfasını analiz eden ve potansiyel müşteriler, yatırımcılar veya işe alım adayları için kısa bir broşür oluşturan bir araçtır.

Modeller:

Ollama (llama3.2:latest) → Lokal, ücretsiz

OpenAI GPT (gpt-4.1-mini) → Bulut, API anahtarı gerekir, ücretli

Özellikler:

Web sayfası içeriğini otomatik çekip analiz eder

Markdown formatında, kod blokları olmadan broşür üretir

Streaming yanıt ile uzun metinler anlık gösterilir

Basit Gradio arayüzü ile kullanıcı dostu kullanım

Kurulum:

Python ortamı oluşturun (venv)

pip install -r requirements.txt ile bağımlılıkları yükleyin

view.launch(inbrowser=True) ile arayüzü başlatın

Kullanım örnekleri:

Hugging Face → https://huggingface.co (GPT)

OpenAI → https://openai.com (Ollama)

Lokal kullanım için Ollama ücretsiz, GPT kullanımı için OpenAI API key gereklidir.
