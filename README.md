Data warehouse & Data Mining 2021

รหัสนักศึกษา : 623021045-9
 
                  #ชื่อกลุ่ม : วากาเมะ

               #สมาชิกกลุ่มประกอบไปด้วย
    
    623020528-4	นายปริชญา หงส์ทองคำ       SC-SI
    
    623020532-3	นายมันนี่ พิทักษ์	         SC-SI
    
    623020541-2	นายสิทธัตกะ จรัสแสง	 SC-SI
    
    623021045-9	นายชณะชัย อิสระกูล	 SC-SI
    
    623021048-3	นางสาวทอฝัน พงษ์พิเดช	 SC-SI
    
# สารบัญเนื้อหา
# บทที่ 1
  *  [introduction](https://github.com/chalarm1405/DWDM21_/blob/main/HW_1) 
     * นิยามของ Data Mining
     * ทำไมจึงต้องมี Data Mining
     * ประเภทข้อมูลที่ใช้ทำเหมืองข้อมูล
     * ขั้นตอนการสกัดสารสนเทศ
 
# บทที่2
* introduction
     * นิยามของ Data Mining
     * ทำไมจึงต้องมี Data Mining
     * ขั้นตอนการสกัดสารสนเทศ
     * เทคนิคในการทำ Data Mining
#บทที่ 2
* ประกอบไปด้วย 3 ส่วยย่อย
  *  [Basic Python](https://github.com/chalarm1405/DWDM21_/blob/main/DATA101_(chapter2).ipynb) 
     * Data Structure โครงสร้างของข้อมูล
     * list slicing 
     * Condition ( if satatement )
     * Quize and Home work  
  *  [Mount G Driv](https://github.com/chalarm1405/DWDM21_/blob/main/Data102_(Chapter2).ipynb) 
     * คำสั่ง .head() .tail()
       * Nan = not a Number (ช่องว่าง)  
       * Box plot
       * Time Series Plot
  *  [Data Visualization](https://github.com/chalarm1405/DWDM21_/blob/main/Data_Visualization.ipynb) 
       * Box plot

       * Scatter plot

       * Plot

       * Bar chart ประกอบด้วย
         * Grouped Barchart
         * Stacked Barchart  

       * Histogram  
   * [Distance Numpy](https://github.com/chalarm1405/DWDM21_/blob/main/Distance_Numpy.ipynb) 
       *  Numpy Array
         * สร้าง Numpy Array (Matrix)
         * สร้าง matrix เริ่มต้น (zeros, ones)
         * สร้าง matrix random
       *  Indexing & Slicing ( Index - ชี้, Slice - ตัด ) 
       *  Useful Function
       *  วนลูปเอง
          * Summation
       * QUIZE
       * Distance Matrix
         * Euclidean Distance (L2-norm)
         * Distance function
         * Manhattan Distance (L1-norm)¶
       * quiz6
       * การบ้านครั้งที่ 11
       
# บทที่ 3
 *  [Basic Python](https://github.com/chalarm1405/DWDM21_/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
       * Meta Data (Data ที่ใช้อธิบาย Data)
          * ชี้ข้อมูลในตาราง 
          * ชี้แบบ .iloc[] (มองข้อมูลแบบ matrix)
       * Missing Values
         * Handling Misiing Value 1 (ลบค่า missing ออกไป)
         * Quiz 3
         * เฉลยตามอาจารย์
         * Handling Misiing Value 1.5 (ลบค่า missing เฉพาะในคอลัมม์ที่เราสนใจออกไป)
         * Quiz 3.1
         * Handling Misiing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
         * Handling Misiing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม))
         * Handling Misiing Value 4 (แทนค่าด้วย ค่ากลาง)
         * ถ้าเป็น morminal (ตัวหนังสือ) จะใช้ฐานนิยม
         * เติมด้วยช่องว่าง column ใกล้เคียง
         * Handling Misiing Value 5 (แทนค่าด้วย ค่ากลางของ sample ใน class เดียวกัน)
       * Select data by values [PD] คำสั่งแพนด้า
         * นำ list ของ boolen มาเลือกในตาราง
         * สร้าง list ของ boolen
       * Quiz 4 + การบ้าน¶
       * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน) (ต่อ)
         * เติมค่า missing ให้ จังหวัดก่อน
         * หาจังหวัดทั้งหมด
       * การเรียงข้อมูล [PD]
       * Outlier
         * ตัด outlier แบบ manual
       * Quiz 5
         * Quiz กลุ่ม ||| (แก้ไข function box_vals สามารับ input ที่ box plot วาดแบบแนวนอนได้)
         * เฉลย
       * การรวมตาราง (ต่อตารางในแนวแกน x) Data Integration
       * การบ้าน + ควิซ
# บทที่ 4
 *  [Data Warehousing and On-line Anaalytical Processing](https://github.com/chalarm1405/DWDM21_/blob/main/Chapter_4.ipynb)
       * Basic Data Warehouse
         * อะไรคือคลังข้อมูล
         * วัตถุประสงค์
         * การบูรณาการ
       * Data Cube and OLAP
         * OLTP vs. OLAP
         * Data Cubes
         * Conceptual Modeling of Data Warehouse
       * การออกแบบ และการใช้งานคลังข้อมูล
       * ความสำคัญของคลังข้อมูล

# บทที่ 5
   * [Association Rules](https://github.com/chalarm1405/DWDM21_/blob/main/Chapter_6_Association_Rules.ipynb)
     * esic Concepts
       * ลบ records ที่ถูก cancel ออกไป 
       * K-itemsets
       * Plot graph of Itemsets
       * Frequence Itemsets to Association Rule
     * Efficient Pattern Mining Methods
       * Apriori
       * (Quiz7) หา k-itemset ที่มีความน่าสนใจ  
# บทที่ 6
   * [Desition Tree](https://github.com/chalarm1405/DWDM21_/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
     * Load Data
     * Train Model
       * import
       * Define
       * train
     * plot tree
       * Evaluation
       * Random
     * Advanced Tree 
       * Import
       * Define
       * train
       * TEST
       * Train - Test
       * Train - Validation
     * HW
       * 1.ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
       * 2.ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
       * 3.ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
       * 4.ต้นไม้ที่ใช้เกณฑ์ entropy มีใบไม่เกิน 40 ใบ
   * [KNN](https://github.com/chalarm1405/DWDM21_/blob/main/Chap7_Classification_(KNN_NN).ipynb)
     * Load data
     * Split Data
     * Train Model
       * Import
       * knn1 , knn2 , knn3
       * Retrain & Evaluate
       * Neural Network
   * [Evaluation](https://github.com/chalarm1405/DWDM21_/blob/main/Chap7_Classification_(Evaluation).ipynb)  
     * Split Data
     * สร้าง Model ทำนาย
     * Evaluation
# บทที่ 7
  * [Clustering](https://github.com/chalarm1405/DWDM21_/blob/main/Chap8_Clustering.ipynb)
     * K-means
     * Generate Data
     * Explore data
     * Clustering
     * Example Application
  
# Project
 * [Project](https://github.com/chalarm1405/DWDM21_/blob/main/Project%20for%20Group.ipynb)
     * การนำเข้าข้อมูล , แหล่งที่มาข้อมูล
     * ดูว่าข้อมูลมี data missing
       * สรุปข้อมูลเป็นรายคอลลัมม์ว่ามี missing
       * Drop missing value
       * ตรวสจสอบเมื่อลบออกไปแล้วตรวจสอบว่ายังไม่ข้อมูลที่หายไปหรือไม่
       * Percent of missing data from dropna
     * รวมตาราง
       * ตรวจสอบดูการลบข้อมูลที่ซ้ำกัน
     * Data Mining
       * สร้างตารางที่ใช้ในการดู challenge
       * สร้างตารางที่ค่าเฉลี่ยนประชากรมากกว่า 40
       * แปลงให้ข้อมูลอยู่ในรูปแบบเป็น transaction
     * apyori
       * ขั้นตอนติดตั้ง apyori
       * เป็นการเรียกใช้ฟังก์ชัน apriori
       * ผลลัพธ์ที่ได้จากการทำ Associantion ซึ่งรายละเอียดจะอยู่ที่ summary
       * SUMMARY
       * Plot กราฟ เพื่อดุค่าของข้อมูลผลเฉลี่ยในแต่ละจังหวัด
     * Classification
       * ทำการดูว่าประเภทของระบบใดในแต่ละภาคมีการใช้มากสุด
       * กำหนดค่า X และ Y
       * Decision Tree
       * KNN
       * Neural Network
       * วาดกราฟต้นไม้
     * Visulization
         
             
         
         
