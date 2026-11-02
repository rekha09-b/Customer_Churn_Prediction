# Customer Churn Analysis and Prediction

## Project overview
Customer churn occurs when a customer stops using a company's services. Understanding which customer groups are associated with churn can help a business investigate customer needs and plan retention efforts.

This project analyzes a telecom customer dataset and compares churn with attributes such as:
- Gender, senior-citizen status, partner, and dependents
- Phone service and internet service type
- Online security and tech support
- Contract type, paperless billing, and payment method


## Key findings
- The dataset contains both churned and retained customers, with retained customers forming the larger group overall.
- Churn counts are similar for female and male customers.
- Non-senior customers make up the larger share of churned customers.
- Customers without partners or dependents make up a larger share of churned customers in the observed counts.
- Fiber-optic customers have the highest churn count among internet-service groups.
- Churn counts are higher among customers without online security or tech support.
- Month-to-month contract customers show the highest churn count; churn is lower for one-year contracts and lowest for two-year contracts.
- Electronic-check users show the highest churn count among payment-method groups.

## Libraries
- Pandas, NumPy, Matplotlib

## Repository contents
- Customer_Churn_Prediction.ipynb
- data.csv
- README.md

## EDA Visualizations
## 1. Over All Churn Status
<img width="557" height="331" alt="Screenshot 2026-11-02 163539" src="https://github.com/user-attachments/assets/6883b5f9-8315-4e66-a127-eedd0c2a57f1" />
<img width="521" height="42" alt="Screenshot 2026-11-02 163611" src="https://github.com/user-attachments/assets/c5f0745a-ec9f-4456-ac0e-bc35c2ecaf48" />

## 2. Churn Distribution By Gender
<img width="574" height="347" alt="Screenshot 2026-11-02 164144" src="https://github.com/user-attachments/assets/6dc9d8bb-3d84-4060-b61b-0ff968d5c3ac" />
<img width="533" height="54" alt="Screenshot 2026-11-02 164211" src="https://github.com/user-attachments/assets/8e10f1b4-2153-4d7b-9220-6aa27a2f3d7a" />

## 3. Churn Distribution By Senior Citizen
<img width="558" height="347" alt="Screenshot 2026-11-02 164543" src="https://github.com/user-attachments/assets/82cb3ad2-79c6-49a1-8d1f-445b380b812e" />
<img width="553" height="40" alt="Screenshot 2026-11-02 164612" src="https://github.com/user-attachments/assets/463b414b-14f0-444e-8ab1-e72e9f08d596" />

## 4. Churn Distribution By Partner
<img width="561" height="342" alt="Screenshot 2026-11-02 164906" src="https://github.com/user-attachments/assets/b988c14d-6bfb-4cae-9be3-8c3c57f2c89d" />
<img width="536" height="37" alt="Screenshot 2026-11-02 164932" src="https://github.com/user-attachments/assets/4d8e8b34-52fc-404b-aade-dc0d6a177971" />

## 5. Churn Distribution By Dependent
<img width="559" height="343" alt="Screenshot 2026-11-02 165306" src="https://github.com/user-attachments/assets/d963dc73-30aa-4765-87a7-e1539b0e9dd2" />
<img width="534" height="38" alt="Screenshot 2026-11-02 165328" src="https://github.com/user-attachments/assets/74c2778b-df4f-4ed3-bd72-3935a2139ce8" />

## Services
## 6. Churn Distribution By Phone Service
<img width="566" height="343" alt="Screenshot 2026-11-02 165602" src="https://github.com/user-attachments/assets/302c963e-eeb3-4288-a951-8d7ef06aedcc" />
<img width="528" height="41" alt="Screenshot 2026-11-02 165620" src="https://github.com/user-attachments/assets/2759641f-73eb-44ee-90ec-0dc0fa93bd2c" />

## 7. Churn Distribution By Internet Services
<img width="566" height="341" alt="Screenshot 2026-11-02 165811" src="https://github.com/user-attachments/assets/3afb2791-a341-48bf-adc1-7e4849017d26" />
<img width="555" height="51" alt="Screenshot 2026-11-02 165828" src="https://github.com/user-attachments/assets/31f9aa46-55cf-45b6-911f-772b2edbcd48" />

## 8. Churn Distribution By Internet Services And Gender
<img width="773" height="341" alt="Screenshot 2026-11-02 170043" src="https://github.com/user-attachments/assets/a9910604-f97c-43ec-944e-92b11bc4f886" />
<img width="585" height="48" alt="Screenshot 2026-11-02 170118" src="https://github.com/user-attachments/assets/e6487ba5-01b3-4d80-a306-906bb00bca28" />

## 9. Churn Distribution By Online Security
<img width="566" height="338" alt="Screenshot 2026-11-02 170348" src="https://github.com/user-attachments/assets/6cf712e9-1e8c-429a-b4cb-5ff965bbaba7" />
<img width="552" height="52" alt="Screenshot 2026-11-02 170405" src="https://github.com/user-attachments/assets/4b21f471-2357-4ff7-ad29-0ed6a6e55b5b" />

## 10. Churn Distribution By TechSupport
<img width="566" height="346" alt="Screenshot 2026-11-02 170710" src="https://github.com/user-attachments/assets/009fe4d1-d3c4-4b3d-9e3c-f2a45afee07d" />
<img width="544" height="38" alt="Screenshot 2026-11-02 170730" src="https://github.com/user-attachments/assets/63f4e3fe-c506-4324-9446-81fd25858c5e" />

## Account Information
## 11. Churn Distribution By Contract
<img width="552" height="340" alt="Screenshot 2026-11-02 170931" src="https://github.com/user-attachments/assets/6b093215-8711-40e6-a560-df48ea59933d" />
<img width="547" height="47" alt="Screenshot 2026-11-02 170949" src="https://github.com/user-attachments/assets/e83d09d4-5d0e-42e2-acce-407f2c6b6589" />

## 12. Churn Distribution By PaperlessBilling
<img width="551" height="344" alt="Screenshot 2026-11-02 171133" src="https://github.com/user-attachments/assets/cffa8135-9d43-4b4b-bf8d-5a6f72412379" />
<img width="537" height="36" alt="Screenshot 2026-11-02 171150" src="https://github.com/user-attachments/assets/5806d824-7bfb-45a1-8b0f-5cf51d82e9c0" />

## 13. Payment Method Distribution
<img width="560" height="341" alt="Screenshot 2026-11-02 171350" src="https://github.com/user-attachments/assets/b41921aa-b0d4-4a72-ac5d-5b4633fe8223" />

## 14. Churn Distribution By Payment Method
<img width="560" height="343" alt="Screenshot 2026-11-02 171716" src="https://github.com/user-attachments/assets/67d111bb-e6d3-4cbd-a6b6-13e8635816a2" />
<img width="533" height="52" alt="Screenshot 2026-11-02 171740" src="https://github.com/user-attachments/assets/24cac6f7-b7c0-4383-bd89-6a00221c3251" />





