# Git cơ bản
1.	Git config:  git config -- global user.name = ”  ”
git config -- global user.email = ”  ”

2.	Git init : Tạo thư mục dự án:  git init trong thư mục gốc của dự án
3.	Git clone: copy từ thư mục dự án gốc về: git clone url_thumuc
4.	Git status: kiểm tra trạng thái commit, các thay đổi.
5.	Git add: thêm các mục trong thư mục.
6.	Git commit: git commit -m “message” – đẩy code lên nhưng không chia sẽ với ai.
7.	Git push/pull: đẩy code lên remote branch:
git pull remote_name branch_name  and git push remote_name branch_name;
ghi đè: git push remote_name branch_name -f;
8.	Xóa local branch: git branch -D branch/name
9.	Xóa remote branch: git push remote_name branch_nam –delete
10.	Thay đổi url của remote: git remote set-url remote_name url_remote;
11.	Thay đổi tên remote: git remote rename old_name new_name;
12.	Xóa remote: git remote remove remote_name
13.	Git branch: liệt kê các nhánh: git branch hoặc git branch -a
14.	Git checkout: Chuyển sang nhánh(branch) khác: 
git checkout <: branch:>
hoặc ** _ git checkout -b <: branch:> nếu muốn tạo và chuyển sang một nhánh mới.
15.	Git stash: lưu thay đổi nhưng chưa muốn commit
16.	Git merge: Nhóm 2 nhánh lại với nhau
Chuyển tới branch muốn merge rồi  dùng git merge <:branch _muon_merge:>
17.	Git reset: Bỏ commit một tệp trong thư mục git reset HEAD tên_file
18.	Git remote: kiểm tra remote hiện có: git remote -v; thêm remove: git add remote url_remove;
19.	Git add ten_file; Git add all: thêm các mục vào phần thư mục tổ chức
20.	So sánh thay đổi trước và sau commit: git diff.
21.	Gộp 3 commit gần nhất làm 1: git rebase -I HEAD~3;
Sửa “Pick” thành ‘s’ để gộp, ‘Pick’ thành ‘d’ để xóa commit, Ctrl+O, Enter.


(Bản ngày 30/6 chưa thêm)