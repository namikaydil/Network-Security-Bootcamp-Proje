# Network-Security-Bootcamp-Proje

 Omurga IPv4 ve IPv6 dual stack olarak çalışabilmeli
 IPv4 ve IPv6 kendi içlerinde OSPF ile haberleşebilmeli
 Hem IPv4 hem de IPv6 omurga, ACL ile sadece istenilen servis portlarından hizmet verebilmeli
 Kullanılmayan diğer portlar kapatılmalı

# Yapılanlar

End Device'ların IP, GW ve DNS ayarlarını yaptım

Switch ve Router'ların Basic ayarlarını yaptım
Bütün cihazlar için;

Password: sunum
Secret: namik
Routerların Interface ayarlarını yaptım

Ping testlerini yaptım ping alıp almadıklarını kontrol ettim
Dynamic routing ospf ayarlarını yaptım

End device'lar server'lara erişip ping atabiliyor
End device'lar birbirlerine ping atabiliyor
Istanbul network'une IPv4 ve IPv6 omurgalarının erişimini kısıtlamak için ACL yazdım

TCP ve UDP izinleri verildi bu yüzden Izmir ve Ankara networklerindeki cihazlar serverlara icmp paket gönderemiyor

Bütün networklerdeki kullanılmayan portları kapattım
Test cihazları ekleyip portların kapalı olduğunu kontrol ettim
Test Cihazlarını sildim

Son kontrolleri yaptım

Bu işlemleri önce ipv4 için yaptım istenilenleri elde ettikten sonra aynı işlemleri ipv6 için yaptım
Omurga IPv4 ve IPv6 dual stack olarak çalışır duruma geldi

# Bütün işlemleri proje üstüne not aldım görüntü kirliliği olmasın diye "<" kullanarak gizledim. O yüzden buraya detaylı olarak yazmıyorum
