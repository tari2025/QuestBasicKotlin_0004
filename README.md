# QuestBasicKotlin_0004
latihan kotlin
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/85df6050-2db3-47d7-8581-b25ea3cb10d1" />
#String templates
Akan sangat berguna untuk mengetahui cara mencetak isi variabel ke output standar. 
<img width="345" height="282" alt="{0730DD03-5B8C-4FA2-A49C-D21FB13286C1}" src="https://github.com/user-attachments/assets/f51ccc56-2acd-4d4c-8ed6-1d42036bac3a" />
#Coding List Kotlin
List menyimpan item sesuai urutan penambahannya, dan memungkinkan adanya item
duplikat.
<img width="708" height="268" alt="{ABB9B21B-79CB-4303-A0D9-1CBFF4D93B0F}" src="https://github.com/user-attachments/assets/3d8f2b7c-4d94-4c36-9237-64e0127a11e6" />
Set
Sementara List diurutkan dan memungkinkan item duplikat, set tidak diurutkan dan hanya
menyimpan item unik.
<img width="744" height="248" alt="{9F472579-65E4-47E9-B6AA-EDEB0C2008C0}" src="https://github.com/user-attachments/assets/f33afa42-d106-405c-bffb-fc6810320299" />
Map
Maps menyimpan item data sebagai pasangan key-value. 

<img width="784" height="322" alt="{D5C9FEC1-4184-46C1-AA49-FE63CE8B4C65}" src="https://github.com/user-attachments/assets/bf484abd-15c9-4f24-a02c-1f214530d8c5" />
Untuk mengakses nilai pada map, gunakan operator akses yang diindeks [] dengan ‘key’nya:

<img width="734" height="308" alt="{69521865-6BE7-4098-BC21-0982159C3850}" src="https://github.com/user-attachments/assets/2be2edb7-cac0-4370-b12b-ee6e43bc2623" />

Conditional expressions
Kotlin menyediakan if dan when untuk memeriksa ekspresi bersyarat.
If
Untuk menggunakan if, tambahkan ekspresi kondisional di dalam tanda kurung () dan
tindakan yang akan dilakukan jika hasilnya benar di dalam tanda kurung kurawal {}:
<img width="305" height="282" alt="{EBAC3458-5E99-492B-A4AC-C1EA25BB2E57}" src="https://github.com/user-attachments/assets/97c20abf-f78a-42d9-ac33-3b8e7998061e" />
When
Gunakan when ketika Anda memiliki ekspresi bersyarat dengan beberapa cabang. when
dapat digunakan baik sebagai pernyataan maupun ekspresi
<img width="568" height="222" alt="{577EE742-A0E2-48A8-AEC9-A8C2C1868C92}" src="https://github.com/user-attachments/assets/daec2f53-ce67-48cd-ab8b-9293958299e4" />

contoh 
<img width="573" height="233" alt="{42881146-2B4B-42F3-A66C-9D4213E6EA7D}" src="https://github.com/user-attachments/assets/57755234-2bf2-4d43-b39e-fee6b8e34b20" />

Ranges
Sebelum membahas tentang perulangan, ada baiknya kita mengetahui cara membuat
rentang untuk perulangan.
<img width="311" height="265" alt="{4F2FB001-6670-438C-8CB0-0F006441FCAD}" src="https://github.com/user-attachments/assets/b8ef4dbe-9515-479e-bd7c-2b401b2c39e6" />

Loops
Dua struktur perulangan yang paling umum dalam pemrograman adalah for dan while.
Gunakan for untuk mengulang serangkaian nilai dan melakukan suatu tindakan. Gunakan
while untuk melanjutkan tindakan hingga kondisi tertentu terpenuhi.
contoh for
<img width="277" height="245" alt="{B16EBE60-DE66-46D3-AA46-1229F5AFEA5B}" src="https://github.com/user-attachments/assets/bfb75adb-fff9-453b-83bc-849c34c3b678" />

contoh while
<img width="222" height="241" alt="{5A3FCFC2-0141-43BF-80CC-9337083337E6}" src="https://github.com/user-attachments/assets/91752efc-1c49-4e77-bbb5-4db76bc91d2f" />

contoh fucntion 
Jika sebuah fungsi tidak mengembalikan sesuatu yang berguna, tipe return dan kata kunci
return dapat dihilangkan. Pelajari lebih lanjut tentang hal ini di Fungsi tanpa
pengembalian

Named arguments
Untuk kode yang ringkas, ketika memanggil fungsi, Anda tidak perlu menyertakan nama
parameter. Namun, menyertakan nama parameter akan membuat kode Anda lebih
mudah dibaca. Ini disebut menggunakan argumen bernama. Jika Anda menyertakan
nama parameter, maka Anda dapat menulis parameter dalam urutan apa pun.
<img width="302" height="294" alt="{792927A4-C487-4C34-A54B-88C8FF3BFEFA}" src="https://github.com/user-attachments/assets/99e959f9-258f-4b04-bd14-1847210608a8" />

<img width="366" height="302" alt="{83FD5A24-685F-48F8-9BF3-26378861E6C6}" src="https://github.com/user-attachments/assets/ff2c109c-f747-4ed8-96bd-8f7a67e736e2" />

Default parameter values
Anda dapat menentukan nilai default untuk parameter fungsi Anda. Parameter apa pun
dengan nilai default dapat dihilangkan saat memanggil fungsi Anda. Untuk
mendeklarasikan nilai default, gunakan operator penugasan = setelah tipe:
<img width="460" height="280" alt="{C2C15E17-F1BA-4AA8-83E7-10F50259F9C5}" src="https://github.com/user-attachments/assets/313ae5b6-4986-4c81-911b-755d70c64f20" />

Functions without return
Jika fungsi Anda tidak mengembalikan nilai yang berguna, maka tipe kembaliannya
adalah Unit. Unit adalah tipe dengan hanya satu nilai - Unit. Anda tidak perlu
mendeklarasikan bahwa Unit dikembalikan secara eksplisit dalam badan fungsi Anda. Ini
berarti Anda tidak perlu menggunakan kata kunci return atau mendeklarasikan tipe
pengembalian:

<img width="308" height="289" alt="{08F06792-C21B-42EE-AAA8-E75BFA58D98A}" src="https://github.com/user-attachments/assets/00017248-0de0-4158-92d3-d0c50c35bf50" />

Lambda expressions
Kotlin memungkinkan Anda untuk menulis kode yang lebih ringkas untuk fungsi-fungsi
dengan menggunakan ekspresi lambda.
Sebagai contoh, fungsi uppercaseString() berikut ini:
<img width="420" height="152" alt="{28588996-A13D-40BF-ADC2-57635F14E16F}" src="https://github.com/user-attachments/assets/d1c625b2-0fa3-4b11-9c8d-2ac543b649dd" />

Class
Kotlin mendukung pemrograman berorientasi objek dengan kelas dan objek. Objek
berguna untuk menyimpan data dalam program Anda. Kelas memungkinkan Anda untuk
mendeklarasikan sekumpulan karakteristik untuk sebuah objek. Ketika Anda membuat
objek dari sebuah kelas, Anda dapat menghemat waktu dan tenaga karena Anda tidak
perlu mendeklarasikan karakteristik ini setiap saat.
<img width="295" height="264" alt="{F8BFC166-44D9-4D99-89E7-DA522824BD9B}" src="https://github.com/user-attachments/assets/e509d8f6-f349-4919-b245-3dae7a165764" />

properties
<img width="395" height="256" alt="{16EF869E-5C2F-4D2A-94EF-4FC456182136}" src="https://github.com/user-attachments/assets/efd4e624-fe5c-4039-80f2-2a9346dee0c7" />

Create instance
<img width="439" height="279" alt="{DB7063ED-A8B1-4D55-9A12-EF7D2E354D3B}" src="https://github.com/user-attachments/assets/ab7001c4-56db-461e-8e37-38fd5cba73d5" />

Access properties
Untuk mengakses properti dari sebuah instance, tulis nama properti setelah nama
instance yang ditambahkan dengan titik . :
<img width="420" height="278" alt="{13A28E6B-84FD-4236-9B71-43DBA0672EB8}" src="https://github.com/user-attachments/assets/d2bca6f6-746e-4854-9d77-3cf44079d504" />















