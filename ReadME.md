Instructions to run the executable in MacOS
Open Terminal, go the path where the executable is present.
Run the following command
./GUI_FinalProject

In WINDOWS, the .exe file will execute via a double click

The directory where the executables are located contains files which are necessary for the successful execution of the application. Please don't delete any of the files.

Dataset description
1.	For training an image captioning model, we have used the Flickr 8K dataset which includes two parts images and text. Image contains a total of 8092 images in JPEG format, all are different shapes and sizes. Out of 8092 training dataset is 6000,test is 1000 and 1000 for development. Second part of the dataset is text files containing descriptions containing 5 captions for each image. Total size of the caption is 40460.
2.	For further Image classification model we have created our own labeled data using the Youtube API which includes youtube video description and respective category of the video.The total size of this data is ~20k rows the data categorized into 9 categories namely adventure, art and music, food, history, manufacturing, nature, science and technology, sports, travel.


Analysis
The project of converting images to finally generating the captions is divided into three phases:
1.	Generating of Description using the Images
2.	Generating categories and captions using the Image description which would be used to recommend engaging social media captions.
3.	Building a UI to present results

