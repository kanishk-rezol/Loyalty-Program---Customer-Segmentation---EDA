# Loyalty Program – Customer Segmentation & EDA

**Scenario:**  
NovaMall, a large urban shopping mall, recently launched a loyalty program to reward repeat customers and drive more personalized marketing. The mall has collected transaction data and membership details over the last year, and your task is to help them understand customer behavior using data analysis.:

You are provided with transaction and loyalty data from a shopping mall.


## Sample Data Columns Explained
The dataset contains transactional and customer-level information from NovaMall's loyalty program. Here are some key columns:

<h2>Dataset Overview</h2>

<table>
  <thead>
    <tr>
      <th>Column Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>InvoiceID</td>
      <td>Unique identifier for each transaction</td>
    </tr>
    <tr>
      <td>CustomerID</td>
      <td>Unique ID for each customer</td>
    </tr>
    <tr>
      <td>CustomerName</td>
      <td>Full name of the customer</td>
    </tr>
    <tr>
      <td>Age</td>
      <td>Age of the customer</td>
    </tr>
    <tr>
      <td>Gender</td>
      <td>Gender of the customer (e.g., Male, Female, Other)</td>
    </tr>
    <tr>
      <td>JoinDate</td>
      <td>Date the customer joined the loyalty program</td>
    </tr>
    <tr>
      <td>VisitDate</td>
      <td>Date of the purchase/visit</td>
    </tr>
    <tr>
      <td>Region</td>
      <td>Geographical location of the customer (e.g., North, South, East, West)</td>
    </tr>
    <tr>
      <td>Category</td>
      <td>Product category (e.g., Apparel, Electronics, Groceries)</td>
    </tr>
    <tr>
      <td>ProductID</td>
      <td>Unique identifier for the purchased product</td>
    </tr>
    <tr>
      <td>ProductPrice</td>
      <td>Price per unit of the product</td>
    </tr>
    <tr>
      <td>Quantity</td>
      <td>Number of units purchased</td>
    </tr>
    <tr>
      <td>TotalSpent</td>
      <td>Total amount spent before discount (ProductPrice × Quantity)</td>
    </tr>
    <tr>
      <td>Discount</td>
      <td>Discount applied to the transaction</td>
    </tr>
    <tr>
      <td>FinalAmount</td>
      <td>Total spent after discount (TotalSpent - Discount)</td>
    </tr>
    <tr>
      <td>PaymentMethod</td>
      <td>Payment method used (e.g., Card, Cash, Wallet)</td>
    </tr>
    <tr>
      <td>MembershipStatus</td>
      <td>Loyalty tier (e.g., Bronze, Silver, Gold, Platinum)</td>
    </tr>
    <tr>
      <td>Email, Phone</td>
      <td>Contact details of the customer (optional for segmentation, not analysis)</td>
    </tr>
  </tbody>
</table>


## Objectives

1. **Clean and Explore the Data**
   - Prepare data for analysis by handling missing values, outliers, and formatting issues.

2. **Perform Exploratory Data Analysis (EDA)**
   - Identify key customer segments by:
     - Age
     - Gender
     - Region
     - Spending habits

3. **Revenue Contribution**
   - Determine which **membership tier** contributes the most to overall revenue.

4. **Customer Clustering**
   - Cluster customers based on behavioral features such as:
     - Frequency of purchase
     - Average spending
     - Discount usage

5. **Data Visualization**
   - Use the following visuals to communicate findings:
     - Bar Charts
     - Box Plots
     - Line Cart
or any other relevent visulization based on your analysis

## Deliverables

- Jupyter Notebook (`.ipynb`) with code, visuals, and findings
- A summary markdown/report explaining **3 key business insights**

## Add The Output IPYNB Files in same directly
ex. file name : Kanishq_EDA.ipynb


## Submission Checklist

-Cleaned dataset and code
-Insightful EDA
-Clustering analysis
-Business insights summarized
-Visuals included
-Notebook and README uploaded


BEST OF LUCK


