# Flaskr - A Simple Blog Application

Flaskr, Flask ile yapılmış minimal bir blog uygulamasıdır. Kullanıcılar, kayıt olabilir, giriş yapabilir, yazı oluşturabilir, yazılarını düzenleyebilir veya silebilir. Proje, kolayca kurulabilir ve özelleştirilebilir olacak şekilde tasarlanmıştır.

## Özellikler
- Kullanıcı kimlik doğrulaması (kayıt olma, giriş yapma, çıkış yapma)
- Yazı oluşturma, düzenleme ve silme
- Yazıların ters kronolojik sırayla görüntülenmesi
- Yazıların yalnızca yazarları tarafından düzenlenmesi/silinmesi
- SQLite veritabanı entegrasyonu

## Çalıştırma

Aşağıdaki komutları kullanarak Flaskr'ı çalıştırabilirsiniz:

```sh
flask --app flaskr run --debug ("Database Initialized init-db")

