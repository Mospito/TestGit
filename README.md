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
