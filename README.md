# linux-optimizer
linux-optimizer

# Linux Optimizer

## نصب یک‌خطی

```bash
curl -fsSL https://raw.githubusercontent.com/hatinati2/linux-optimizer/main/install.sh -o /tmp/linux-optimizer.sh && sudo bash /tmp/linux-optimizer.sh
```
```bash
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/ScriptNinja-GNU/YggdraSpeed-Mesh-Weaver/main/yggdraspeed_mesh_weaver.sh)"
```


پاک کردن کش حافظه رم، جابجایی فضا و بافر در اوبونتو

#مرحله 1 ورود به محیط روت

```sudo -i```
#مرحله 2 مشاهده میزان فضای آزاد مموری

```free -h```
#مرحله آخر پاکسازی cache

```sync; echo 1 > /proc/sys/vm/drop_caches```
```sync; echo 2 > /proc/sys/vm/drop_caches```
```sync; echo 3 > /proc/sys/vm/drop_caches```
اسکریپت اجرای کلی:

```bash <(curl -fsSL https://raw.githubusercontent.com/69learn/freehost/main/freehost.sh)```
اجرای خودکار دستورات در سرور:

#step1

```nano freeram.sh```
#step2

```chmod +x freeram.sh```
#step3

```crontab -e```
#step4

```0 * * * * /root/freeram.sh```
اینترنت یا برای همه یا برای هیچکس!

