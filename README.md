<h1>Spam Classification</h1>
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according being ham (legitimate) or spam.<br>
 
In this project we build a model for classifying the SMS into spam or ham through the text of the SMS using standard classifiers.
<b>Prerequisites:-</b><br>
<b>
Python<br>
scikit-learn / sklearn<br>
Pandas<br>
NumPy<br>
matplotlib<br></b>
An environment to work in - something like Jupyter or Spyder
For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.<br>

<b>Dataset:</b><br>
The dataset is in the form of a CSV file:<br>
https://drive.google.com/file/d/18TGGVR4TqYLY2_sI4sRWMz4ncOidr0Ju/view?usp=sharing/<br>
The files contain one message per line. Each line is composed by two columns: “Class” contains the label (ham or spam) and “SMS” contains the raw text.



