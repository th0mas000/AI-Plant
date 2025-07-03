# 🌿 PlantAI - Image Classification of Plant Leaves

PlantAI เป็นโปรเจกต์จำแนกประเภทของใบพืชโดยใช้ Deep Learning ด้วย TensorFlow/Keras โมเดลนี้ถูกฝึกจากชุดข้อมูลภาพใบพืชหลากหลายประเภทเพื่อให้สามารถทำนายประเภทของพืชได้จากภาพ

## 🧠 Model
- ใช้ Keras Sequential API

- ## 🛠️ ไลบรารีที่ใช้
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL

โครงสร้าง <br>
![Image Alt](https://github.com/th0mas000/AI-Plant/blob/75055e18d3f1a3c4cb8f805e14af1e2beca9cfa5/path_example1.png)

หากจะต้องการเปลี่ยน model ที่จะ train เป็นอย่างอื่น ก็จัดการ folder ใน training ได้เลย

ตัวอย่างจำแนกประเภท ขวดแก้ว - ขวดพาสติก - กระป๋อง<br>
![Image Alt](https://github.com/th0mas000/AI-Plant/blob/75055e18d3f1a3c4cb8f805e14af1e2beca9cfa5/path_example2.png)



และแก้ไข num_classes และ class_names ให้สอดคล้องกับภาพที่ต้องการจำแนง

## 🚀 การใช้งาน
1. เตรียม Dataset ให้ตรงโครงสร้าง
2. รัน notebook เพื่อฝึกโมเดล
3. ใช้ model ทำนายภาพได้เลย!!


