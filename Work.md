# Upgrading Ubuntu

command             |    mean
-----------------   |    --------------------------------------------------------------------------------
sudo apt update     |    ปรับปรุงและอัพเดทแหล่งซอฟต์แวร์และการตรวจสอบเวอร์ชั่นใหม่ของ Packages
sudo apt upgrade    |    อัพเกรดโปรแกรมทั้งหมดในระบบของเรา ซึ่งจะปรับปรุงให้เป็นเวอร์ชั่นใหม่ล่าสุด
sudo apt dist-upgrade    |   ดาวน์โหลดและติดตั้ง Packages เหล่านั้น และลบ Packages ที่ล้าสมัยออกด้วย
sudo apt autoremove    |    ลบ Packages ที่ไม่จำเป็นต้องใช้ทั้งหมด
sudo apt install update-manager-core    |    ติดตั้ง update manager core
sudo do-release-upgrade    |    จากนั้นสั่งอัพเกรดได้เลย
sudo do-release-upgrade -d    |    การเพิ่ม -d ท้ายคำสั่งเพื่อบังคับให้อัปเกรด สำหรับข้อมูลเพิ่มเติมอ่านส่วน "ไม่พบรุ่นใหม่" 


# Command-Line Interface
1.Requirement

command             |    mean
-----------------   |    --------------------------
sudo apt install tree    |    การติดตั้งโปรแกรม tree


2.Working Directory

command             |    mean
-----------------   |    --------------------------
tree    |    แสดงรายการไฟล์และโฟล์เดอร์ในรูปแบบของต้นไม้
pwd    |    แสดงตำแหน่งโฟล์เดอร์ที่ทำงานอยู่
cd    |    คำสั่งเปลี่ยนโฟล์เดอร์ทำงาน
ls    |    คำสั่งแสดงรายการไฟล์


3.Files and Folders

command              |    mean
-----------------    |    --------------------------
cp    |    คัดลอกไฟล์
mv    |    ย้ายไฟล์ไปที่ตำแหน่งใหม่
rm    |    ลบไฟล์
mkdir    |    ทำไดเรกทอรี
chmod    |    เปลี่ยนโหมด
chown    |    เปลี่ยนเจ้าของ


4.System Information

command              |    mean
-----------------    |    --------------------------
df free uname lsb_release    |    แสดงข้อมูลระบบ
ps top    |    แสดงข้อมูลกระบวนการ
ifconfig iwconfig    |    ข้อมูลเครือข่ายดิสเพลย์
lshal lshw lspci lsusb    |     แสดงข้อมูลฮาร์ดแวร์


5.Text Files

command              |    mean
-----------------    |    --------------------------
find    |    ค้นหาไฟล์
grep    |    ค้นหาเนื้อหาของไฟล์ข้อความ
sed    |    ค้นหาและแทนที่ไฟล์ข้อความ
nano    |    แก้ไขไฟล์ข้อความ
cat less more    |    แสดงเนื้อหาไฟล์


6.Users Management

command              |    mean
-----------------    |    --------------------------
who whoami groups    |    แสดงข้อมูลผู้ใช้
adduser deluser passwd usermod    |    แก้ไขผู้ใช้
addgroup delgroup    |    แก้ไขกลุ่ม


7.Helps

command              |    mean
-----------------    |    --------------------------
man apropos type where    |    คำสั่งช่วยเหลือ
arrow keys    |    อ่านคู่มือ
q    |    ออกจากคู่มือ
man -k    |    apropos
man -f    |    ค้นหาตามชื่อ



