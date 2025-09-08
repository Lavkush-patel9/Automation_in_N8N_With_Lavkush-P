# Automation_in_N8N_With_Lavkush-P

AutoPoet 🖋️✨

An AI-powered automation workflow that generates personalized poems based on a person’s name, looks, and profession.

🔧 Tools Used

n8n – Workflow automation

Airtable – Data storage & management

Google Gemini AI (Chat Model) – Poem generation

⚡ Workflow Steps

Form Submission → User fills a form with Name, Looks, and Profession

Airtable Record → Data stored in Airtable

Pathway Selection → Different profession paths (Software Engineer, Web Developer, AI Engineer)

AI Poem Generation → Gemini AI writes a creative poem based on inputs

Update Airtable → Poem automatically saved back to Airtable

<img width="1567" height="617" alt="image" src="https://github.com/user-attachments/assets/20bd0d24-7ef9-433b-a19e-92aa41692245" />

<img width="1796" height="398" alt="image" src="https://github.com/user-attachments/assets/b4c87a3c-ca4d-469f-9da8-33d14edcaa46" />


SmartPay Automation 💡

An automation workflow built with n8n + Excel + Google Sheets that processes customer data and automatically separates records based on payment method.

🔧 Tools Used

n8n – Workflow automation

Excel Sheet – Raw data source

Google Sheets – Structured data management

Customer Database – Central storage

IF Node (Data Transformation) – Payment method filter

⚡ Workflow Steps

Import raw data from Excel into n8n

Push structured data into a customer database

Sync with Google Sheets for better data handling

Edit Fields → only keep:

CustomerID, CustomerName, Product, Quantity, UnitPrice, TotalPrice

IF Node → Separate customers by payment method:

Cash → Group A

Non-Cash (UPI, Card, etc.) → Group B

📊 Example Data
CustomerID	CustomerName	  Product	  Quantity	UnitPrice	TotalPrice	PaymentMethod
C001	      Rohan Patel	    Laptop	    1	       45000	     45000	     Cash
C002	      Meera Singh	    Headphone	  2	       1500	       3000	       UPI
C003	      Arjun Malhotra	Keyboard	  1	       1200      	 1200	       Card

🚀 Use Cases

Automated billing & reporting

Payment method analysis

E-commerce & retail CRM pipelines

<img width="1690" height="478" alt="Screenshot 2025-09-08 223429" src="https://github.com/user-attachments/assets/a0da228f-521f-4439-9ea7-9dcc58555a90" />




