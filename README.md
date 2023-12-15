# Webmin-menggunakan-VPS-di-Proxmox
1. PilIh Install Proxmox VE untuk memulai instalasi standar 

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/c20a6149-01b3-437e-b1b2-640adadfcc9d)

2.Tunggu proses instalasi proxmox

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/6217aa54-3d3d-4af2-859a-1011b6aa1ac8)

3. Baca dan click”I agree” untuk melanjutkan

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/1e155b7c-b151-4b6b-adda-f96cba930c9b)

4. Baca dan click”Next” 

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/a5ea6476-9c8c-44ed-84bd-cd1dc640474e)

5. Atur lokasi, zona waktu dan tata keyboard. lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/7c59021d-902f-4c32-a398-22fc201e4c0d)

6. Buat kata sandi dan alamat email untuk pemberitahuan administrator sistem, lalu click “next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/5a85c586-6ae1-4981-90f2-dd20dd93eea4)

7. Pilih antarmuka manajemen, nama host untuk server, alamat IP yang tersedia, gateway default, dan server DNS. Lalu click “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/49f3904b-0a81-4fd9-b348-27e1b0705902)

8. Baca lalu click “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/dff502e6-d921-41c3-8a07-ad326dfc3010)

9. Tunggu sampai proses install selesai. Proxmox terinstall.

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/fb87f116-f61c-45b0-9758-7a30b5389575)

10. Run Proxmox.   

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/2f2fda1f-2ec5-429c-88b1-e6bc93599390)

11. Buka browser lalu masukan ip dan beri port 8006
contoh : 192.168.100.44:8006

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/ebf9c9d3-8a8f-4175-8c0a-db86dc961ec5)

12.Akses proxmox masih belum menerapkan SSL (Secure Socket Layer). 

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/2b58e958-d054-4212-8626-8003b436f0c8)

13. Login akun yang sudah dibuat saat instalasi. klik “Login”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/57c1eb3c-0c3d-498e-9974-5fa4548665d9)

14. Upload iso vm. Pilih local >> iso image >> pilih upload

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/59cb4b4d-5430-43f2-85af-a04b3097b1ef)

15. Pilih Select File untuk file yang akan anda upload, dan berikan nama file pada file yang akan anda upload. setelah itu klik upload.

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/e9e1c197-f997-4f06-82e8-6070c79dfd32)

16. Proses upload sedang berjalan, tunggu sampai selesai. jika sudah terupload klik “Finish”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/4cde9e61-c0cc-45f0-a1e1-751f9d958e70)

17. Membuat VPS KVM di Proxmox. Masuk ke datacenter lalu local dan klik create vm.

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/297a6bc3-826e-48fb-981e-55102db6de81)

18. Berikan nama VPS anda. klik Next.

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/d1b4d1e3-d560-4bbc-8bed-ee6ba00ad25f)

19. Pilih iso image yang telah di upload lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/14f7195a-2b1a-4f39-956e-fa11e0dffa5c)

20. Atur system VPS lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/bab8626f-3c4d-4f93-8b9c-ce371fd1a69f)

21. Atur disk VPS lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/114a8fb6-5498-4fc6-a569-efeb1910956a)

22. Atur CPU VPS lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/3993a0e7-ca88-4be7-9a19-86129ad9e995)

23. Atur memory VPS lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/1b3cc224-2329-4e98-aa27-8552b4beb576)

24. Atur network pada VPS. lalu klik “Next”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/7ca88817-4f48-4fa3-b54f-0a9151c6314b)

25. Klik finish

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/603d2b5a-6ae2-400b-b570-4df70a0936d8)

