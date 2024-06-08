# 🤖 Klasifikasi dan Objek Deteksi

Proyek ini menunjukkan bagaimana cara klasifikasi menggunakan `scikit-learn` dan object recognition dengan `opencv`.

## Instalasi

1. Clone repositori ini:
   
    ```bash
    git clone https://github.com/izzalDev/car-computer-vision.git
    cd car-computer-vision
    ```

1. Instal Conda:

    Ikuti petunjuk pada halaman instalasi Conda untuk menginstal Conda di sistem Anda. Conda adalah manajer paket yang membantu Anda mengelola dependensi untuk proyek Anda.

2. Instal DVC:

    DVC (Data Version Control) adalah sistem kontrol versi untuk proyek sains data dan pembelajaran mesin. Instal DVC menggunakan Conda:
    ```bash
    conda install -c conda-forge dvc
    ```

3. Buat dan aktifkan lingkungan Conda:

    Buat lingkungan Conda baru berdasarkan file `environment.yml` yang disediakan dan aktifkan:
    ```bash
    conda env create -f environment.yml
    conda activate my_env
    ```

    Ini akan menginstal semua dependensi yang diperlukan untuk proyek.

4. Tarik data dan file model terbaru menggunakan DVC:

    DVC melacak data dan file model dan memungkinkan Anda untuk membuat versi dari mereka. Tarik data dan file model terbaru menggunakan DVC:
    ```bash
    dvc pull
    ```

    Ini akan memastikan bahwa Anda memiliki versi terbaru dari data dan file model yang diperlukan untuk proyek.

## Penggunaan

Setelah Anda menyelesaikan langkah-langkah instalasi, Anda dapat mulai menggunakan dan memodifikasi notebook yang sudah ada.
