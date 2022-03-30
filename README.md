# Uninstall Old Kernel in Fedora

Jika kalian menggunakan fedora, pasti kalian sadar bahwa setiap kalian melakukan update kernel, kernel yang lama tidak akan dihapus. Melainkan tettap terinstall dan dapat dipilih di grub untuk menggunakannya saat boot. Namun apabila kalian terpikir untuk menguninstallnya, lakukan langkah berikut:
1. Buka terminal kalian.
2. Ketikkan
    ```
    uname -sr
    ```
    untuk mengetahui kernel apa yang sedang kalian gunakan saat ini.
3. Ketikkan 
    ```
    rpm -q kernel
    ```
    untuk mengetahui kernel-kernel yang terinstall di fedora kalian.
4. Ketikkan
    ```
    sudo dnf remove **x**
    ```
    dengan **x** adalah kernel yang ingin kalian uninstall. Untuk mendapatkan nama kernelnya, gunakan referensi dari langkah no 3 tadi.
5. Tunggu prosesnya dan selesai sudah.

## <b>About Me</b>

I'm a student at Del Institute of Technology. <br>
Bachelor of Informatics study program. <br>


<button><a href="https://www.instagram.com/gabrielhtg77/">My Instagram</a></button>
<br>
<button><a href="https://www.del.ac.id/">Institut Teknologi Del</a></button>