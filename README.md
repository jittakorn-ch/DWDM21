# DWDM21
### Data Warehouse & Data Mining 2021

**นายจิตรกร จันทะสี 623021044-1**

*Group Name*: **แมวส้มสร้างตัว**
1. จิตรกร จันทะสี
2. คำแสน แก้วพิภพ
3. วานิตา สมเด็จ
4. อาธิติยา ธรรมวงษา
5. กรกนก สังฆพันธ์


# สารบัญ
* บทที่ 1: [Introduction](https://github.com/jittakorn-ch/DWDM21/blob/main/Chapeter1.md) (บรรยาย)
  * Data Warehouse & Data Mining
    * Data Mining (การทำเหมืองข้อมูล)
      * Knowledge Discovery (KDD) Process
      * ขั้นตอนการทำเหมืองข้อมูล
      * เทคนิคของ Data Mining
* บทที่ 2: Know Your Data
  * [มิติของ Data](https://github.com/jittakorn-ch/DWDM21/blob/main/Chapter2%20(note).pdf) (บรรยาย)
  * [Basic Python](https://github.com/jittakorn-ch/DWDM21/blob/main/Data101_(Chapter2).ipynb)
    * Varibles
    * Casting
    * Data Structure (list)
      * วิธีสร้าง list ว่าง
      * เติมค่าลงใน list (.append())
      * การชี้ค่าใน list (indexing)
      * list slicing
      * format string
    * Loop
      * Nested loop
    * Condition (if statment)
    * Function
      * normal
      * ไม่มี input
      * ไม่มี output
      * ไม่มีทั้ง input และ output
      * ลักษณะของ input (parameter)
  * [Pandas](https://github.com/jittakorn-ch/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    * Read Data
      * .head() & .tail() (ดูหัวตาราง ท้ายตาราง)
    * Boxplot
    * Time Series plot
  * [Visualization](https://github.com/jittakorn-ch/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
      * Normal
      * กำหนดขนาดจุด
      * กำหนดสี
      * เปลี่ยนลักษณะของจุดเป็นอย่างอื่น
    * Plot (เป็นการพล็อตกราฟที่เชื่อมกัน)
    * Bar Chart
      * Grouped Barchart (พล็อตเทียบด้านข้าง)
      * Stacked Barchart (พล็อตเทียบในแท่งเดียวกัน)
    * Histogram
  * [Distance Numpy](https://github.com/jittakorn-ch/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
      * สร้าง numpy array (matrix)
      * matrix transpose
      * สร้าง matrix เริ่มต้น (zeros,ones)
      * สร้าง matrix random
      * matrix properties
      * matrix properties
      * Useful functions
      * เขียน function วนลูปหา sum, mean, max, min
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * Distance of Binary Value
* บทที่ 3: [Data Preprocessig](https://github.com/jittakorn-ch/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)
  * การชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดา [ชื่อคอลัมน์][index]
    * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
  * Missing Values
    * Handling Missing value 1 (ลบค่า missing)
    * เขียน function หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
    * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
    * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
    * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
    * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
    * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
  * Select data by values [PD]
    * สร้าง list ของ boolean
    * นำ list ของ boolean มาเลือกค่าในตาราง
  * ต่อตางแนวแกน Y [PD]
    * Handling Missing Value 5 (แทนด้วย ค่ากลางของ sample ใน class เดียวกัน) ต่อ
    * การเรียงข้อมูล [PD]
  * หา Outlier
    * เขียนฟังค์ชั่น คำนวณ หา Q1,Q2,Q3,IQR,vmin,vmax โดยรับ input เป็น output ขอบ boxplot
    * เขียน function box_vals ให้สามารถรับ input ที่ box plot วาดแบบแนวนอนได้ (vert = False)
    * Panda's looping (.ilerrows)
  * การรวมตาราง (ต่อตารางในแนวแกน x)
    * รวม 2 ตาราง (.merge())
    * เลือกมาเฉพาะ column ที่ต้องการมาแปะ (.map())
  * Group by (pandas)
  * [PD] save ตารางเอาไปใช้ที่อื่น
  * [PD] การสร้างตาราง
      


























