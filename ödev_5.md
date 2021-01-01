#### <u>SQLite ve LocalDB</u>

​	SQLite bir veritabanı kütüphanesidir. Çalışması için herhangi bir sunucuya ihtiyacı yoktur. Bu yüzden kurulum veya konfigürasyon adımları gibi gereklilikleri yoktur. Ancak sunucu kullanan veritabanları daha güvenlidir.

LocalDB, Microsoft'un yazılımcılar için hedeflediği SQL Server Express'in bir özelliğidir. Bu sayede tam bir SQL Server kurulumu yapmadan çoğu SQL Server özelliği kullanılabilir. Daha kompakt bir yapıya sahiptir. Kolay bir kurulumu vardır. 

#### <u>Lazy Loading</u>

​	Lazy Loading, örnek olarak bir web sayfasında ihtiyaç duyulan bir resmin ihtiyaç duyulduğu zaman çağrılması mantığı ile çalışır. İhtiyaç olduğu zaman veritabanına sorgu atılır ve tüm veri tablosu yerine gereken bilgiler alınır. Tekrar başka bir veriye ihtiyaç olduğu zaman tekrar bir sorgu atılır ve bu böyle devam eder. Bu kavramın zıttına Eager Loading denir. Bu durumda tüm veri seti veritabanından alınır ve bekletilir. Veri ihtiyacı olduğu zaman bu bekletilen veriler kullanılır. Lazy Loading, sık sık veritabanından sorgu yaptığı için çok büyük veritabanlarında performans olarak biraz daha yavaş kalmaktadır. 

#### <u>Kaynakça</u>

https://www.isimtescil.net/bilgibankasi/sqlitein-tum-avantajlar-ve-dezavantajlar

https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/sql-server-express-localdb?view=sql-server-ver15#:~:text=Microsoft%20SQL%20Server%20Express%20LocalDB,Server%20Express%20targeted%20to%20developers.&text=LocalDB%20installation%20copies%20a%20minimal,using%20a%20special%20connection%20string.

https://www.inploid.com/t/localdb-nedir-ve-neden-kullanilir/52604/

https://medium.com/@e.karabudak7/lazy-loading-vs-eager-loading-67d09c6a251

https://marsus.com/lazy-load-nedir/

https://www.kukumav.net/blog/lazy-load-kullanimi/