# e-commerce-classifier
This consists of the notebook that predicts the category of the items of the e-commerce shopping list as given in the dataset to one of the 27 categories. You could find the dataset at https://www.kaggle.com/c/uw-cs480-fall20. This was a part of the Kaggle in-class competition. 

It includes a text classification technique using RNN with LSTM unit, image classification technique using ResNet and an ensemble learning technique.

A predictive app is to be deployed sonn based on this project.

<!--[if IE]><meta http-equiv="X-UA-Compatible" content="IE=5,IE=9" ><![endif]-->
<!DOCTYPE html>
<html>
<head>
<title>rnn.html</title>
<meta charset="utf-8"/>
</head>
<body>
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; modified=\&quot;2021-04-13T04:22:09.368Z\&quot; agent=\&quot;5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36\&quot; etag=\&quot;r2XnfCy-oMfFTbKNjQVI\&quot; version=\&quot;14.5.10\&quot; type=\&quot;device\&quot;&gt;&lt;diagram id=\&quot;YeY_X3pGseeH2n7vuqo6\&quot; name=\&quot;Page-1\&quot;&gt;7Vrfd5owFP5rfOwOEER9tNa1O2dbu9lz2j5GiZANCAtBcH/9goQfgUJxtkVPfWm5X27MTe733WDiAMzc+JpC3/5GTOQMNMWMB+BqoGkqUAD/lyDbFBmNtRSwKDaFUwEs8F8kQEWgITZRIDkyQhyGfRlcEc9DKyZhkFISyW5r4sij+tBCNWCxgk4dfcAms1N0PFQK/AZhy85GVhXR4sLMWQCBDU0SlSAwH4AZJYSlT248Q06yeNm6pP0+N7TmgVHksS4dPBjd390DFj9snq6VH7d4vp5fGCI2ts0mjEw+f2ESymxiEQ868wK9LNCvhPjcTeXgL8TYVqQPhoxwyGauI1p5iHT7yA3l0zAznxIzM65iydoKa008NiMOobvYgG7ok+EVxwNGyW9UahmNx9MpSHpgxynhl9psMr3k+CqkG2SKcNJJJzNtXEsBBSSkK9SygBknIbUQa/HT84xzqSDiIj5N3o8iBzK8keOAgrNW7leklT+IzO6RZfG5G+iEYqSBZjgsyVHyZLHdmqRIsuQSI4w/IckaLoJdhqfcQR37cdGYSAuu5A732OXK1ZTvKOJ/fxIXeuUO8rDLDPji+SHLUD7bZdWTY2mMNbg8mQqrIxsztPDTECNeqmR+NrGmhWcNzBQrjShDcTu56mQQHbSshIiSqQszKuqPmhUVu1R7DOWN6DN8hj7vUTWOX/3gFNQPGtXft9ZvsGkiby+xn7CudePIdD0+67pNrx10Pep1V1fO+Tswf5M+86cfbV2eEXeJPZ6YD1KZAZArswr6Ls2qdtZ2W83toG21IefvI+5Ro7hrShJq31e7+5eHdFiskZe/Si0bdc3njv0gYddLCn81Jr2CwqvfqXK7P4UbZ4W37cpdFD7sU+GTvRX+34K1P55gq1+WjkCwz72vnQVbbLVdFAv6VKzafA7a96a8IGvmwvgQnZ+SuqvbMej/hbv5lKxvbtyGTD4S/1DU0Hs/JlNHp1bn8+u2/O5td9lW3L01XLe92f4w7Lg/HLo9iK53BO8UKihlVN4lVLVClTQu0atgy5RSuC25+YlD0H0cfVS5kX3BX3bnD2kABXPzJTmAzM9d5rzGW2rtLP+g06Fjqki1c/s3rEjcLH4RkOa8+F0FmP8D&lt;/diagram&gt;&lt;/mxfile&gt;&quot;,&quot;toolbar&quot;:&quot;pages zoom layers lightbox&quot;,&quot;page&quot;:0}"></div>
<script type="text/javascript" src="https://app.diagrams.net/js/viewer-static.min.js"></script>
</body>
</html>
