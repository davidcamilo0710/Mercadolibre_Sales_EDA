# EDA on ResetStore-Mercadolibre Sales: Project Overview
## Table of Contents
* [Background](#background)
* [Important EDA Questions](#important-eda-questions)
* [Dataset Features and Descripment](#dataset-features-and-descripment)
* [EDA Steps](#eda-steps)
* [Important Graphs](#important-graphs)
* [Important Business Inferences](#important-business-inferences)
* [TABLEAU Dashboard](#tableau-dashboard)

## Background 

Resetstore is a store that operates in Mercadolibre Colombia and makes shipments to the whole country. This company has several active advertising campaigns in the different departments and it is required to observe the results, get business inferences and take decisions. For this reason, this project focuses on analyze the sales, profit using Statistics and Visualization techniques. You can see the analysis process in [Spanish](https://nbviewer.org/github/davidcamilo0710/Mercadolibre_Sales_EDA/blob/master/Ventas_ResetStore_EDA.ipynb) and in [English](https://nbviewer.org/github/davidcamilo0710/Mercadolibre_Sales_EDA/blob/master/Sales_ResetStore_EDA.ipynb) and the visualization in Tableau [here](https://public.tableau.com/views/ResetStoreColombia/Dashboard1?:language=es-ES&:display_count=n&:origin=viz_share_link). In addition, a projection...

## Important EDA Questions

- Understanding our geographic spread of customers in Colombia
- Check if any geographic region or city has significantly less profit and address why
- Check for any promising departments/cities to expand our advertising campaigns
- Understanding which type of products have high revenue and profit
- Does shipping mode has any effect on revenue and profit

## Dataset Features and Descripment
![Inversiones](https://user-images.githubusercontent.com/60159274/158505131-a5fa7fea-b6c6-408c-a55a-33577dd75017.png)

- Year
- Date
- Platform - Default Mercadolibre
- Region - Divided by Amazonía, Andina, Caribe, Orinoquia and Pacifica
- Department
- Municipality
- Transport - Shipping mode of the purchased products
- Category - Category of the product
- Products - Sub-Category
- Quantity - Quantity of products in the purchase
- Discount - % Discount availed
- Sale - Revenue obtained from the purchase
- Profit - Profit/Loss

## EDA Steps

- Five point Descriptive Statistics - Univariate description of both the numerical and categorical variables
- Correlation and Pair plot - Distribution and the relation between the numerial variables
- Bivariate and multivariate Analysis - Plotting Pieplot and Barplots to visualize and infer the significance of the features

## Important Graphs

1. Bogota DC among Medellin among top 10 Revenue contributing Cities

![Top 10 Municipios](https://user-images.githubusercontent.com/60159274/158505069-ce46bc74-7cbb-4b8e-aac2-97891fd97db1.png)

2. Relatively smaller municipalies such as Tumaco and Cartago have higher revenue and profit per purchase on average

![Inversiones](https://user-images.githubusercontent.com/60159274/158505152-31872809-e8d0-404e-9452-151bd99f1e6a.png)

3. Orinoquia Region trending in less profits because of loss in Home Appliances category. This is to be expected given a donation that is made and represents a negative profit

![Orinoquia](https://user-images.githubusercontent.com/60159274/158505194-d2e31594-3487-43fe-8e6e-371b997de7e4.png)

4. Trade Equipment have been given high discount at times, but Home appliances have wider possible range of discount

![descuento](https://user-images.githubusercontent.com/60159274/158505632-2fd0fb66-5fa0-4a86-9096-ee4e6d91ac44.png)

5. Products on Industrial category yields best revenue and profit per purchase

![categoria](https://user-images.githubusercontent.com/60159274/158505362-1fa2c067-06a2-4e2e-9ff3-39e40dc88d15.png)

6. Surprisingly, Selling a unit of proyector gives almost 3 times more profit than selling a unit product from Corte laser and 16 times than other sub category in Industrial

![Industrial](https://user-images.githubusercontent.com/60159274/158505382-2db3cdb4-2fed-49e1-b842-a0ddd25b9c84.png)

7. "Servientrega-2" It is a fast delivery service, for this reason it provides a little more profit

![Transporte](https://user-images.githubusercontent.com/60159274/158505388-185d94a5-3124-492a-b103-1cd815ba0184.png)

## Important Business Inferences

1. In Orinoquia, the Home appliances business is in loss and it is a concern to be addressed
2. Company gets high revenue from popular cities such Bogota DC, Medellin and Cali, but small municipalities such as Tumaco and Quibdo shows promise with high average revenue and profit per purchase
3. Industrial products give the best average profit per purchase
4. In Industrial related products, Proyectors gives between 3x and 16x profit compared with any other sub category
5. Company should promote "Servientrega-2" shipping modes for better revenue and profit per purchase

## TABLEAU Dashboard

Develop a dashboard for an optimal visualization of the data, you can access the view [here](https://public.tableau.com/views/ResetStoreColombia/Dashboard1?:language=es-ES&:display_count=n&:origin=viz_share_link)

![Tableu](https://user-images.githubusercontent.com/60159274/158330809-6f5bd381-d914-45a3-966d-ad109bcf05d7.png)
