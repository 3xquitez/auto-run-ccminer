# AUTO RUN CCMINER IN TERMUX

## การติดตั้งแบบรวดเร็ว
```
apt-get update -y && apt-get install git -y && git clone https://github.com/mantvmass/auto-run-ccminer && cd auto-run-ccminer && chmod +x setup.sh && sh setup.sh
```

## การติดตั้งตามขั้นตอน
```
apt-get update -y
```
```
apt-get install git -y
```
```
git clone https://github.com/mantvmass/auto-run-ccminer
```
```
cd auto-run-ccminer
```
```
chmod +x setup.sh && sh setup.sh
```
* หลังจากเปิดไฟล์ bash.bashrc เพิ่มบรรทัดแรกเป็น
- ```run-miner```
* แล้ว save

## เพิ่มเติมการใช้โปรแกรม
* หากต้องการหยุดขุดให้ใช้กด ```CTRL + C```
* หากต้องการเปลี่ยน TAG ใช้คำสั่ง ```edit-miner```
* หากต้องการเปิดขุด ใช้คำสั่ง ```run-miner```
