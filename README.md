### Cài đặt Windows cho Ubuntu Debian Linux cực hay và dễ với Github Actions 🍎


# Cách sử dụng:

+ **Fork trang này về, vào Settings, chọn actions, nhấn runner, add self hosted runner, chọn hệ điều hành bạn cần. Sao chép các lệnh và bỏ vào Windows Powershell quyền Administrator, Ubuntu, Debian Terminal với Sudo Root Access, sau đó chạy** 😻

+ **Để biết chắc rằng Linux của bạn có hỗ trợ KVM, hãy chạy lệnh sau:**
```
sudo apt update && sudo apt install cpu-checker -y && sudo kvm-ok
```
+ **Nếu đầu ra là Support thì có thể dùng, nếu Not Supported thì sẽ không thể dùng***
