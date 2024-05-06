This work utilizes several open source repos on YOLO based detection and tracking (using DeepSORT), in a crude and lazy manner, to serve as reference. Furthermore, it exposes a fundamental problem with detection and tracking. Detection is significantly better than tracking, and occlusion very easily seeps over time within a video.

Following are the models used in the repos: [Models](https://drive.google.com/drive/folders/1Rrg-GCYywYIAj_iATbJ0mRsgIyzQbOoU?usp=drive_link)

Following are the resultant video output comparison.

| No. | Video Results|Snapshot|
| --- | --- | ---|
| 1 | [Reference Video](https://drive.google.com/file/d/1yzGkAY5VL9DgqHQvqoD82B7uk5iH4iOC/view?usp=drive_link) |![Screenshot from 2024-05-06 23-04-04](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/7ee95078-72f9-4911-9fbf-9cc4d29f9f3c)|
| 2 | [Video Output: occlusion 1_1](https://drive.google.com/file/d/1Ug5vJEnenUpNxhOXQBZnxf9L8zsTkBMg/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/ae9c7aab-598a-44ff-8837-35bb0d869793) |
| 3 | [Video Output: occlusion 1_2](https://drive.google.com/file/d/1n_Vb1XphDr3c8DBkBLwKsrWKduSc-hSR/view?usp=sharing) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/b1db6114-97c5-4914-b2e9-48a58a22baf6) |
| 4 | [Video Output: occlusion 1_3](https://drive.google.com/file/d/11ROifav5bUISmU1H5OsK7fWbDvfXbVhN/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/66fc6dc2-24ed-4e99-8773-e5e20b8d6219)|
| 5 | [Videeo Output: occlusion 1_4](https://drive.google.com/file/d/1fBUL3GjM7aPVO3XKI2jbKTpwt-Gf6UtC/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/91c07fdf-7170-49e0-a2e4-40af2bb99011)|
| 6 | [Video Output: occlusion 2](https://drive.google.com/file/d/1P4I3aE2vBDAKO1iQypY3Miv-7_sC0kaV/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/f5d8c06c-a3db-4063-abf6-0b34c10f89ce)|
| 7 | [Video Output: occlusion 3_1](https://drive.google.com/file/d/1Dm1cTvrXQYaFtk1azrPTsyqgnrlTvYac/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/358af799-6aae-413e-85a9-89ae2c9d3fbf) |
| 8 | [Video Output: occlusion 3_2](https://drive.google.com/file/d/1VnHE1Y8k-7IC4rGxlgC5kFnZjHU2ra0x/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/98eee825-4267-4102-8ab0-5652135ba337) |
| 9 | [Video Output: occlusion 4](https://drive.google.com/file/d/1RcC21eA3FeLQhFqOIXvemH7ovCNMWZe7/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/951c57fc-ecd8-4ee1-ace9-b63a5fb621ee) |
| 10 | [Video Output: occlusion 5](https://drive.google.com/file/d/1zMJoeKUpaMdYfY7W-3g4DxazpYSIzj_h/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/fa97e5ce-66e9-436f-9eee-7b231e4496ce)|
| 11 | [Video Output: occlusion 6](https://drive.google.com/file/d/1o9IFlLkDAicNgqeT9kV_WlAc1FH-k3Vi/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/02f18404-d6bf-41c9-976e-7bca1a7ea8e4)|
| 12 | [Video Output: occlusion 7](https://drive.google.com/file/d/1gfqsDs4gSgNPWhYa-j9wOgPmQYYkBqZF/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/0605d015-d9e1-4f1c-a2e1-9dd56023e359) |
| 13| [Video Output: occlusion 8_1](https://drive.google.com/file/d/1hjh8ltkx3Egg83SGUN5JnCzmta2u8_c8/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/4d2f0249-28b5-41bd-a52c-6507412fbfd3)|
| 14| [Video Output: occlusion 8_2](https://drive.google.com/file/d/1_xbGXlVg9vqLKkqF7gRWSNOUAsUSIrih/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/e74590af-b434-4cc6-a8a4-bcccbd2e9bd4)|
| 15 | [Video Output: occlusion 9](https://drive.google.com/file/d/1WbbhJUEWV40VMWnH7zKjXpzdHBzG5T0x/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/659a8535-3b02-458f-9f61-f37533e5f8a6)|
| 16 | [Video Output: occlusion 10](https://drive.google.com/file/d/1ryT92frW-jCgkbNFDcAATd8jeGEiubzS/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/43c3886d-8ad0-4237-8530-023a6fa9a86d)|
| 17 | [Video Output: occlusion 11](https://drive.google.com/file/d/1X7nF1e1Fsq2t2hGHPQgQRqFRl4JLvqty/view?usp=drive_link) | ![image](https://github.com/superdianuj/yolo_detection_tracking/assets/47445756/001ada67-38ba-4c00-b388-de7dd987704e)|

