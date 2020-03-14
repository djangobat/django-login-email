# Tùy chỉnh đăng nhập bằng email

Xem chi tiết bài viết tại [Cách tùy chỉnh đăng nhập bằng email](https://djangobat.com/blog/cach-tuy-chinh-ang-nhap-bang-email/)


## Cài đặt

Đầu tiên, tải repository về máy tính:

```bash
git clone http://github.com/djangobat/django-login-email.git
```

Cài đặt requirements:

```bash
cd django-login-email
pip install -r requirements.txt
```

Tạo database:

```bash
python manage.py makemigrations users
python manage.py migrate
```

Chạy development server:

```bash
python manage.py runserver
```

Mở Chrome hay FireFox : **127.0.0.1:8000**



