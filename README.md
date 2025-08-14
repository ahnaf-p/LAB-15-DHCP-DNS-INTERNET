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
![setup](beress.PNG)  
  5. Setting DNS, masukan DNS google.  
![qwerty](dns.PNG)  
  6. Tambahkan Firewall NAT agar client bisa mengakses ke internet.  
![sdfs](api.PNG)  
  7. Pindah ke PC Client dan jangan lupa untuk setting IP nya jadi obtain auto.  
  8. Setelah selesai, sekarang cek ke PC client, apahak sudah dapat IP.  
     PC1:  
     ![dkaiojasd](CLIENTTT.PNG)  
     PC2:  
     ![fnsushe](ahnafcb.PNG)  


# Kesimpulan
  Dengan DHCP Server, pembagian alamat IP, gateway, dan DNS ke perangkat klien dilakukan secara otomatis, sehingga meminimalkan kesalahan konfigurasi manual dan menghemat waktu.
