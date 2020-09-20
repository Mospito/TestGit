# TestGit
#ฝึกหัดการใช้งานกิต
# Git Config
- git config --global user.name "yourname"
- git config --global user.email "yourEmail"
# git remote
- git git remote add origin [URL] : ใน URL จะใส่ HTTPS หรือ SSH แล้วแต่เรา
- git remote remove origin : ลบ remote origin
- git remote -v : ตรวจสอบ remote
# SSH key
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com" 
- cat ~/.ssh/id_rsa.pub
- เอา ssh key ที่ได้ไปใส่ใน setting บน github
# Clone git
- ถ้าหาก clone Git มา แล้วใช้คำสั่ง yarn start ไม่ได้ ให้ทำการติดตั้ง npm โดยใช้คำสั่ง npm install
- ถ้าใช้คำสั่ง yarn start / npm start ไม่ได้ ให้ทำการ add react เข้าไปก่อนโดยคำสั่ง yarn add react-scripts
# Git push
- ถ้ามี Err ขึ้นจากที่ใช้งาน Git push -u origin master ให้ลองใช้เป็น Git push -f origin master
# การลบ Remote Origin
- git remote romove origin หรือ git remote rm origin 
# การดู remote ที่เชื่อมต่ออยู่
- git remote -v 
# การลบ User and Email 
- git config --global --edit  แล้วกด insert แล้วกด Esc และพิมพ์ :wq แล้วกดปุ่ม Enter 
# การ อัพขึ้น firebase
- firebase login
- firebase init
- firebase deploy
