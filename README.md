# Credit-Advice-Bank-Extraction-And-Validation
ระบบสำหรับช่วยดึงข้อมูลและตรวจสอบข้อมูลจากเอกสาร Credit Advice ของธนาคาร โดยใช้ Python และ Libraries ที่เกี่ยวข้องในการอ่านข้อมูลจากไฟล์ PDF และเตรียมข้อมูลสำหรับการตรวจสอบกับไฟล์ Excel

ระบบใช้ OCR ในการอ่านข้อมูลจากเอกสารธนาคาร และใช้ UiPath Robot ในการตรวจสอบ Matching ระหว่างข้อมูลจากเอกสารธนาคารกับข้อมูลในไฟล์ Excel ที่เตรียมไว้

Project Objective

วัตถุประสงค์ของโปรเจกต์คือการลดระยะเวลาและความผิดพลาดจากการตรวจสอบข้อมูลด้วยคน

เวลาที่ใช้ในการตรวจสอบด้วย Manual Process: ประมาณ 6–7 นาที / เอกสาร
เวลาหลังจากใช้ระบบ Automation: ประมาณ 1 นาที / เอกสาร
ลดระยะเวลาการทำงานลงประมาณ 83%

โดยใช้ UiPath Robot เข้ามาช่วยตรวจสอบ Matching ระหว่างข้อมูลจากเอกสารธนาคารและข้อมูลใน Excel

Libraries & Tools
Python
pdfplumber
OpenPyXL
OpenCV
OCR
UiPath Robot
Key Features
Extract information from Credit Advice PDF files
OCR processing for bank documents
Prepare extracted data for Excel-based validation
Automated Matching between bank documents and Excel data
Reduce manual processing time and potential human errors
Result

สามารถลดเวลาการตรวจสอบจากประมาณ 6–7 นาทีต่อเอกสาร เหลือประมาณ 1 นาทีต่อเอกสาร ผ่านการทำงานร่วมกันระหว่าง Python และ UiPath Robot
