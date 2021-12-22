step1: git init
->khởi tạo repo dưới local
step2: git checkout -b develop
->tạo nhánh mới có tên là develop
step3: commit code
- git add fileName -> Thêm từng file 1
- git add . ->Thêm tất cả các file
- git commit -m "Message"
step4: Add remote
- git remote add origin https://github.com/NightWing2110/learn-git.git
step5: Push code
- git push origin tên nhánh



=> làm xong task



Các câu lệnh git cơ bản
- git branch -d tên_nhánh ->Xóa 1 nhánh
- git checkout -b tên_nhánh ->Tạo mới 1 nhánh và chuyển sang nhánh đó
- git branch -> Xem danh sách nhánh
- git checkout tên_nhánh-> Chuyển nhánh
- git remote add tên_remote link remote  ->Thêm mới 1 remote
- git add fileName -> add 1 file 1
- git add .  ->add nhiều file cùng 1 lúc
- git commit -m "Nội dung của message" ->Commit code (Note: để commit code thì phải add trước)
- git push origin tên_nhánh -> Đẩy code lên nhánh (origin là tên remote mà chúng ta đặt)
- git pull origin tên_nhánh ->Pull code(kéo code) mới nhất của nhánh đó về local