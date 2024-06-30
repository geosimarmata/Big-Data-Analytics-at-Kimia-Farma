# Big Data Analytics: Kimia Farma Virtual Internship
![RakaminxKimiaFarma](https://github.com/geosimarmata/Big-Data-Analytics-at-Kimia-Farma/blob/main/Figs/Rakamin%20X%20Kimia%20Farma.png)

## Description
This repository contains the project work for the Kimia Farma Virtual Internship focusing on Big Data Analytics. The internship program, in collaboration with Rakamin Academy and Kimia Farma, aims to develop skills and accelerate careers in the field of Big Data Analytics. Participants are introduced to foundational learning materials such as Article Reviews and Company Coaching Videos to familiarize themselves with the competencies required for Big Data Analytics roles in the company. The program includes weekly Task assessments and culminates in a final project where participants are tasked to create a portfolio-worthy sales dashboard from raw data.

## Project Details
The final project for this internship involves creating a sales dashboard for one of Kimia Farma's products based on data spanning one year. Participants will work with provided raw data to develop insights and visualize trends using tools like PostgreSQL for data management, Google Data Studio for visualization, and SQL for programming tasks.

## Dataset
The provided dataset consists of the following tables:

**penjualan**: Sales transactions data.
**barang**: Product details.
**pelanggan**: Customer information.

### 📂 Design Datamart
[Click here to view the Query](https://github.com/geosimarmata/Big-Data-Analytics-at-Kimia-Farma/blob/main/All_Query.sql)

#### Tabel Base
The base table combines data from penjualan, pelanggan, and barang tables with the primary key on invoice_id.
![Sample Base Table](https://github.com/geosimarmata/Big-Data-Analytics-at-Kimia-Farma/blob/main/Figs/Base_table_fig.png)

#### Tabel Aggregate
The aggregate table summarizes data from the base table, facilitating faster and more efficient data analysis. This table will serve as the source for creating the sales dashboard.
![Sample Aggregate Table](https://github.com/geosimarmata/Big-Data-Analytics-at-Kimia-Farma/blob/main/Figs/Agg_table_fig.png)

### 📊 Data Visualization
Built a comprehensive dashboard using Google Data Studio with the aggregate table as the data source. Explore the dashboard here.

