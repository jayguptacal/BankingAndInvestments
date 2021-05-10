# Can We Identify Credit Card Fraudulent Transactions with Machine Learning?

<p align="center"><img src="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/images/CreditCardsFraudsBannerwelcome.jpg"></img></p>

## Introduction
As per the <a href="https://www.prnewswire.com/news-releases/payment-card-fraud-losses-reach-27-85-billion-300963232.html" target="_blank">the Nilson Report</a>, fraudulent card losses worldwide in 2018 reached to $27.85  billions.  

Fraud losses are incurred by payment card issuers, merchants, acquirers of card transactions from merchants, and acquirers of card transactions at ATMs on all credit, debit, and prepaid general purpose and private label payment cards issued around the globe. 
Here is a picture from the same Nilson Report showing the magnitude of this problem for the financial industry:

<p align="center"><img src="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/images/CardFrauds_Nilson_Report.jpg"></img></p>

The payment frauds are of different types and some of the popular ones are identified here:

 - **Card Not Present Fraud:** - the scammer attempts to make a fraudulent credit card transaction online or over the phone, whilst not physically possessing the card.
 - **Skimming:** - it refers to the copying of card magnetic-stripe track data at Point of Sales terminals and ATMs.
 - **Jackpoting** - certain older ATMs may be vulnerable to ‘jackpotting’, where the criminal either uses malware or a ‘black box’ hardware device to connect to the ATM dispenser and empty it of cash.
 - **Business email Compromise** - this involves the impersonation of company staff, typically members of senior management who can authorise transfers, deceiving employees into transferring funds to the criminal’s account.
 
You can read more about the above <a href="https://www.lexology.com/library/detail.aspx?g=6b1c754a-2dfc-403b-91c6-85c9d8a79456" target="_blank">different types of fradulent activities here</a>. 

## Goals for the Project

- **Identify fraudulent credit card transactions** with various machine learning algorithms.
- Given the proportion of the fraudulent vs. non-fradulent dataset, use the **upsampling, downsampling, and synthetic minority oversampling techinique (SMOTE)** for better machine learning models
- Build different **machine learning models** and identify the most suited one for this problem based on the best results

Due to class imbalance ratio, I plan to focus on **measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC)** as confusion matrix accuracy is not meaningful for unbalanced classification.

<p align="center">
<img src="https://github.com/jayguptacal/BankingAndInvestments/blob/main/FinancialFraudDetection/images/financialfraudspresentationcover.png">
</p>

## Check-Out Jupyter Notebooks For Different Steps of Machine Learning Modeling ##

While clicking on the below links for the detailed working of this project, please ensure that you open in a new window by right-clicking and then opening it so that this summary notebook remains open. The data sometimes may not load properly in the new window, so please reload it until it shows properly.

<img src="https://github.com/jayguptacal/portfolio/blob/main/image/bannerOpenNotebooks.jpg">

* <a href="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/1_Problem_Identification_CreditCard_Frauds.ipynb" target="_blank"><b>Problem Identification Notebook</b></a>

* <a href="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/2_Data_Wrangling_CreditCard_Frauds.ipynb" target="_blank"><b>Data Wrangling Notebook</b></a>

* <a href="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/3_EDA_CreditCard_Frauds.ipynb" target="_blank"><b>Exploratory Data Analysis Notebook</b></a>

* <a href="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/4_Preprocessing_CreditCard_Frauds.ipynb" target="_blank"><b>Pre-Processing and Training Data Development Notebook</b></a>

* <a href="https://github.com/jayguptacal/BankingAndInvestments/blob/main/CreditCardFraudDetection/5_MachineLearning_CreditCard_Frauds.ipynb" target="_blank"><b>Machine Learning Modeling Notebook</b></a>

* <a href="" target="_blank"><b>Documentation Notebook</b></a>

## Check-Out Jay Gupta's Portfolio for Other Machine Learning Projects ##
<p align="center">
<a href="https://jayguptacal.github.io/portfolio/" target="_blank"><img src="https://github.com/jayguptacal/portfolio/blob/main/image/FullPortfolioBanner.jpg"></a>
</p>

