# Termux কী, কীভাবে কাজ করে এবং প্রয়োজনীয় বেসিক কমান্ডগুলো সুন্দরভাবে দেওয়া আছে:


---

Termux ক্লাস - প্রথম দিন: বেসিক পরিচিতি ও কমান্ড

Termux কী?

Termux একটি Android টার্মিনাল এমুলেটর ও লিনাক্স এনভায়রনমেন্ট যা মোবাইলেই প্রোগ্রামিং, টুল রান করা, স্ক্রিপ্ট চালানো, হ্যাকিং প্র্যাকটিস ইত্যাদি করতে সাহায্য করে।


---

প্রথম দিনের লক্ষ্য:

Termux ইন্টারফেস পরিচিতি

কমান্ড লাইন বেসিক

দরকারি প্যাকেজ ইনস্টল

ফাইল ও ডিরেক্টরি ব্যবস্থাপনা



---

১. Termux Update ও Upgrade

pkg update -y
pkg upgrade -y


---

২. প্যাকেজ ম্যানেজমেন্ট

pkg install <প্যাকেজ_নাম>
apt install <প্যাকেজ_নাম>

উদাহরণ:

pkg install git
pkg install curl
pkg install python


---

৩. সাহায্যের জন্য

<কমান্ড> --help
man <কমান্ড>


---

৪. ফাইল ও ডিরেক্টরি ম্যানেজমেন্ট


---

৫. Python ও Git ইনস্টলেশন

pkg install python -y
pkg install git -y


---

৬. স্টোরেজ পারমিশন (sdcard অ্যাক্সেস)

termux-setup-storage


---

৭. ফাইল এডিটর ইনস্টল (nano)

pkg install nano
nano filename.txt


---

৮. Git ক্লোন এবং রান

git clone <repo-url>
cd <foldername>
bash script.sh


---

৯. সেশন ক্লিয়ার / Exit

clear      # টার্মিনাল পরিস্কার
exit       # Termux থেকে বের হওয়া


---

১০. অতিরিক্ত দরকারি প্যাকেজসমূহ (suggested)

pkg install unzip
pkg install wget
pkg install neofetch
pkg install openssh


---

১১. টার্মিনাল স্টাইল দেখতে

neofetch


---

