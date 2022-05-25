# ConfigurationReaderApp

Bu uygulamada .NET CORE 6 sürümü kullanılmıştır.

## Yapılması gerekenler\
1-ConfigurationApp içindeki docker-compose.yml dosyası ile redis serverini localhostta kurmak (docker-compose -f docker-compose.yml up).\
2-ConfigurationApp projesini build aldıktan sonra oluşan dll dosyasını projenize referans göstermek.\
3-Projeninizde bulunan bin/debug/net6.0 dizininin içine records.db dosyasını atmak.\
Bu adımlardan sonra ConfigurationApp içindeki GetValue<T>(string key) methodu kullanabilirsiniz.
  
## Test Çalışmaları\
ConfigurationTestUnit projesi içinde kullanabileceğiniz 3 adet test methodu yazılmıştır.
