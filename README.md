# code_for_paymentgateway_YIF

Please follow these steps to integrate the payment gateway
1.Create a folder Paytm at the same label of your app and put the checksum.py file in this folder.
2.Now import checksum from Paytm folder in the views.py file
    code: from Paytm import Checksum
3.add the code of checkout_part.py file into your checkout view at the end
4.import the csrf_exempt into the views.py file.
    code: from django.views.decorators.csrf import csrf_exempt
5.put the code of response_view.py file into your views.py file.
6.Now create paytm.html and response.html files into your templates dir.
7.define the MERCHANT_KEY="your merchant key" in starting of your views.py file.
