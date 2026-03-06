# Remote Instance with SSH putty

1. Pastikan sudah install putty
![alt text](image-10.png)

2. Koneversi file public key dari .pem menjadi .ppk di putty
   - buka puttyGen
   - load File .pem
   - Save as .ppk
   ![alt text](image-1.png)

3. set up putty untuk Remote SSH
   - buka apps putty
   - isi IP public sesuai instance (AWS - Public IPv4 address) / pada menu EC2 instance
   - isi port untuk SSH sesuai Security Group di instance
   - isi nama session (NIM_server) agar saat connetct lagi tinggal load saja
   - load File .ppk (klik SSH -> Auth -> Credentials -> load File .ppk)
   - Kembali ke session klik save
   - klik Open
   - Masukan username sesuai instance
   ![alt text](image-11.png)
   ![alt text](image-12.png)
   ![alt text](image-13.png)

4. "sudo apt-get Update" (Update OS) lanjut "sudo apt-get Upgrade"
![alt text](image-14.png)

5. Pembuktian Remote SSH secara Visual
   - copy Public IP Address instance paste ke browser
   ![alt text](image-15.png)
   - install web server seperti Apache/Nginx 
   - sudo apt install apache2
   - Reload browser
   ![alt text](image-16.png)

6. matikan instance agar tidak kena tagihan
   - sudo shutdown now 
   ![alt text](image-17.png)
