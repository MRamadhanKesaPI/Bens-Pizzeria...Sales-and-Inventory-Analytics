# Ben’s Pizzeria - Sales & Inventory Analytics

**Welcome to my personal project repository!**

## Table of Contents
- [**Project Background**](#project-background)
- [**Project Assets**](#project-assets)
- [**Data Structure**](#data-structure)
- [**Insights**](#insights)
- [**Recommendations**](#recommendations)

## Project Background
Ben’s Pizzeria is a small, newly established pizzeria specializing in delivery and pickup. Based in Houston, it has already served customers in Austin, Dallas, and El Paso. With a focus on long-term growth, the business aims to optimize sales and improve inventory management. 

Key objectives include identifying outperforming products, ensuring sufficient stock for popular items, and refining overall sales strategies. To support these efforts, Ben’s Pizzeria has provided two months of orders and inventory data to uncover insights into recent trends and inform data-driven decisions.

### Purpose of the Analysis:
The goal of this analysis is to help Ben’s Pizzeria make data-driven decisions to improve sales and inventory management. The goals are to:

- Analyze sales trends and customer ordering patterns to maximize revenue opportunities.
- Provide actionable recommendations to improve delivery efficiency and enhance customer experience.
- Identify best-selling and underperforming items to optimize inventory and reduce waste.

## Project Assets
To make the analysis and insights easy to explore, the following resources are available:

- The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Processes_for_Bens-Pizzeria...Sales-and-Inventory-Analytics/).

- The DAX measures to support data analysis can be found [here](https://mramadhankesapi.github.io/DAX-Processes_for_Bens-Pizzeria...Sales-and-Inventory-Analytics/).
  
- A Power BI dashboard can be downloaded here: [Ben's Pizzeria.pdf](https://github.com/user-attachments/files/18859091/Ben.s.Pizzeria.pdf) or [Ben's Pizzeria.pbix](https://github.com/MRamadhanKesaPI/Bens-Pizzeria...Order-Activity-and-Inventory-Management/blob/main/Ben's%20Pizzeria.pbix)

## Data Structure
The Ben's Pizzeria datasets used in this project consist of four tables. Three come from PostgreSQL (Order Activity, Inventory Management 1, and Inventory Management 2), and one is a DAX measure table (Ben's Pizzeria Measures).

![Relationships Ben's](https://github.com/user-attachments/assets/655cd5df-ed7e-4dae-8330-2ca4e81a1e1c)

These final datasets were created by generating views in PostgreSQL. The steps can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Processes_for_Bens-Pizzeria...Order-Activity-and-Inventory-Management/).

## Insights
#### 1. Top-Selling Items & Categories:  
   - **Pizza** is the highest-grossing category, dominating sales compared to sides, beverages, and desserts.  
   - **Chicken wings** and **Dr. Pepper** also have strong sales, which may be surprising given pizza’s dominance. 

#### 2. Revenue & Order Trends:  
   - **Peak sales** occur during **lunch** and **evening** hours.  
   - **Order volume** fluctuates throughout the day, highlighting opportunities for **targeted promotions**.  

#### 3. Delivery vs. Pickup Distribution: 
   - **Delivery** accounts for **73.07%** of total orders, while **pickup** represents **26.93%**, emphasizing the need to optimize **delivery logistics**. 

#### 4. Inventory Stock & Management:  
   - Some beverages, such as **Dr. Pepper** and **Pepsi**, have critically low stock levels (<25%).  
   - **Pizza dough**, **mozzarella**, and **key pizza toppings** show moderate stock depletion, requiring **restocking strategies**. 

---
Below is an overview from the Power BI dashboard. A Power BI dashboard can be downloaded here: [Ben's Pizzeria.pdf](https://github.com/user-attachments/files/18859091/Ben.s.Pizzeria.pdf) or [Ben's Pizzeria.pbix](https://github.com/MRamadhanKesaPI/Bens-Pizzeria...Order-Activity-and-Inventory-Management/blob/main/Ben's%20Pizzeria.pbix)

![Ben's Pizzeria 1](https://github.com/user-attachments/assets/8318a2dc-8c0b-49c6-b0b3-4e634f51ebe7)

![Ben's Pizzeria 2](https://github.com/user-attachments/assets/b022d0f8-ca50-48d1-a2c2-b10d474b5b2e)

---

## Recommendations
#### 1. Top-Selling Items & Categories:  
   - **Highlight High Performers**:Highlight pizza, chicken wings, and Dr. Pepper in marketing and bundle deals to maximize revenue.  
   - **Add Variety**: Introduce new pizza flavors or wing sauces to keep customers interested.

#### 2. Revenue & Order Trends:  
   - **Boost Slow Periods**: Offer discounts or combos during off-peak times to increase sales. 
   - **Manage Rush Hours**: Ensure enough staff and stock during lunch and evening peaks to handle demand efficiently.
     
#### 3. Delivery vs. Pickup Distribution:  
   - **Streamline Delivery**: Improve routing, packaging, and staff training to prepare delivery orders as efficiently and quickly as possible. 
   - **Encourage Pickup**: Offer small incentives (like discounts or loyalty points) to reduce delivery load.

#### 4. Inventory Stock & Management:  
   - **Monitor Critical Stock**: Regularly monitor inventory levels to prevent them from dropping below 25%
   - **Restock Key Ingredients**: Keep enough pizza dough, mozzarella, and toppings, adjusting orders based on trends.
   - **Reduce Waste**: Identify slow-selling items and lower their stock levels to avoid overordering.

---
### Thank you for exploring this project, Feel free to hear your thoughts, insights, or any feedback! Let’s keep the discussion going!
