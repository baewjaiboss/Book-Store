<!-- @format -->

# Book Store

Requirement ทางธุรกิจ:

- ทีม Product และทีม Marketing ต้องการขยาย
  ตลาดมาประเทศไทย จึงอยากรู้ว่าสินค้าไหนที่
  ขายดีเพื่อจะได้หาสินค้าที่ถูกใจผู้บริโภคมาวางขาย
  และวางแผนจัดโปรโมชั่นได้เหมาะสม

- ทีม Marketing อยากรู้ยอดขาย และจำนวนลูกค้าในแต่ละประเทศ
- ทีม Marketing อยากรู้ว่าหนังสือเล่มไหนขายดีเพื่อจะได้เลือกมาโปรโมทได้
- ทีม Product อยากรู้ว่าหนังสือหมวดหมู่ไหนขายดีเพื่อจะได้ตามหาหนังสือด้านนั้นมาขายมากขึ้น
- ทีม Marketing อยากได้ระบบค้นหาหนังสือตามยอดขาย ตามประเทศ เพื่อช่วยให้วางแผน Marketing ได้ง่ายขึ้น

Requirement ทาง Tech:

- บริษัทเก็บข้อมูลยอดขายจากบนเว็บไซต์ไว้ใน
  Database
- ต้องการให้ทีม Data Engineer เตรียมข้อมูลให้
  Data Analyst ออฟฟิศไทย เอาข้อมูลนี้มาทำ
  Report และ Dashboard เสนอทีม Product และ
  Marketing

## Workshop1 Data Collection with Python

- Get data from MySQL database และ Get data from REST API โดยนำข้อมูลทั้ง 2 Convert to Pandas และ join the data ให้เป็นตารางเดียวกันและ Save to CSV

## Workshop2 Data Cleansing with Spark

- ใช้ spark ในการทำ Data Profiling เบื้องต้น และดูรายละเอียดข้อมูลด้วยการทำ Exploratory Data Analysis (EDA) และ ทำ Data Cleansing และ Save data เป็น CSV

## Workshop3 Upload to Data Lake

- ใช้ Cloud Storage เป็น Data Lake มีการทดสอบสร้าง Bucket และทดสอบ Upload file โดยใช้ 3 วิธีได้แก่ Web UI ,Command line ,Code Python

## Workshop4 Automated Data Pipeline with Airflow

- ทดสอบสร้าง Cloud Composer จัดการ workflow ด้วย Airflow และได้ทดสอบสร้าง Pipeline

## Workshop5 Data Warehouse with BigQuery

- ทดสอบสร้าง Dataset บน BigQuery และทดสอบ Import ข้อมูลโดยใช้ 3 วิธีได้แก่ Web UI บน web browser ,bq command ด้วย BashOperator บน Airflow ,GCSToBigQeryOperator บน Airflow และได้ทดสอบเขียน SQL

## Workshop6 Data Visualisation with Looker Studio

- ทดสอบการสร้าง view บน BigQuery และทดสอบสร้าง Dashboard บน Looker Studio
