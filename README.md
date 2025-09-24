# Ghost Kitchen Analytics Project  

In this project, I explored tendencies and potential insights from a **very small dataset**. While small samples are often overlooked, they can still provide a useful overview of operations and raise valuable questions.  

The dataset was a **sample generated with Excel** (available in this repo), simulating a company that manages multiple **ghost kitchens**. Despite the limited size of the data, I aimed to extract some preliminary findings that could later be tested on larger datasets.  

## Key Questions and Observations  

- **Brand performance**: SushiShop appears to be outperforming other brands. But why?  
  - Could it be the specific dates covered in the dataset?  
  - Promotions or stronger online presence?  
  - Brand recognition, or simply better operational performance?  

- **Customer profile**: Buyers are distributed across both gender and age groups, with no strong concentration.  

- **Kitchen locations**: The three locations considered seem to be reasonably well placed. Poorer sales from certain brands may not necessarily be tied to location.  

## Ghost Kitchen Concept & Data Modeling

A **ghost kitchen** is a delivery-only food service model where kitchens operate without a physical dine-in space. Multiple brands can run from the same kitchen, focusing purely on online orders and delivery efficiency. This allows for faster scaling, lower operational costs, and flexible menu testing.

For this project, I modeled the data using a **star-shaped table structure** to make insights clearer and scalable:  

- **Orders** as the central fact table, containing transactions.  
- **Customers**, **Brands**, **Kitchens**, and **Calendar** as dimension tables, providing attributes for analysis.  

Even with a **small dataset**, using a star schema was important because it:  
- Improves clarity of relationships between tables.  
- Makes the model more intuitive to explore in Power BI.  
- Sets a foundation for **future growth**, so the same structure can support much larger datasets without major redesign.  

I could have created **more links and relationships** across the tables, but in this project they didn’t feel necessary. For such a limited dataset, keeping the model simple was the best choice to focus on business insights rather than overcomplicating the schema.

<img width="901" height="685" alt="Structure_gk" src="https://github.com/user-attachments/assets/78b463d1-501e-46aa-b017-48544cbd4051" />



This structure allows easy exploration of trends, brand performance, customer behavior, and location insights, while setting the foundation for future growth and expansion of the dataset.

## Next Steps  

This small-scale analysis demonstrates how even limited data can spark questions. With a larger dataset, these hypotheses could be tested more robustly, enabling deeper insights into:  

- Long-term sales trends  
- Regional and demographic patterns  
- Brand-specific growth opportunities  
