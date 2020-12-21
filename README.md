# FASTBIZ

FASTBIZ – DEEP LEARNING SOLUTION

About:
The FASTBIZ finance model will be based on 6 basic competitive strategies namely

1. FASTBIZ Network Vision - where the management team will incorporate the policies and guidelines as/if enabled by the Government of India to promote facilitated cashless services

2. A Differentiation Strategy – where the company will rely on its management model to ensure competitive positioning in the market

3. A Facilitated Business Actualization Strategy – where the company will enter into FAST TRACK partnerships and FASTBIZ alliances to help fulfill customer requirements for solutions, products and services. The company will also depend upon FASTBIZ investors to facilitate business actualization.

4. A Facilitated Business Services Strategy – that is based on the company’s Facilitators Desk model, where the company will do its best to help customers use FASTBIZ Coupons for purchases.

5. A Growth Strategy – that will be based on a Partner Network model, where the focus will be on two categories of partners i.e. Fast Track Partners and FASTBIZ Service Partners (alliances).

(a) Fast Track Partners will be entities like FASTBIZ exchanges, sellers and associated businesses that help trade, buy or sell, send or receive FASTBIZ Coupons. 

(b) FASTBIZ Service Partners (alliances) will be entities like organizations, institutes or business alliances that help the company provide (l) solutions, products and services for (1) FASTBIZ investors & customers and (2) the triple-bottom-line-need to fulfill certain corporate social responsibilities

6. A Cost Leadership Strategy – that will be based on the management culture of the company to help set a successful track record for its vision, mission and operational excellence.
 
Scope: 
The FASTBIZ coupon system will need to use data science and deep learning
to predict the next day value of EUR/USD or USD/INR or EUR/INR currency pair, 
so as to ensure the Business Actualization Strategy can sustain dynamics of the market.

Deploying the solution:
1.	Register the FASTBIZ-EXCHANGE application on FusionFabric.cloud Developer Portal, and include the Exchange Rates and Currency Conversion API.
Client ID: 3f0cd314-de61-44a6-9df4-d0e04bd7265f 
Secret key: b535cfb7-c2f3-42f4-a623-2e9f7292d014

2.	Open the FASTBIZ-EXCHANGE project in the file explorer.

3.	Copy an available config.csv.sample to config.csv, open it, and enter <3f0cd314-de61-44a6-9df4-d0e04bd7265f>, and <b535cfb7-c2f3-42f4-a623-2e9f7292d014> of the application created at the step 1.

4. Enter the execution mode, in case of a simple demonstration open the command prompt
window, type python Forex-Data-Science.py

The following errors are being reported for your sample application as on 21/12/2020 7:21 AM IST

C:\2020\FASTBIZ\FASTBIZ-main>python Forex-Data-Science.py
c0a9d668-0a66-4191-93e9-3f0f3ded6220
b535cfb7-c2f3-42f4-a623-2e9f7292d014
c0a9d668-0a66-4191-93e9-3f0f3ded6220
b535cfb7-c2f3-42f4-a623-2e9f7292d014
{'error': 'unauthorized_client', 'error_description': 'INVALID_CREDENTIALS: Inva
lid client credentials'}
Dates Sample:  ['2020-12-21', '2020-12-20', '2020-12-19', '2020-12-18', '2020-12
-17', '2020-12-16', '2020-12-15', '2020-12-14', '2020-12-13', '2020-12-12']
Retrieving data from the API server. Please be patient, there are 20 years of da
ta!
c0a9d668-0a66-4191-93e9-3f0f3ded6220
b535cfb7-c2f3-42f4-a623-2e9f7292d014
{'error': 'unauthorized_client', 'error_description': 'INVALID_CREDENTIALS: Inva
lid client credentials'}
Traceback (most recent call last):
  File "Forex-Data-Science.py", line 137, in <module>
    usd = dta["rates"]["USD"]
KeyError: 'rates'
  
