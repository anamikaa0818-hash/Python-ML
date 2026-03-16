Problem Summary Context:

Term deposits are a critical revenue stream for banks, involving cash investments held for a predetermined period at an agreed-upon interest rate. To promote term deposits, banks utilize various marketing strategies, including email marketing, advertisements, telephonic marketing, and digital marketing. Despite the rise of digital channels, telephonic marketing remains highly effective for engaging customers, although it requires significant investment in call centers.

Challenge:

Given the high cost of telephonic marketing campaigns, it is crucial for banks to pre-identify potential customers who are likely to subscribe to a term deposit. This targeted approach can enhance the efficiency of outreach efforts, ensuring that resources are allocated to clients with a higher probability of conversion.

Objective:

The objective is to develop a predictive model to identify clients who are likely to subscribe to a term deposit based on data from previous direct marketing campaigns conducted by a Portuguese banking institution. The model aims to predict the binary outcome (yes or no) indicating whether a client will subscribe to a term deposit.

Detailed Column Descriptions: age: This column represents the age of the bank client. It's a numeric variable indicating the age in years.

job: This column indicates the type of job the client has. It's a categorical variable with options such as "admin.", "unknown", "unemployed", "management", etc.

marital: This column represents the marital status of the client. It's a categorical variable with options such as "married", "divorced", or "single".

education: This column indicates the level of education of the client. It's a categorical variable with options such as "unknown", "secondary", "primary", or "tertiary".

default: This column indicates whether the client has credit in default. It's a binary variable with options "yes" or "no".

balance: This column represents the average yearly balance in euros for the client. It's a numeric variable.

housing: This column indicates whether the client has a housing loan. It's a binary variable with options "yes" or "no".

loan: This column indicates whether the client has a personal loan. It's a binary variable with options "yes" or "no".

contact: This column represents the type of communication used to contact the client. It's a categorical variable with options such as "unknown", "telephone", or "cellular".

day: This column represents the last contact day of the month. It's a numeric variable.

month: This column represents the last contact month of the year. It's a categorical variable with options such as "jan", "feb", "mar", etc.

duration: This column represents the duration of the last contact in seconds. It's a numeric variable.

campaign: This column represents the number of contacts performed during this campaign and for this client. It's a numeric variable.

pdays: This column represents the number of days that passed by after the client was last contacted from a previous campaign. It's a numeric variable where -1 means the client was not previously contacted.

previous: This column represents the number of contacts performed before this campaign and for this client. It's a numeric variable.

poutcome: This column represents the outcome of the previous marketing campaign. It's a categorical variable with options such as "unknown", "other", "failure", or "success".

y: This column is the target variable and indicates whether the client has subscribed to a term deposit. It's a binary variable with options "yes" or "no".# Python-ML
ML Projects 
