# Global-Retail-Customer-Segmentation-with-RFM
## Project Overview 
This project demonstrates the implementation of RFM (Recency, Frequency, Monetary) analysis for customer segmentation at SuperStore, a global retail company. It aims to help the marketing team design targeted campaigns based on customer behaviors.
Tools Used: 
Python
## Dataset 
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. Dataset named "ecommerce retail"
Main tables:
    - InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
    - StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
    - Description: Product (item) name. Nominal.
    - Quantity: The quantities of each product (item) per transaction. Numeric.
    - InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
    - UnitPrice: Unit price. Numeric, Product price per unit in sterling.
    - CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
    - Country: Country name. Nominal, the name of the country where each customer resides.
## Data processing
## Suggestions for marketing team
- Champions: recent, frequent, highest revenue purchases --> offer special deals, frequent customer care.
- Loyal: frequent purchases --> Encourage them to join the loyalty program or special deals for frequent customers to increase loyalty.
- Potential Loyalist: new customers but spend a lot --> offer attractive promotions
- New Customers: recent purchases but very low frequency --> suggest best-selling products
- Promising: recent purchases but low spending --> Offer deals or discounts on their next purchase to encourage them to spend more
- Need Attention: moderate frequency and spending --> Send information about new deals or new products via email or text to keep them in mind about the brand.
- About To Sleep: low frequency and revenue --> Send emails to remind them about your brand and encourage them to come back
- At Risk: buy a lot and often but not long ago --> Contact them directly to ask about their shopping experience and listen to their needs
- Cannot Lose Them: buy a lot but low number of customers and recent revenue --> Offer deals, promotions or discounts, create urgency by sending short-term offers to encourage them to shop now, keep them there by all means
- Hibernating customers: haven't bought in a while, low spending --> Offer products with special discounts
- Lost customers: rfm is almost lowest --> Create many product promotion campaigns
