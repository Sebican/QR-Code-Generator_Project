# QR-Code-Generator_Project
This project is for generating QR Code of Different Size by entering the Text. 

1.Google-chart-API-URL i used in this project :  https://chart.googleapis.com/chart?
2.Some required parameters that we need to add in the url, the first parameter is cht,cht=qr, It specifies a QR code and it is required parameter.
The next parameter is chs=width x height, It specifies Image's size, for example, chs=150x150, So the width & height will be 150 and it is also required parameter.
The next parameter is chl=data, It is their data to encode. The data can be digits, alphanumeric characters or binary bytes.
3.https://chart.googleapis.com/chart?cht=qr&chs=100x100&chl=hello  //text is hello
4.To remove White space around QR code Generator add the data inside the braces ( chf=bg,s,65482100& ) before cht of the chart URL.
5.DEPLOYED-ON-SERVER-HERE-IS-THE-URL: https://www.blogger.com/u/1/blog/themes/edit/422184325041

Thank You!
