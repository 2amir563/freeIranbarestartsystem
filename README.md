# freeIranbarestartsystem
اینجا اومد اسکریپت فری ایران را با اسکریپت ریستارت سیستم در هر زمانی به صورت دوره ای ترکیب کردم
یعنی دوتا گیتهاب زیر را باهم ترکیب کردم

https://github.com/amir198665/FreeIRAN


https://github.com/2amir563/restart-at-moultitime/tree/main

برای اجرای این اسکریپت فقط کافی است کد زیر را بزنیم


```
curl -O https://raw.githubusercontent.com/2amir563/freeIranbarestartsystem/refs/heads/main/FreeIRAN.sh && chmod +x FreeIRAN.sh && sed -i -e 's/\r$//' FreeIRAN.sh && sudo apt update && sudo apt install -y dialog && ./FreeIRAN.sh
```

برای اجرای دوباره فقط کافی است کد زیر را بزنیم


```
./FreeIRAN.sh

```

