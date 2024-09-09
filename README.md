# KenkartOtomasyonuApi
KenkartOtomasyonuApi, Kenkart Otomasyon sisteminin veritabanı ile etkileşimini sağlayan bir API'dir. Bu proje, Kenkart sistemindeki verilerin yönetilmesi ve erişimi için gerekli altyapıyı sunar.

Projenin Amacı
Bu API, Kenkart otomasyon sisteminin veritabanına güvenli ve verimli bir şekilde erişim sağlamak amacıyla geliştirilmiştir. Kullanıcıların, kart verilerini yönetmelerine ve sorgulamalarına olanak tanır.

Özellikler
Veritabanı Bağlantısı: API, Kenkart otomasyonunun veritabanına güvenli bir bağlantı sağlar.
Kullanıcı Yönetimi: Kullanıcı bilgilerini veritabanından çekme, güncelleme ve silme işlemlerini destekler.
Veri Yönetimi: Kart ve kullanıcı bilgilerinin yönetimi için gerekli CRUD (Create, Read, Update, Delete) operasyonlarını gerçekleştirir.
JSON Formatı: API, verileri JSON formatında döndürür ve gönderir, bu da veri paylaşımını standart ve kolay hale getirir.
Teknolojiler

.NET Core / .NET 6
Entity Framework Core: Veritabanı işlemleri için kullanılmıştır.
SQL Server: Veritabanı yönetim sistemi olarak kullanılmıştır.
Swagger: API dokümantasyonu için entegre edilmiştir.
Kurulum


Bu projeyi yerel makinenize klonlayın:
git clone https://github.com//RagnarLorthbro/KenkartOtomasyonuApi.git


Kullanım

Swagger arayüzünü kullanarak API uç noktalarını inceleyebilir ve test edebilirsiniz. API, aşağıdaki uç noktaları sunar:

/api/users - Kullanıcı bilgilerini listeler
/api/cards - Kart verilerini yönetir
