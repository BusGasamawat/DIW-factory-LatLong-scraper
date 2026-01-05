# DIW-factory-LatLong-scraper

**วัตถุประสงค์ของโปรแกรมสร้างขึ้นเพื่อการวิจัยและเพื่อการศึกษาเท่านั้น**
\
\
โปรแกรมนี้เป็นโปรแกรมเพื่อดึงข้อมูลตำแหน่งที่ตั้งโรงงาน (latitude & longitude) โดยค้นหาโรงงานตามตามประเภทโรงงานหลัก (ดังที่ปรากฎในเว็บ https://www.diw.go.th/datahawk/factype.php) พร้อมทั้งระบุเลขทะเบียนโรงงาน (fac_id) และชื่อโรงงาน (fac_name) จากข้อมูลในเว็บไซต์กรมโรงงานอุตสาหกรรม (https://www.diw.go.th/webdiw/search-factory/) จากนั้นจึงบันทึกข้อมูลที่ได้ลงไฟล์ Microsoft Excel
\
\
โปรแกรมเขียนใน Jupyter Notebook ด้วยภาษา Python ทำงานด้วยการดึง hyperlink ทั้งหมดทีละหน้าเว็บของผลการสืบค้นข้อมูล หลังจากนั้นจึงดึงข้อมูลโรงงานผ่าน hyperlink แต่ละอันลง list แล้วจึงบันทึกลง DataFrame ก่อนจะ export สู่ไฟล์ excel

เนื่องจากไม่ใช่ทุกโรงงานจะมีตำแหน่งที่ตั้งในรูปแบบ hyperlink ดังนั้นข้อมูลที่เก็บได้ส่วนใหญ่จะเป็นโรงงานขนาดกลาง-ใหญ่

\
*ตัวอย่างโรงงานที่สามารถเก็บข้อมูลได้*

![Image](https://github.com/user-attachments/assets/e1a35b00-a271-4468-b91b-4d89d899d7e9)

*ตัวอย่างหน้าเว็บที่เก็บข้อมูล*

![Image](https://github.com/user-attachments/assets/930d9304-d4f1-45d9-8adf-cd8f81f84fa4)

*ตัวอย่างข้อมูลที่ได้ในไฟล์ excel*

<img width="889" height="165" alt="Image" src="https://github.com/user-attachments/assets/e69a49ad-e08a-40a5-be2d-3ac6eeef7630" />







