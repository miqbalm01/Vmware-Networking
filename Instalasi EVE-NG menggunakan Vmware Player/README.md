# Pra-instalasi EVE-NG

Download Tools Vmware player dan VM EVE-NG untuk Latihan Networking menggunakan EVE-NG

 1. Vmware player (free)
https://customerconnect.vmware.com/en/downloads/details?downloadGroup=PLAYER-1556&productId=800&rPId=47861
 2. VM EVE-NG (Community/Free edition)
https://www.eve-ng.net/index.php/download/

## Langkah instalasi EVE-NG di vmware player/workstation:

 1. Pertama, Anda perlu menginstal VMware Player/Workstation di komputer Anda.
![enter image description here](https://github.com/miqbalm01/Vmware-Networking/blob/ffd3b79fa7e1810685ad559aec58db55c39b9aa2/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image1.png?raw=true)

 2. Setelah instalasi VMware Player atau Workstation selesai, buka program tersebut. Selanjutnya, ekstrak file EVE-COMM-VM.zip ke lokasi yang sesuai di komputer Anda.
![image2.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image2.png?raw=true)

 3. Di VMware Player atau Workstation, pilih opsi " **Open a Virtual Machine** " untuk membuka jendela untuk mengimpor mesin virtual.
![image3.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image3.png?raw=true)

 4. Cari dan pilih file OVF dari EVE-NG yang telah Anda ekstrak sebelumnya.
![image4.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image4.png?raw=true)

 5. Lanjutkan dengan mengimpor file OVF tersebut dan Tambahkan Nama Project. Lalu Klik Import dan tunggu hingga prosesnya selesai.
![image5.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image5.png?raw=true)

 6. Pastikan bahwa pengaturan jaringan VM EVE-NG diatur ke "Bridged."![image6.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image6.png?raw=true)
 7. Sesuaikan alokasi memori untuk VM EVE-NG. Disarankan minimal 2 GB, tetapi lebih disarankan untuk mengalokasikan 4 GB atau lebih jika memungkinkan.
![image7.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image7.png?raw=true)
 8. Power-on/Start EVE-NG VM
![image8.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image8.png?raw=true)

 9. Setelah VM EVE-NG selesai booting, pastikan ada alamat IP yang ditampilkan di atas layar login.
![image9.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image9.png?raw=true)

 10. Login ke VM EVE-NG menggunakan akun berikut:
User: root
Password: eve
![image10.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image10.png?raw=true)

 11. Ikuti proses setup wizard atau menu awal yang muncul saat pertama kali menjalankan EVE-NG.
![image11.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image11.png?raw=true)

 12. Pilih IP Address DHCP agar secara otomatis akan mendapatkan IP
![image12.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image12.png?raw=true)

 13. Pada bagian NTP Server kosongkan saja
![image13.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image13.png?raw=true)

 14. Lalu pada proxy server configuration, pilih direct connection. Setelah itu sistem akan menyimpan data yang ada input dan sistem akan melakukan restart.
![image14.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image14.png?raw=true)

### Untuk memastikan Eve-NG berjalan.

 1. Pertama, Buka peramban web Anda dan masukkan alamat IP EVE-NG
    dalam peramban tersebut. IP didapatkan dari Eve-NG pada saat akan login.
![image15.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image15.png?raw=true)

2. Login ke antarmuka web EVE-NG menggunakan akun berikut:
User: admin
Password: eve
![image16.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image16.png?raw=true)

3. Setelah login, tampilan awal EVE-NG akan kosong karena Anda belum membuat lab.
![image17.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image17.png?raw=true)

16. lalu balik ke Vmware server dan lakukan login untuk memastikan VMware berjalan.
username : root
password : anda yang telah kamu buat pada step 12
![image18.png](https://github.com/miqbalm01/Vmware-Networking/blob/main/Instalasi%20EVE-NG%20menggunakan%20Vmware%20Player/Image/image18.png?raw=true)
Untuk mematikan VM EVE-NG, Anda dapat masuk ke command-line VM dan menjalankan perintah berikut: `poweroff`

