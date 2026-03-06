# membuat EC2 / instance / vm

1. pilih menu all services --> klik EC2
![alt text](image.png)

2. didalam menu EC2 pilih instance
![alt text](image-2.png)

3. didalam menu instance pilih launch instance
![alt text](image-3.png)

4. beri nama instance dengan format NIM_server
![alt text](image-4.png)

5. kita pilih OS server untuk instance
![alt text](image-5.png)

6. pilih resource instance T3.Micro (2VCPU, 1GB Memory)
![alt text](image-6.png)

7. Membuat key pair, pilih New key Pair, isi nama key, pilih RSA, format File .pem, create key pair
![alt text](image-7.png)

8. setting kebijakan keamanan / security group
   - Allow SSH -> ARtinya membolehkan remote SSH dari luar
   - Allow HTTPS -> Artinya instance bisa di akses dari protocol HTTPS
   - Allow HTTP -> Artinya instance bisa di akses dari protocol HTTP
![alt text](image-8.png)

9. Selesai Set-Up Pilih Launch Instance
![alt text](image-8.png)

10. Pastikan Launch Instance Sukses
![alt text](image-9.png)
