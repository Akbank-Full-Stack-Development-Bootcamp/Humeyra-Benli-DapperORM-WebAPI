# Dapper ORM Nedir?
ORM nedir? ilk olarak bu soruyu cevaplandıralım. ORM yani Object Relational Mapping, veritabanını doğrudan projelerinizdeki nesnelerle eşleyen bir yapıdır. Kodlarınız ile veritabanı arasındaki bir köprü gibi düşünebiliriz. ORM kullanarak veritabanından verileri okuyabilir ve veriler üzerinde değişiklikler yapabilirsiniz. ORM ile artık SQL sorguları yazmamıza gerek kalmıyor ve veritabanı ile doğrudan iletişime geçebiliyoruz.

Her programlama dilinde ORM bulunmaktadır. Bunlara bir kaç örnek verelim.

C# için "Entity Framework Core, Dapper", Python için "Django, Storm", Java için de "Hibernate, Ebean" örneklerini verebiliriz.

Dapper Micro ORM özellikleri:
- Performans açısından hızlıdır. En hızlı 2. ORM'dir.
- CRUD işlemlerini doğrudan IDBConnection nesnesini kullanarak gerçekleştirir.
- Veritabanı üzerinden statik ve dinamik verilerin sorgulanmasını sağlar.
- Dapper sadece tek bir "Dll"dir. Bu yüzden hızlıdır.
- Configuration dosyasına ihtiyaç duymaz.
- Stackoverflow tarafından geliştirilmiş bir ORM'dir.

Bu repoda Dapper ORM kullanılarak geliştirilmiş bir Web API proje örneği bulunmaktadır.
