# JetsonNANOCustomDataset
Step by step manual to start using the Jetson nano for AI applications, basic steps to set up for the first time, training your model in your own computer with your custom dataset and deploying your model in Jetson Nano.
## All you need to start (Hardware)
* [Jetson Nano 4GB Developer Kit](https://www.amazon.com.mx/nVidia-Jetson-Nano-Desarrollador-B01/dp/B084DSDDLT/ref=sr_1_1?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=jetson+nano&qid=1618334404&sr=8-1)
*  [Micro SD minimum 64GB 100MB/s](https://www.amazon.com.mx/SAMSUNG-microSDXC-Tarjeta-Adaptador-MB-ME128HA/dp/B0887GP791/ref=sr_1_6?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=5LLIO2088IXV&dchild=1&keywords=mini%2Bsd%2Bcard%2B64%2Bgb&qid=1618334519&sprefix=mini%2Bsd%2Bcard%2Caps%2C202&sr=8-6&th=1)
*  [Cable Micro USB](https://www.amazon.com.mx/UGREEN-Trenzado-Cargador-Samsung-lectores/dp/B07VJMC4Z5/ref=sr_1_14?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=31EDU662858OT&dchild=1&keywords=cable+micro+usb&qid=1618334800&sprefix=cable+micro+%2Caps%2C212&sr=8-14)
*  [Keyboard and Mouse](https://www.amazon.com.mx/Logitech-MK220-Teclado-inal%C3%A1mbricos-espa%C3%B1ol/dp/B0080W1VVC/ref=sr_1_1?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=12PKP6HURCC2&dchild=1&keywords=keyboard+and+mouse&qid=1618335240&sprefix=keeyboard+a%2Caps%2C204&sr=8-1)
*  Monitor
*  [Webcam](https://www.amazon.com.mx/Logitech-C270-Webcam-720p-Negra/dp/B01BGBJ8Y0/ref=sr_1_22?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=webcam&qid=1618335412&sr=8-22)
*  [Case with fan](https://www.amazon.com.mx/Yahboom-Carcasa-acr%C3%ADlico-Ventilador-refrigeraci%C3%B3n/dp/B07TH8NBWF/ref=sr_1_2?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=case+jetson+nano&qid=1618335601&sr=8-2)
*  [HDMI](https://www.amazon.com.mx/Amazon-Basics-Trenzado-Velocidad-Oscuro/dp/B07S25XD8X/ref=sr_1_1_sspa?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=HDMI&qid=1618335800&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE1N0Q3TzlGVVdCVE0mZW5jcnlwdGVkSWQ9QTA0NDc3NzIyMkpDRk5BRkVBU0JMJmVuY3J5cHRlZEFkSWQ9QTAxMDk0MDAxTDg1OUtOWDc5Q0RKJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
*  [Ethernet](https://www.amazon.com.mx/UGREEN-Ethernet-Trenzado-10000Mbit-Compatible/dp/B086G7VHP3/ref=sr_1_6?__mk_es_MX=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=ethernet+cable&qid=1618336925&sr=8-6)
*  Computer

## Write Image to the microSD Card
