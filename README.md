สคริปสำหรับติดตั้ง Odoo 8 / OpenERP
=======================

สำหรับผู้ใช้งาน Ubuntu Server เวอร์ชั่น 14.04

!! คำแนะนำเบื้องต้น !!

1.เหมาะสำหรับผู้เริ่มต้นเนื่องจากทำเพียงขั้นตอนง่ายๆ ก็สามารถติดตั้งได้อย่างสะดวก
2.เครื่อง Server ของคุณต้องเชื่อมต่ออินเตอร์เน็ต
3.ปัจจุปันมี VPS ให้ใช้งานอยู่มากมายในที่นี้ขอแนะนำ Digital Ocean ซึ่งตอนนี้มี VPS Server อยู่ที่สิงคโปรค์และราคาถูกมาก เริ่มต้นเดือนละ 5$ หรือ 300 กว่าบาท/เดือนเท่านั้น (ถูกกว่าเมืองไทยมาก) และได้ความเร็วใกล้เคียงกับเมืองไทย

ก็อบปี้ ลิ้งค์นี้เพื่อสมัครและรับฟรี 10$ ใช้งานฟรี 2 เดือน https://www.digitalocean.com/?refcode=ea909e9c0fc9
4.ติดตั้ง openssh และ login ให้เรียบร้อย
===========================

วิธีการติดตั้งให้ทำตามคำสั่งต่อไปนี้
1.เพื่ออัพเดทระบบให้เป็นปัจจุบัน

sudo apt-get update
sudo apt-get -y upgrade

2.ติดตั้ง git

sudo apt-get install git

3.ดาวน์โหลด script ไปยัง server

cd
git clone https://github.com/guitarstyle/odoo8-Thai-install-ubuntu-14.04.git

4.เข้าไปยัง ไดเรคทอรี่   odoo8-Thai-install-ubuntu-14.04

cd odoo8-Thai-install-ubuntu-14.04/odoo-v8/ubuntu-14-04/
sudo chmod +x odoo_install.sh
sudo ./odoo_install.sh

5. รอจนเสร็จสิ้นการติดตั้ง
