# Lendal Case Study
> Project by Beng Cheong and Géraldine Bengsch (First Upgrad case study) <br>
>
> This project uses EDA to identify common types of risks found in consumer finance companies lending loans:
> - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
> - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
>
> The project contains:
> - Data Analysis notebook
> - Presentation to client in PDF format
> - A folder containing images used (Visualisations are our own, picture is from Unsplash)
> - The data set `loan.csv`
> - The data dictionary `Data_Dictionary.xlsx`


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## General Information
![Photo by <a href="https://unsplash.com/@jpvalery?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jp Valery</a> on <a href="https://unsplash.com/s/photos/money?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  ](img/jp-valery-blOLCO2K4M0-unsplash.jpg)

> ## The Lending Club
>"Lending Club" is a US based peer-to-peer (P2P) company that connects investors with borrowers, providing both personal and business loans. It is accessible to most borrowers, but provides better terms to borrowers with high incomes and great credit scores. After applying, investors review the loan and decide on investing in it or not.

- **General information:** 
A loan describes money that is being lend to an individual or an organisation. The loan recipient receives the money with the implication that the money will be paid back over time. When lend through a financial institution, the recipient usually will be liable to pay interest on the amount of money received. Here, the bank provides the loan which is sold to the Lending Club. The Lending Club helps its members to pay debt. It explicitly invites invitations for members to consolidate loans. Interested parties apply to the company and choose their preferred loan option, e.g. rate, term and payment options. The loan is funded by investors with the Lending Club in charge of the money. 
Find out more about the company at: https://www.lendingclub.com/

- **Background:** There are many reasons why a person may need to lend money. A common reason is the consolidation of debt, that is, combining debt from various creditors into a single amount. Other common reasons include large purchases, such as a car or property purchase, or starting a business.

- **Business problem:**
Banks can earn money through lending money out to their customers and the compensation of a certain interest rate. However, this assumes that the debtors will indeed repay their loan in full. A borrower may find themselves unable to make payments, meaning that the loan will default. As a result, the bank looses not only the principal amount, but also the interest on the money. Banks need to make a decision on who they lend money to. This usually occurs based on data from previous loan recipients.

- **Dataset:** The dataset consists of 111 columns and 39717 entries. Not all columns contain data, with a total number of 2263364 missing entries. Based on our exploration, the Lending Club data is similar to other data that may be obtained through other financial companies. The data set was provided to us through *UpGrad*. However, it is also available publicly.



## Conclusions
Please see the notebook and Presentation slides for more detailed insights.
1. Purpose of the loan  does not matter. 
2. Borrowers were **more likely to default on their loans if interest rates at time of borrowing were high**. 
3. Borrowers are **more likely to default when term was 60 months and they were below Grade B**. 
4. The amount of funds provided by investors is an import factor, as those whose who were **able to pay off fully had help from investors**.
5. **Annual income is not an indicator** of whether the loan will be paid.



## Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-informational?style=flat&logoColor=white&color=2bbc8a)
![NumPy](https://img.shields.io/badge/NumPy-1.21.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Pandas](https://img.shields.io/badge/Pandas-1.3.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1-informational?style=flat&logoColor=white&color=2bbc8a)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-informational?style=flat&logoColor=white&color=2bbc8a)
![Plotly](https://img.shields.io/badge/Plotly-5.5.0-informational?style=flat&logoColor=white&color=2bbc8a)
![Kaleido](https://img.shields.io/badge/Kaleido-0.2.1.post1-informational?style=flat&logoColor=white&color=2bbc8a)



## Contact
Created by [@GeriNZ](https://github.com/GeriNZ) and [@bengcheo](https://github.com/bengcheo) - feel free to contact us! <br>
Students at UpGrad: *Master of Science in ML and AI* <br>
© 2021


