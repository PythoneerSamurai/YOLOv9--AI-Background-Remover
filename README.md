
# YOLOv9 -- AI-Background-Remover

This repository houses an AI background remover that utilizes the YOLOv9 semantic segmentation model as it's backbone. Alongwith the model, separate code has been written to make the background remover work efficiently. This is a GUI based application, you just have to execute the main.py file, and the GUI will show up. Other than removing backgrounds from images or videos, you can also change the background with any custom image that you have.

## Disclaimer

This AI model has been trained on freely available datasets. I have spent a lot of time to find the best quality data that is freely available in order to train the model. However, even the best quality freely available datasets do not have pixel-perfect annotations. Therefore, the model may not compete with the famous background removers available on the internet.


## Installation

You can either clone my repository by running the following command in your terminal (remember to open the terminal in the folder you want this project in)

```bash
 git clone https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover.git
```
![Screenshot from 2024-06-13 11-09-05](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/e5834ac3-f52b-42ec-b707-fa533352658e)

Otherwise, you can just download this project in the form of a ZIP file, by clicking the 'green code button' and then clicking the 'download ZIP' button.

![Screenshot from 2024-06-13 11-11-24](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/2e6629ba-6767-41c7-822d-79ee3280a846)

## Usage

The usage of the model is fairly simple, you need to have python installed. In addition to that you need to install three python libraries called 'ultralytics', 'opencv-python', and 'customtkinter'. You can install them by running the following command in your terminal

```javascript
pip install ultralytics opencv-python customtkinter
```

Afterwards, just open the 'main.py' file in an IDE or text editor of your choice, and execute the file. This will open up a user-friendly GUI, using which you can perform the function you want.

![gui](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/73a4d5f3-2d8b-4371-9be5-613179d81364)

Note that there is a slider in the GUI, using which you can adjust the confidence score of the AI model. Sometimes you may not achieve a desired background removal, in such a case adjusting the slider can result in a desirable output. Therefore, do play around with the confidence score if necessary.

## Results
Real Image
![real_one](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/2a0095b2-e9cc-4324-a91e-3f5c0c7217e4)

Background Removed
![mask_one](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/207ecf59-a30c-4cd9-889d-6a187bab68b8)

Background Changed
![image_one](https://github.com/PythoneerSamurai/YOLOv9--AI-Background-Remover/assets/112153865/f1850311-cf0a-4ca8-afd4-3e4fd01d88b9)


## License

No License.
