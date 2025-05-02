# data-platform-batch58

## Vietnamese
📌 Giới thiệu  
Dự án này trình bày một nền tảng dữ liệu **từ ingestion đến trực quan hóa**, giúp xử lý dữ liệu lớn bằng các công nghệ hiện đại như **Apache Airflow, Spark, Delta Lake, Trino, Power BI**.  

## 🏗 Kiến trúc hệ thống  
![Data Platform Architecture](link-hinh-kien-truc.png)  

### 🔹 Thành phần chính:
- **Data Ingestion**: Thu thập dữ liệu từ nhiều nguồn (S3, API, Kafka).  
- **Orchestration**: Airflow lên lịch và giám sát pipeline ETL.  
- **Storage**: MinIO/S3 để lưu dữ liệu raw (Bronze layer).  
- **Processing**: Apache Spark xử lý dữ liệu theo tầng Silver & Gold.  
- **Query Engine**: Trino tăng tốc truy vấn dữ liệu.  
- **Metadata**: OpenMetadata để quản lý lineage dữ liệu.  
- **BI & Visualization**: Power BI giúp phân tích trực quan hóa dữ liệu.  

## ⚙️ Công nghệ sử dụng  
| Công nghệ  | Chức năng |
|------------|----------|
| **Apache Airflow** | Orchestrate pipelines |
| **Apache Spark** | Xử lý dữ liệu lớn |
| **Delta Lake** | Lưu trữ dữ liệu với ACID Transactions |
| **Trino** | Engine truy vấn dữ liệu |
| **MinIO** | Object Storage |
| **dbt** | Modeling dữ liệu |
| **Power BI** | Trực quan hóa dữ liệu |

## 🚀 Hướng dẫn triển khai  
### 1️⃣ **Clone repo & thiết lập môi trường**  
```sh
git clone https://github.com/username/data-platform-batch58.git
cd data-platform-batch58


## English
📌 Introduction  
This project presents a **complete data platform architecture**, processing large-scale data using modern technologies such as **Apache Airflow, Spark, Delta Lake, Trino, and Power BI**.  

## 🏗 System Architecture  
![Data Platform Architecture](link-to-architecture-image.png)  

### 🔹 Key Components:
- **Data Ingestion**: Collecting data from multiple sources (S3, API, Kafka).  
- **Orchestration**: Airflow schedules and monitors ETL pipelines.  
- **Storage**: MinIO/S3 to store raw data (**Bronze layer**).  
- **Processing**: Apache Spark processes data in **Silver & Gold layers**.  
- **Query Engine**: Trino accelerates data queries.  
- **Metadata Management**: OpenMetadata to track data lineage.  
- **BI & Visualization**: Power BI for insightful analytics.  

## ⚙️ Technologies Used  
| Technology  | Function |
|------------|----------|
| **Apache Airflow** | Orchestrates data pipelines |
| **Apache Spark** | Processes large-scale data |
| **Delta Lake** | Ensures ACID transactions & time travel |
| **Trino** | High-performance query engine |
| **MinIO** | Object storage for raw data |
| **dbt** | Data modeling & transformation |
| **Power BI** | Visualizes & analyzes data |

## 🚀 Deployment Guide  
### 1️⃣ **Clone the repository & set up the environment**  
```sh
git clone https://github.com/username/data-platform-batch58.git
cd data-platform-batch58
