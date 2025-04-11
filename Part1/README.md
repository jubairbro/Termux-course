# Termux ক্লাস: দিন ১ - বেসিক কমান্ড শিখি

Termux হলো Android এর জন্য একটি শক্তিশালী Linux টার্মিনাল অ্যাপ। এই ক্লাসে আমরা শেখবো Termux ওপেন করার পর দরকারি বেসিক কমান্ডগুলো।

---

## ১. Termux আপডেট ও আপগ্রেড
```bash
pkg update -y
pkg upgrade -y
```

---

## ২. দরকারি প্যাকেজ ইনস্টল
```bash
pkg install git -y
pkg install python -y
pkg install curl -y
pkg install wget -y
pkg install nano -y
pkg install unzip -y
pkg install zip -y
pkg install neofetch -y
```

---

## ৩. স্টোরেজ পারমিশন নিতে (sdcard access)
```bash
termux-setup-storage
```

---

## ৪. ফাইল ও ফোল্ডার ম্যানেজমেন্ট

| কাজ                                | কমান্ড                           |
|-----------------------------------|----------------------------------|
| বর্তমান লোকেশন জানতে              | `pwd`                            |
| ফোল্ডারে থাকা ফাইলগুলো দেখতে     | `ls`                             |
| হিডেন ফাইলসহ দেখতে               | `ls -a`                          |
| ফোল্ডার তৈরি করতে                 | `mkdir FolderName`              |
| ফোল্ডারে ঢুকতে                    | `cd FolderName`                 |
| এক ধাপ পেছনে যেতে                 | `cd ..`                          |
| একসাথে পিছনে যেতে                | `cd ../../`                     |
| ফাইল তৈরি করতে                    | `touch file.txt`                |
| ফাইল লিখতে                        | `nano file.txt`                 |
| ফাইলের কনটেন্ট দেখতে             | `cat file.txt`                  |
| ফাইল ডিলিট করতে                   | `rm file.txt`                   |
| ফোল্ডার সহ ডিলিট করতে             | `rm -rf FolderName`             |
| ফাইল কপি করতে                     | `cp file1.txt newfile.txt`      |
| ফাইল কাট-পেস্ট করতে               | `mv file.txt /new/location/`    |

---

## ৫. Bash স্ক্রিপ্ট চালানো
```bash
chmod +x script.sh   # রান করার পারমিশন দেওয়া
./script.sh          # স্ক্রিপ্ট চালানো
```

---

## ৬. Git ব্যবহার করে প্রজেক্ট ক্লোন করা
```bash
git clone https://github.com/user/repo.git
cd repo
ls
```

---

```

---

## ৮. সিস্টেম তথ্য দেখতে
```bash
neofetch
```

---

## ৯. টার্মিনাল পরিস্কার ও বের হওয়া
```bash
clear     # স্ক্রিন ক্লিয়ার
exit      # Termux থেকে বের হওয়া
```

---

## ১০. সাহায্য ও ম্যানুয়াল দেখতে
```bash
<command> --help
man <command>
```

---

## ✅ পরবর্তী ক্লাসে:
- Bash চালানো
- Python স্ক্রিপ্ট চালানো
- টুল বানানোর (ধারণা) 
  
---

**Creator :** Jubair Bro  
**Telegram :** [https://t.me/JubairFF](https://t.me/JubairFF)
