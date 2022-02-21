# List of all the fields part of dataset are as follows: 
<li>business_code: company code of the account</li>
<li>cust_number: customer number given to all the customers of the account</li>
<li>name_customer: name of the customer</li>
<li>clear_date: date on which the customer clears an invoice, or in simple terms, makes the full payment</li>
<li>business_year: the year in which the invoice was created</li>
<li>doc_id: a unique identifier of an invoice</li>
<li>posting_date: the date on which the particular invoice was entered in the ERP database</li>
<li>document_create_date: the date on which the invoice document was created</li>
<li>document_create_date.1: normalized version of document_create_date (we'll use this to split the data)</li>
<li>due_in_date: the date on which the customer is expected to clear an invoice</li>
<li>invoice_currency: the currency of the invoice amount in the document of the invoice</li>
<li>document type: represents the type of document, eg, D1 represents invoice</li>
<li>posting_id: key indicator to identify whether on AR terms is invoice, deduction, credit memo based on its value. Applicable for SAP ERP</li>
<li>area_business: business area in sap is defined as an organisational area within the financial accounting module</li>
<li>total_open_amount: the amount that is yet to be paid for that invoice</li>
<li>baseline_create_date: the date on which the invoice was created</li>
<li>cust_payment_terms: business terms and agreements between customers and accounts on discounts and days of payments</li>
<li>invoice_id: unique number assigned when a seller creates an invoice</li>
<li>isOpen: indicator of whether an invoice is open or closed. isOpen = 1, means that the invoice is still open</li>