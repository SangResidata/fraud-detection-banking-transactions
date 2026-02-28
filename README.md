# fraud-detection-banking-transactions
this dataset provides in-depth insights into transaction behavior and financial activity patterns, making it ideal for fraud detection exploration and anomaly identification.  

This dataset contains 16 columns and 2,512 samples of transaction data, covering a wide range of transaction attributes, customer demographics, and activity patterns. Every entry provides comprehensive insights into transaction behavior, making it a robust foundation for building predictive models and enhancing financial security through anomaly detection.  

Key Features:

- **TransactionID**: A unique alphanumeric identifier for each transaction.
- **AccountID**: A unique identifier for each account (accounts may have multiple transactions).
- **TransactionAmount**: The monetary value of the transaction, ranging from small daily expenses to large purchases.
- **TransactionDate**: The specific date and time when the transaction occurred.
- **TransactionType**: The category of transaction, either 'Credit' or 'Debit'.
- **Location**: The geographic location of the transaction (US city names).
- **DeviceID**: The unique ID of the device used to perform the transaction.
- **IP Address**: The IPv4 address used during the transaction; useful for tracking account activity.
- **MerchantID**: A unique identifier for the merchant, used to identify primary merchants and transaction anomalies.
- **AccountBalance**: The remaining balance in the account after the transaction is processed.
- **PreviousTransactionDate**: The date of the last transaction on the account; essential for calculating transaction frequency.
- **Channel**: The medium used for the transaction (Online, ATM, or Branch).
- **CustomerAge**: The age of the account holder.
- **CustomerOccupation**: The profession of the user (e.g., Doctor, Engineer, Student, or Retired).
- **TransactionDuration**: The total duration of the transaction in seconds.
- **LoginAttempts**: The number of login attempts prior to the transaction—high counts may indicate potential security anomalies.
