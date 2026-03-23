# BSC_DPDM2025
## Data Preparation and Data Mining 

Boonyarat Senjan 663020036-9
### **รายละเอียดรายวิชา**  
รายวิชานี้มุ่งเน้นให้ผู้เรียนเข้าใจพื้นฐานและเทคนิคในการเตรียมข้อมูลก่อนการวิเคราะห์ขั้นสูง ผ่านการเรียนรู้เครื่องมือและอัลกอริทึมที่เกี่ยวข้องกับ Data Mining  

> **หน่วยกิต:** 3 (1-4-7)  
> **อาจารย์:** ผศ.ดร.ธนพงศ์ อินทระ

---

## **แผนการประเมินผล**

| **ส่วนงาน**    | **รายละเอียด**                              | **น้ำหนักคะแนน** |
|----------------|--------------------------------------------|-------------------|
| **Midterm**    | Data Preprocessing (รายบุคคล)              | 25%               |
| **Final**      | ทฤษฎี Data Mining (รายบุคคล)               | 25%               |
| **Project**    | ผสาน Data Preprocessing + Data Mining (กลุ่ม)| 20%               |
| **Homework**   | งานแบ่งกลุ่ม/งานใหม่                        | 15%               |
| **Quiz**       | ถาม-ตอบในชั้นเรียน                         | 10%                |
| **GitHub**     | README                                       | 5%                |
| **Total**      |                                            | 100%              |

---

## 📚 **สารบัญ**

- [ บทที่ 1: Introduction — Data Mining](#บทที่-1-introduction--data-mining)
- [ บทที่ 2: Getting to Know Your Data](#บทที่-2-getting-to-know-your-data)
- [ บทที่ 3: Data Preprocessing](#chapter-3-data-preprocessing)
- [ บทที่ 6: Mining Frequent Patterns & Associations](#chapter-6-mining-frequent-patterns-association-and-correlations)
- [ บทที่ 8: Classification – Basic Concepts](#chapter-8-classification-basic-concepts)
- [ บทที่ 9: Classification – Advanced Methods](#chapter-9-classification-advanced-methods)
- [ บทที่ 10: Cluster Analysis – Basic Concepts and Methods](#chapter-10-cluster-analysis-basic-concepts-and-methods)
- [ สอบกลางภาค: Rainfall Data Preprocessing](#-midterm-rainfall-data-preprocessing)
- [ โครงงาน: Rainfall Prediction Model Comparison](#-project-rainfall-prediction-model-comparison)

---

## **ภาพรวมบทเรียน**
---

## บทที่ 1: Introduction — Data Mining

เนื้อหาประกอบไปด้วย ความหมายและความสำคัญของ Data Mining ว่าทำไมต้องวิเคราะห์ข้อมูลขนาดใหญ่ รวมถึงแนวคิดหลักและมุมมองหลายมิติของการค้นหาความรู้จากข้อมูล นอกจากนี้ยังทำความเข้าใจกระบวนการ KDD ประเภทของข้อมูลที่ใช้ได้ รูปแบบความรู้ที่ค้นพบได้ และเทคนิคหรือเทคโนโลยีที่สนับสนุน ตลอดจนตัวอย่างงานประยุกต์ที่ Data Mining ถูกนำไปใช้จริงในชีวิตประจำวัน

- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/121fbe5094aafae9ad4cfaef84e18ad29090261f/01Intro%202.pdf)


---

## บทที่ 2: Getting to Know Your Data

เรียนรู้ลักษณะต่าง ๆ ของข้อมูล ตั้งแต่ประเภทของ Data Objects และ Attribute Types รวมถึงสถิติเบื้องต้นที่ใช้ทำความเข้าใจการกระจายและความแปรปรวนของข้อมูล นอกจากนี้ยังครอบคลุมเทคนิคการทำ Data Visualization และวิธีวัดความเหมือน/ความต่างของข้อมูล ซึ่งเป็นพื้นฐานสำคัญก่อนนำข้อมูลไปทำ Data Mining ขั้นต่อไป

- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/02Data.pdf)

---

<a name="chapter-3-data-preprocessing"></a>
## **บทที่ 3: Data Preprocessing**  
เรียนรู้เทคนิคการเตรียมข้อมูลให้พร้อมสำหรับการวิเคราะห์ ประกอบด้วยการทำความสะอาดข้อมูล การแปลงข้อมูล และการปรับมาตรฐานข้อมูล
- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/03Preprocessing.pdf)  
- **ตัวอย่างการปฏิบัติ:** 
  - [Data Preprocessing CODE](https://github.com/aoonging/BSC_DPDM2025/blob/e9df967a0d9ca02301fc1310999e61ec441e72bb/Ch3_Data_Preprocessing.ipynb) - เทคนิคการเตรียมข้อมูลพื้นฐาน
  - [PCA CODE](https://github.com/aoonging/BSC_DPDM2025/blob/main/Ch3_dimensionality_reduction_PCA.ipynb) - การลดมิติข้อมูลด้วยเทคนิค PCA

---

<a name="chapter-6-mining-frequent-patterns-association-and-correlations"></a>
## **บทที่ 6: Mining Frequent Patterns & Associations**  
เรียนรู้การค้นหารูปแบบและความสัมพันธ์ที่เกิดขึ้นบ่อยในข้อมูล ด้วยเทคนิค Association Rule Mining
- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/06FPBasic.pdf)  
- **ตัวอย่างการปฏิบัติ:** [CODE](https://github.com/aoonging/BSC_DPDM2025/blob/a39b8e69e862cf2ac5d05a88f43f8ca78629809b/Ch4_Frequent_Patterns_(Association_Rules).ipynb) 

#### **HW4 – งานกลุ่ม: วิเคราะห์การนักแสดงร่วมกับประเภทของหนัง รวมไปถึง rating ที่ได้รับ**  
**โจทย์:**  
1.  วิเคราะห์ว่านักแสดงคนไหนที่มักจะพบว่าเล่นหนังด้วยกัน
2.  วิเคราะห์นักแสดงคนไหนเล่นหนังประเภทไหนเฉพาะหนังที่ได้ rating Good/Excellent

- **นำเสนอ:** [ HW4 Presentation](https://www.canva.com/design/DAHAIu-27wA/JNl3RrqI0YX9M_q8EChv6A/edit?utm_content=DAHAIu-27wA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) - สไลด์สรุปผลการวิเคราะห์  
- **โค้ด:** [HW3 Code](https://github.com/aoonging/BSC_DPDM2025/commit/a715da3287d2f7d71a348b237474970a43e3d096) 


---

<a name="chapter-8-classification-basic-concepts"></a>
## **บทที่ 8: Classification – Basic Concepts**  
เรียนรู้พื้นฐานของการจำแนกประเภทข้อมูล เทคนิคการสร้างโมเดล และวิธีการประเมินประสิทธิภาพ
- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/08ClassBasic.pdf)
- **ตัวอย่างการปฏิบัติ:** [CODE](https://github.com/aoonging/BSC_DPDM2025/blob/03a8a1c4127128af6406b5de210542f7d586e200/ch5_classification.ipynb)
  
- **Quiz9 :** [📄 Quiz9](https://github.com/aoonging/BSC_DPDM2025/blob/main/Quiz9.pdf)
- **Quiz11 :** [Code Quiz11](https://github.com/aoonging/BSC_DPDM2025/blob/main/Ch5_Classification.ipynb)
- **Quiz12 :** [📄 Quiz12](https://github.com/aoonging/BSC_DPDM2025/blob/main/Test12.jpg)

---

<a name="chapter-9-classification-advanced-methods"></a>
## **บทที่ 9: Classification – Advanced Methods**  
เรียนรู้เทคนิคการจำแนกประเภทข้อมูลขั้นสูง เช่น Random Forest, Support Vector Machines, Neural Networks
- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/09ClassAdvanced.pdf)

---

<a name="chapter-10-cluster-analysis-basic-concepts-and-methods"></a>
## **บทที่ 10: Cluster Analysis – Basic Concepts and Methods**  
เรียนรู้พื้นฐานการวิเคราะห์กลุ่มข้อมูล เพื่อจัดกลุ่มข้อมูลที่มีความคล้ายคลึงกันโดยไม่ต้องมีข้อมูลฝึกสอน
- **เอกสารประกอบการสอน:** [📄 ดาวน์โหลด PDF](https://github.com/aoonging/BSC_DPDM2025/blob/main/10ClusBasic.pdf)  
- **ANN Tutorial:** [📄 เอกสาร ANN](https://github.com/aoonging/BSC_DPDM2025/blob/main/AI%20%E0%B8%9A%E0%B8%B8%E0%B8%8D%E0%B9%80%E0%B8%AA%E0%B8%A3%E0%B8%B4%E0%B8%A1.pdf)  
  > **หมายเหตุ:** ศึกษาเรื่อง Perceptron Learning ที่หน้า 169 ในเอกสาร

---

## 📝 Midterm: Rainfall Data Preprocessing
- **โค้ด:** [💻 Midterm Code](https://github.com/aoonging/BSC_DPDM2025/blob/23e90a40a14da3a0a5897de323281feed5b03414/Midterm_663020036_9.ipynb) - โค้ดที่ใช้ในการวิเคราะห์

### 📌 สรุปขั้นตอน
- รวมข้อมูลหลายไฟล์ → สร้าง dataset
- คัดเลือกสถานีที่ใช้
- ตรวจสอบ missing (record ที่หายจริง)
- ตัดสถานีที่ missing ≥ 20%
- เติมข้อมูลด้วย Median (อิงฤดูกาล)
- สรุปผลเป็นปริมาณน้ำฝนรายเดือน

---

## 📝 Project: Rainfall Prediction Model Comparison  
**กลุ่ม: มะฮะมู้ด**
- **โค้ด:** [PROJECT Code](https://colab.research.google.com/github/aoonging/BSC_DPDM2025/blob/main/Group7_RadiusNeighborsRegressor.ipynb#scrollTo=9IPULvU3HSub)
- **CANVA:** [CANVA PROJECT](https://www.canva.com/design/DAHDnt_fSps/FefjToG3Nnj9gNM1Lbu7aA/edit?utm_content=DAHDnt_fSps&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
  
### **โจทย์**
เปรียบเทียบโมเดลพยากรณ์ปริมาณน้ำฝน เพื่อหาโมเดลที่มีประสิทธิภาพดีที่สุด

### **โมเดลที่ใช้**
- LSTM  
- RandomForestRegressor  
- RegressorChain  
- RNR (Radius Neighbors Regressor)  

### **แนวทางการทำงาน**
- ใช้ข้อมูลย้อนหลัง (window) เพื่อพยากรณ์ล่วงหน้า (horizon)  
- ใช้ข้อมูลปริมาณน้ำฝนหลายสถานีร่วมกับตัวแปรสภาพอากาศ  
- แบ่งข้อมูลแบบ Time Series (Train / Validation / Test)  

### **ผลลัพธ์**
- เปรียบเทียบประสิทธิภาพของแต่ละโมเดล  
- บันทึกผลลัพธ์เป็น CSV และแสดงกราฟค่าจริงเทียบค่าทำนาย  

### **สรุป**
โมเดลให้ผลลัพธ์แตกต่างกัน โดยเลือกโมเดลที่ดีที่สุดจากค่า MSE, R² และ Accuracy เพื่อใช้พยากรณ์ในอนาคต

---
