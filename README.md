WEBMIN

Dibuat oleh :

Sakti Abadi (21050974074)

Deskripsi

Webmin adalah perangkat lunak administrasi server berbasis web yang menyediakan antarmuka pengguna grafis (GUI) untuk mengelola dan mengonfigurasi server Linux dan sistem berbasis Unix. Dengan Webmin, administrator sistem dapat melakukan berbagai tugas administratif melalui browser web tanpa harus mengandalkan baris perintah.

Fitur WEBMIN

1. Manajemen Pengguna dan Grup: Webmin memungkinkan administrator untuk membuat, menghapus, dan mengelola pengguna serta kelompok pengguna pada sistem.

2. Konfigurasi Jaringan: Administrasi konfigurasi jaringan seperti pengaturan antarmuka jaringan, konfigurasi DNS, dan konfigurasi firewall dapat dilakukan melalui antarmuka Webmin.

3. Manajemen Layanan: Webmin mendukung manajemen layanan seperti Apache, MySQL, dan layanan sistem lainnya. Administrator dapat memulai, menghentikan, atau mengonfigurasi layanan dengan mudah.

4. Pengelolaan File dan Direktori: Webmin memungkinkan administrator untuk menjelajah sistem file, mengelola izin file dan direktori, serta melakukan operasi dasar pada berkas dan folder.

5. Pemantauan Sistem: Informasi tentang penggunaan sumber daya sistem seperti CPU, RAM, dan ruang disk dapat diakses melalui modul pemantauan sistem Webmin.

6. Manajemen Sekuritas: Webmin menyediakan alat untuk mengelola keamanan sistem, termasuk konfigurasi firewall, sertifikat SSL, dan manajemen kunci SSH.
   

Install WEBMIN menggunkan Proxmox


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

26. Install Webmin. Cek IP dengan perintah
“ip a”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/b0ebc7d7-220e-4005-a46c-f7f7e18b80f2)

27. Install curl
“apt install curl”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/b3620260-a7c5-4893-85ce-e042d6be69c2)

28. Masukkan repository webmin dengan peintah
“curl -o setup-repos.sh https://raw.githubusercontent.com/webmin/webmin/master/setup-repos.sh” Konfifirmasi dengan perintah 
“sudo sh setup-repos.sh”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/196ae652-ce3a-4f39-a2a6-e7f5f3ce4e76)

29. Install webmin
“apt-get install webmin”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/aee6ffc1-4e88-4862-a3e6-1abdf1ac1797)

30. Masuk ke “nano /etc/webmin/miniserv.conf”
Ubah port 10000 menjadi 8080

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/1833322a-bb18-4fa1-ac57-36b515a5d44e)

31. Restart webmin
“systemctl restart webmin”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/5aeec06e-8969-48d8-be35-e6d8a343d022)

32. Cek IP dengan perintah
“ip a”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/abc328d4-ec11-4762-bb23-727c06038a04)

33. Ketik https://ip ubuntu:8080 pada browser >> Klik advance >> Klik proceed to ip

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/bbbe7667-4493-4eca-bd91-f92dff113f42)

34. Masukkan Username dan Password yang sama seperti login Ubuntu

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/dc476d32-3fb4-4e08-8777-456fc138cd65)

35. Tampilan dashboard webmin

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/17924c1f-ddff-447e-8e3a-c509448ee99a)

36. Buka website https://cs.indocenter.co.id/clientarea.php >> Klik “Domains” >> Klik “My Domains”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/2cf85068-6d23-4b30-b237-cd42f77b144d)

37. Klik Lambang kunci

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/f942e41c-39a3-49d6-8f68-72d0d6e42a0a)

38. Klik “Private Nameserver”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/ae187760-7f11-4ec2-8162-6af1269aeb47)

39. #Register nameserver dan IP Address
Private nameserver >> ubah nameserver menjadi “ns1” >> masukkan ip address server >> Save Changes

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/7ad787e1-1fe2-4e2d-8ef3-8937e564de8f)

40. #Register nameserver dan IP Address
Private nameserver >> ubah nameserver menjadi “ns2” >> masukkan ip address server >> Save Changes

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/18f1a12b-022d-4b83-8c74-33ab3a92979d)

41. Klik “Nameserver”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/ed504ab7-ce60-4b3c-af67-16aaee8b0835)

42. Ubah ceklis ke “Use custom nameservers(enter below)” >> Ubah nameserver 1 menjadi “ns1.(domain)” >> Ubah nameserver 2 menjadi “ns2.(domain)” >> Changes Nameserver

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/f94be41e-033b-476e-87a2-ed4958e9c0c2)

43. Buka kembali dashboard webmin

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/6ae5d6b9-489c-4e5d-8f4e-94acb638e52f)

44. Install BIND DNS Server pada Webmin

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/102ab590-00f7-414a-a154-8f60db04b71d)

45. Install Packages

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/d3704186-fc08-4fcd-96a1-c9cdf89e3640)

46. #Buat master zone baru
Un-used Modules >> BIND DNS Server >> Create master zone

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/30bd9729-bc7f-4f5f-a7f1-89141a91b6d4)

47. #Buat master zone
Isi “Domain name” dengan domain anda >> Isi “Master zone” dengan “ns1.(domain)” >> Isi email address >> Isi “IP address for template records” dengan IP server >> Klik “Create” >> Klik “Return to zone list”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/5fa4da60-b6b7-40cf-befa-97cbf31139dc)

48. Klik “Address”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/0268da1c-821c-4802-b8ac-5e70fb656081)

49. Isi “Name” dengan “ns1.(domain)” >> Isi “Address” dengan IP Server >> Klik “Create”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/ee3be883-1d7a-485b-9bbb-9f5bc1487434)

50. Isi “Name” dengan “ns2.(domain)” >> Isi “Address” dengan IP Server >> Klik Create

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/8ce598cc-a338-4de1-9f0a-32467124aeaf)

51. Jika sudah menambahkan semua klik “Return to record types”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/47b31b1b-0b74-4c6c-8e9b-59012b26fad2)

52. Setting Nameserver dengan klik “Name Server”

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/b7184af5-d3e1-4dfa-a163-2d013904d6a9)

53. Isi Zone Name dengan domain >> Isi Name Server dengan “ns2.(domain)” >> Klik Create

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/1690ab9e-ae9b-49be-8c41-7db5479126f5)

54. Pastikan sudah terinput Name dan Name Servernya

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/17c0b800-eb2d-4458-a570-979d7e139977)

55. Simpan konfigurasi

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/f7aec604-4e68-4027-bf5e-43559194eda7)

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/2433de76-6434-4801-ba9d-0ed8ee1ebb36)

56. Buka website https://pandi.id/whois untuk cek nameserver apakah sudah berubah menjadi nameserver yang telah dibuat

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/9ccefda7-a567-4dd4-abda-6df07828fa09)

57. Buka website https://intodns.com/ untuk pengecekan apakah semua konfigurasi semua sudah benar atau belum

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/a2422177-9715-49fc-86fa-7670139f9391)

58. Buka website https://www.whatsmydns.net/ lalu masukkan domain dan pilih record NS yang berfungsi untuk menampilkan informasi tentang catatan NS dari suatu domain di berbagai server DNS di seluruh dunia. Cek juga yang record A untuk menampilkan informasi tentang catatan A dari suatu domain di berbagai server DNS di seluruh dunia.

![image](https://github.com/saktiabadi/Webmin-menggunakan-VPS-di-Proxmox/assets/47803981/95440350-714e-4357-99fb-c13ded5431a3)
