# Lendal Case Study
> Project by Beng Cheong and Geraldine Bengsch (First Upgrad case study)
> This project uses EDA to identify common types of risks found in consumer finance companies lending loans:
> - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
> - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
![burning money](img/jp-valery-blOLCO2K4M0-unsplash.jpg)

- **General information:** A loan describes money that is being lend to an individual or an organisation. The loan recipient receives the money with the implication that the money will be paid back over time. When lend through a financial institution, the recipient usually will be liable to pay interest on the amount of money received. Here, the bank provides the loan which is sold to the Lending Club. The Lending Club helps its members to pay debt. It explicitly invites invitations for members to consolidate loans. Interested parties apply to the company and choose their preferred loan option, e.g. rate, term and payment options. The loan is funded by investors with the Lending Club in charge of the money. 
Find out more about the company at: https://www.lendingclub.com/

- **Background:** There are many reasons why a person may need to lend money. A common reason is the consolidation of debt, that is, combining debt from various creditors into a single amount. Other common reasons include large purchases, such as a car or property purchase, or starting a business.

- **Business problem:**
Banks can earn money through lending money out to their customers and the compensation of a certain interest rate. However, this assumes that the debtors will indeed repay their loan in full. A borrower may find themselves unable to make payments, meaning that the loan will default. As a result, the bank looses not only the principal amount, but also the interest on the money. Banks need to make a decision on who they lend money to. This usually occurs based on data from previous loan recipients.

- **Dataset:** The dataset consists of 111 columns and 39717 entries. Not all columns contain data, with a total number of 2263364 missing entries. Based on our exploration, the Lending Club data is similar to other data that may be obtained through other financial companies.



## Conclusions
Please see the notebook for more detailed insights.
1. Purpose of the loan  does not matter. 
2. Borrowers were **more likely to default on their loans if interest rates at time of borrowing were high**. 
3. Borrowers are **more likely to default when term was 60 months and they were below Grade B**. 
4. The amount of funds provided by investors is an import factor, as those whose who were **able to pay off fully had help from investors**
5. **Annual income is not an indicator** of whether the loan will be paid.



## Technologies Used
- python - version 3.10
- numpy - version 1.21.5
- pandas - version 1.3.5
- matplotlib - version 3.5.1
- seaborn - version 0.11.2


## Contact
Created by [@GeriNZ] and [@bengcheo] - feel free to contact us!


