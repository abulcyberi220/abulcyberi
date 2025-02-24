# abulcyberi.sh

آخرین و به روزترین صفحات ورود به سیستم.
دوستانه مبتدیان
چندین گزینه تونل زنی
لوکال هاست
ابری
LocalXpose
پشتیبانی از URL ماسک
پشتیبانی داکر
نصب و راه اندازی
فقط، این مخزن را شبیه سازی کنید -

git clone --depth=1 https://github.com/abulcyberi220/abulcyberi.git
حالا به دایرکتوری کلون شده و اجرا کنید abulcyberi.sh-

$ cd abulcyberi
$ bash abulcyberi.sh
در اولین راه اندازی، وابستگی ها را نصب می کند و تمام abulcyberi نصب شده است.

نصب (Termux)
با استفاده از tur-repo می توانید abulcyberi را به راحتی در Termux نصب کنید

$ pkg install tur-repo
$ pkg install abulcyberi
$ abulcyberi
یک نکته: Termux
از هک کردن جلوگیری می کند . بنابراین هرگز در مورد چیزی که مربوط به abulcyberi است در هیچ یک از گروه های بحث termux بحث نکنید. برای اطلاعات بیشتر به ویکی مراجعه کنید

اگر از termux استفاده کنید، آن را دانلود کنید*_termux.deb

.debfail را با اجرا نصب کنید

apt install
یا

$ dpkg -i
$ apt install -f
روی داکر اجرا کنید
آینه تصویر داکر:

داکر هاب :
docker pull abulcyberi220/abulcyberi
GHCR :
docker pull ghcr.io/abulcyberi220/abulcyberi:latest
با استفاده از اسکریپت wrapper run-docker.sh

$ curl -LO https://raw.githubusercontent.com/htr-tech/zphisher/master/run-docker.sh
$ bash run-docker.sh
کانتینر موقت

docker run --rm -ti htrtech/zphisher
به یاد داشته باشید که دایرکتوری را نصب کنید
