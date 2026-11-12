# Dxconnect

Halka remote desktop tool - ek PC ki screen doosre PC, phone ya tablet se dekho
aur chalao. Same network (LAN / Wi-Fi) par chalta hai, aur Tailscale ho to
bahar se bhi. Koi server ya account nahi chahiye.

## Download

Hamesha sabse nayi version:

| Kiske liye | File |
|---|---|
| Windows | [dxconnect-windows-x86_64.exe](https://github.com/lilesh0070/dxconnect_app/releases/latest/download/dxconnect-windows-x86_64.exe) |
| Linux (PC) | [dxconnect-linux-x86_64](https://github.com/lilesh0070/dxconnect_app/releases/latest/download/dxconnect-linux-x86_64) |
| Linux (Raspberry Pi 64-bit) | [dxconnect-linux-arm64](https://github.com/lilesh0070/dxconnect_app/releases/latest/download/dxconnect-linux-arm64) |
| Android | [dxconnect-viewer.apk](https://github.com/lilesh0070/dxconnect_app/releases/latest/download/dxconnect-viewer.apk) |

Saari versions: [Releases](https://github.com/lilesh0070/dxconnect_app/releases)

App ek baar lag jaye to aage ke update khud yahin se le leti hai.

## Lagana

**Windows** - exe chalao. Pehli baar SmartScreen warning aayegi (exe signed
nahi hai): **More info -> Run anyway**. App ke andar **Install on this PC**
dabao - Start Menu me icon aa jayega aur PC chalu hone par app khud chalegi.

**Linux**

```bash
chmod +x dxconnect-linux-x86_64
./dxconnect-linux-x86_64 --install
```

Phir menu me **Dxconnect** dhoondho. Wayland par pehli baar screen share ki
ijazat ka dialog aayega - ek baar **Share** dabao, phir dobara nahi poochhega.

**Android** - APK kholo aur install karo (Settings me "unknown sources" allow
karna padega).

## Istemaal

1. Dono taraf app chalao.
2. Har window apni **10-digit ID** dikhati hai.
3. Jis PC ko dekhna hai uski ID doosre me daal kar **Connect** dabao.

Phone ya tablet par kuch install kiye bina bhi chalta hai: jis PC ko dekhna hai
uske `http://<us-pc-ka-ip>:47812` ko phone ke browser me kholo.

Doosre device ko app deni ho to app ki window me upar **Download**, **Copy**
aur **QR** hain - QR scan karte hi sahi file utarti hai.

---

Is repo me sirf bani hui files (Releases) hain.
