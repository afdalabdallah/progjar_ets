| **NRP** | **Nama** | 
| ----------- | -------- |
| 5025201163 | Muhammad Afdal Abdallah |

## Notes

Segala file yang di edit terdapat pada folder progjar5

### Multithread
> server_thread_http.py
![image](https://user-images.githubusercontent.com/90978855/229297821-7122b832-28a1-46c2-a673-7754c8cfd11a.png)
<br>
Pada multithread, inisialisasi server menggunakan library thread untuk membuat thread baru

### Multiprocess
> server_process_http.py
![image](https://user-images.githubusercontent.com/90978855/229297955-77a3e48a-da1c-4062-87ac-4f5e119a3fc5.png)
<br>
Pada multiprocess, inisialisasi server menggunakan library multiprocess untuk membuat process baru

### Multithread (secure)
> server_thread_http_secure.py

### Multiprocess (secure)
> server_process_http_secure.py

## Perbedaan kode secure dan non-secure
Pada program secure, terdapat tambahan potongan kode untuk mengambil certificate dan key yang sudah digenerate pada folder certs dengan command openssl.
<br>
![image](https://user-images.githubusercontent.com/90978855/229297721-474bd6d0-3366-4002-8543-0db3f0a0854e.png)
<br>
Letak potongan kode tersebut sama untuk program multithread dan multiprocessing.
