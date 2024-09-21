# Financial-Fraud-Detection-System <br/>

Data are obtained from https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data/data to local storage.<br/>
The model is trained using Random Forest algorithm, achieving an accuracy of 99.94% and reducing false positives to 35.<br/>
The model's features are engineered using a correlation matrix and Variance Inflation Factor (VIF).<br/>
Log transformation is applied to normalize skewed data and outliers are detected and removed.<br/>



### What are the key factors that predict fraudulent customer?<br/>

**1. Transaction Patterns:** Unusual transaction amounts, frequency, or merchant categories.<br/>
**2. Geolocation & Device:** Unusual locations, new devices, or geographical inconsistencies.<br/>
**3. Account Changes:** Sudden changes in personal info (address, email, etc.).<br/>
**4. Payment Methods:** Use of multiple or prepaid cards, switching payment methods.<br/>
**5. Past Fraud:** Previous fraud history or frequent chargebacks.<br/>
**6. Demographics:** Age, income, and employment factors.<br/>



### Do these factors make sense? If yes, How? If not, How not? <br/>

1. Transaction patterns (e.g., unusual amounts or frequency) and geolocation/device changes signal abnormal behavior.<br/>
2. Sudden account changes and unusual login patterns often point to account takeovers.<br/>
3. Multiple or prepaid payment methods are typical of fraud attempts.<br/>
4. Past fraud history predicts future risk.<br/>
5. Demographics and suspicious communication provide additional context but must be used carefully to avoid bias.<br/>



### What kind of prevention should be adopted while company update its infrastructure? <br/>

**1. Enhanced Authentication:** Use multi-factor authentication (MFA), biometric login, and device fingerprinting.<br/>
**2. Real-time Fraud Detection:** Implement AI-based monitoring, anomaly detection, and geolocation tracking.<br/>
**3. Data Security:** Ensure end-to-end encryption, tokenization, and secure payment gateways.<br/>
**4. Security Audits:** Conduct regular security audits, testing.<br/>
**5. Behavioral Monitoring:** Track user transactions for suspicious activity.<br/>
**6. Access Control:** Limit access with role-based controls and enforce strong password policies.<br/>
**7. External Collaboration:** Utilize shared fraud databases and work with financial institutions.<br/>
**8. Customer Education:** Raise awareness about phishing and fraud risks.<br/>




### Assuming these actions have been implemented, how would you determine if they work?<br/>

1. Track the number of fraud attempts and successful fraud cases over time. A decreasing trend indicates effectiveness.<br/>
2. Measure how often legitimate activities are incorrectly flagged as fraud. Lower false positives show improved precision.<br/>
3. Analyze customer feedback and complaints related to security measures, ensuring that protections don't negatively impact user experience.<br/>
4. Evaluate how quickly fraud detection systems identify and prevent fraud. Faster detection means better system performance.<br/>
