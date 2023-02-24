# leet-solutions
Solutions to some easy leetcode challenges. This repo is also used to learn about git

## Sử dụng git cơ bản

### Các câu lệnh sau đây dùng để chạy trên terminal

Để clone repo này về máy, sử dụng lệnh
```bash
git clone https://github.com/longieee/leet-solutions.git
```

Để xem mình đang ở branch nào:
```bash
git branch
```
Output của câu lệnh trên sẽ trông như sau
```bash
* develop
  experiments/testing
  branch-1
  branch-2
  main
```
Branch có dấu `*` là branch hiện tại của mình
Mỗi repo sẽ có một branch default. Đối với repo này, tên của branch default đó là `main`

Để đổi sang một branch khác:
```bash
git checkout {tên branch muốn đổi sang}
```

Tại local, sau khi clone repo về, có thể tạo một branch mới bằng cách:
```bash
git checkout -b {tên của branch mới}
```

Một branch có thể chứa code cũ hơn so với `origin` (tên gọi của cái chỗ trên github mà mình kéo code về). Để cập nhật branch tại local up-to-date với origin, dùng lệnh
```bash
git pull
```

Khi mình có thay đổi trên một branch muốn đẩy lên trên origin, trước tiên checkout vào branch đó trên local, sau đó sử dụng lệnh:
```bash
git push -u origin {tên branch muốn đẩy lên}
```

Tham khảo thêm các câu lệnh khác tại đây: https://education.github.com/git-cheat-sheet-education.pdf
