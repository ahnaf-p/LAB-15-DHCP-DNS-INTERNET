# LAB-15-DHCP-DNS-INTERNET
Kamis 14 Agustus 2025  
  
# Mengkonfigrasi DHCP dan DNS  pada Mikrotik  
  ![topo](pppp.png)  

  1. Setting DHCP Client agar Mikrotik terhubung ke intrnet melalui ether1 yang terhubung ke ISP.  
![ada](client.PNG)  
  2. Buat IP static untuk ether2  
![dasd](addresses.PNG)  
  3. Setup DHCP Server untuk membagikan IP ke client secara otomatis.  
![wasd](server.PNG)  
  4. Setting DNS, masukan DNS google.  
![qwerty](beress.PNG)  
  5. Tambahkan Firewall NAT agar client bisa mengakses ke internet.  
![sdfs](dns.PNG)  
  6. Pindah ke PC Client dan jangan lupa untuk setting IP nya jadi obtain auto.  
![djas](api.PNG)  
  7. Cek apakah mendapat IP, di PC client.  
     PC1:  
     ![dkaiojasd](CLIENTTT.PNG)  
     PC2:  
     ![fnsushe](ahnafcb.PNG)  


# Kesimpulan
  Dengan DHCP Server, pembagian alamat IP, gateway, dan DNS ke perangkat klien dilakukan secara otomatis, sehingga meminimalkan kesalahan konfigurasi manual dan menghemat waktu.
