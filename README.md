# nyc-taxi-2025-pyspark
Phân tích &amp; làm sạch dữ liệu NYC Yellow Taxi 2025 bằng PySpark trên Google Colab
# Phân tích dữ liệu NYC Yellow Taxi 2025 với PySpark

## Tổng quan
Notebook thực hiện tiền xử lý, làm sạch và phân tích mô tả dữ liệu chuyến đi **NYC Yellow Taxi năm 2025** trên **Google Colab** sử dụng **PySpark**.

## Quy trình xử lý
1. **Kết nối & Khởi tạo:** Gắn Google Drive, khởi tạo `SparkSession` và kiểm tra danh sách tệp `.parquet`.
2. **Làm sạch dữ liệu:** Gộp 12 tệp dữ liệu năm 2025, chuẩn hóa kiểu dữ liệu, lọc dữ liệu nhiễu/ngoại lai và lưu vào `taxi_clean_2025`.
3. **Phân tích & Trực quan hóa:** Thống kê số chuyến theo giờ, theo thứ trong tuần, Top 10 khu vực đón/trả và phân bố tổng tiền chuyến đi.

## Công cụ sử dụng
- Python, Google Colab
- PySpark (`SparkSession`, `pyspark.sql.functions`)
- Pandas, Matplotlib, Seaborn
