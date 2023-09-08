# :bulb: Preprocessing Citra Satelit

Repository ini berisi langkah-langkah preprocessing citra satelit, citra satelit yang digunakan disini adalah Landsat 8. Preprocessing yang dilakukan meliputi:
* Composite Bands
* Radiometric Calibration
* Clip Bands
* Cloud Removal

## :package: Prasyarat

Sebelum memulai, pastikan telah terinstall beberapa tools:
* Text editor
* Web browser
* Python
* Jupyter Lab

## :cd: Menginstall Aplikasi

Untuk menginstall aplikasi ini, ikuti langkah berikut:

```bash
# clone this repository
git clone https://github.com/kunkoder/satellite-image-preprocessing.git

# change working directory
cd satellite-image-preprocessing
```

## :open_file_folder: Struktur Projek

```text
├── dataset
│   ├── climate
│   ├── landsat
│   ├── shape
│   └── srtm
├── output
│   ├── climate
│   ├── landsat
│   └── srtm
└── preprocessing.ipynb
```

## :eyes: Preview

**Band Komposit**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/satellite-image-preprocessing/main/images/composite-bands.png)

**Kalibrasi Radiometrik**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/satellite-image-preprocessing/main/images/thermal-calibration.png)

**Pemotongan Citra**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/satellite-image-preprocessing/main/images/clip-bands.png)

**Penghapusan Awan**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/satellite-image-preprocessing/main/images/cloud-removal.png)

## :balance_scale: Lisensi

[MIT License](https://github.com/kunkoder/espeka/blob/main/LICENSE)
