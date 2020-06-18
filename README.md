<h2> Indian Folk Dance Form Classifer </h2>
<h5> CNN Model for classification of folk dances </h5>

<hr/>

<p> This project is in reference to the Hacker Earth Deep Learning Challenge <a href="https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-identify-dance-form/">Identify the dance form</a></p>

<p> 
    The classifier uses cnn to identify the image of a dance form. 
    <br/>
    Following are the class categories for identification:
</p>

<ul>
    <li>Manipuri</li>
    <li>Bharatanatyam</li>
    <li>Odissi</li>
    <li>Kathakali</li>
    <li>Kathak</li>
    <li>Sattriya</li>
    <li>Kuchipudi</li>
    <li>Mohiniyattam</li>
</ul>

<p> The dataset for the same is available at: <a href="https://he-s3.s3.amazonaws.com/media/hackathon/hackerearth-deep-learning-challenge-identify-dance-form/identify-the-dance-form-deea77f8/0664343c9a8f11ea.zip?Signature=VMTiYhb40BdZ7ImRUoQnDGUVXpQ%3D&Expires=1592315647&AWSAccessKeyId=AKIA6I2ISGOYH7WWS3G5">Data</a> </p>

<p> Make sure your python enviroment fullfils the following deps. If not, install the following using 'pip install ___dep___' </p>

<p> Python Dependencies:  </p>
<ul>
    <li>Open Cv</li>
    <li>Pandas</li>
    <li>Tensorflow</li>
    <li>Numpy</li>
</ul>

<p> After downloading the Dataset, place it in a folder named: data and run preprocess.py. When the preprocessing is finnished, you should have two new files with the name: features.py and labels.npy. Now run the model.py which will save the model to cnn.model dir. You are now ready to make predictions. To test an image, place it in the data/test/ folder and run predict.py..
Prediction results are saved in predictions.csv file
</p>