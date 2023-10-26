# Mobile5

# link youtube(menyusul pak)

# a. Explicit Intent:
Explicit Intent adalah jenis intent dalam pengembangan Android yang secara jelas menentukan komponen tujuan yang akan dipanggil. Dalam Explicit Intent, pengembang secara eksplisit menyebutkan nama komponen tujuan yang ingin dipanggil, seperti aktivitas, layanan, atau penerima siaran. Intent ini digunakan untuk memulai komponen dalam aplikasi yang sama atau dalam aplikasi yang berbeda dengan menyebutkan nama paket dan kelas komponen yang dituju.

Manfaat dari Explicit Intent adalah:

- Memungkinkan pengembang secara langsung mengarahkan aplikasi ke komponen yang spesifik.
- Memungkinkan komunikasi antara komponen yang berbeda dalam aplikasi yang sama atau antara aplikasi yang berbeda.
- Dapat mengirim data tambahan melalui intent, seperti parameter atau argumen, yang akan diterima oleh komponen tujuan.

# b. Implicit Intent:
Implicit Intent adalah jenis intent dalam pengembangan Android yang tidak secara eksplisit menyebutkan komponen tujuan yang akan dipanggil. Sebaliknya, Intent ini menyatakan tindakan yang ingin dilakukan dan memungkinkan sistem Android mencari komponen yang sesuai untuk menangani tindakan tersebut. Misalnya, membuka halaman web, memutar audio, mengirim email, dll.

Manfaat dari Implicit Intent adalah:

- Memungkinkan pengembang untuk meminta sistem Android untuk menemukan komponen yang sesuai untuk menangani tindakan yang diinginkan.
- Meningkatkan fleksibilitas dan interoperabilitas karena komponen dari aplikasi lain dapat menangani tindakan yang sama.
- Dapat digunakan untuk meminta aksi dari aplikasi pihak ketiga yang diinstal di perangkat.

Dalam kedua jenis Intent ini, Explicit Intent dan Implicit Intent, pengembang dapat mengirim data tambahan melalui intent, seperti string, bilangan bulat, objek Parcelable, dll., yang dapat diterima oleh komponen tujuan untuk melakukan tindakan atau operasi yang relevan.
