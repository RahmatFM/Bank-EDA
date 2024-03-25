# The Marketing Campaigns (Deposito Subscribed) - EDA

### Data source :
https://drive.google.com/file/d/1mvNj8sFFDC5FKMlMd6IHF85eRGfhyBtc/view?usp=sharing

### Explanation:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.

> - Number of Instances: 45211 for bank-full.csv.
> - Number of Attributes: 16 + output attribute.
  
### Goals :
1. What is the tendency of a person to subscribe to deposits based on age, balance, day, duration, campaign, pdays, and previous?
2. What is the proportion of deposit subscriptions on the data?
3. What groups have a deposit subscription tendency based on the categories of age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome?
4. What data has a strong correlation affecting someone subscribing to deposits?
   
## FEATURE DESCRIPTION :
> **bank client data:**
> - age (numeric)
> - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services")
> - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
> - education (categorical: "unknown","secondary","primary","tertiary")
> - default: has credit in default? (binary: "yes","no")
> - balance: average yearly balance, in euros (numeric)
> - housing: has housing loan? (binary: "yes","no")
> - loan: has personal loan? (binary: "yes","no")

>  **related with the last contact of the current campaign:**
> - contact: contact communication type (categorical: "unknown","telephone","cellular")
> - day: last contact day of the month (numeric)
> - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
> - duration: last contact duration, in seconds (numeric)
> **other attributes:**
> - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
> - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
> - previous: number of contacts performed before this campaign and for this client (numeric)
> - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

> **Output variable (desired target):**
> - y: client subscribed
