MPR SQUAD — P.C.S Work Details (Offline Android Project)

এই প্রজেক্টে আপনার দেওয়া লোগো, QR আর MP RAKIB sordar-এর ছবিসহ HTML অ্যাপ যুক্ত আছে।
ডিউটি, বিল, ব্যক্তিভিত্তিক খরচ, বেতন/মোবাইল বিল/বোনাস, অন্যান্য তথ্য, PDF রিপোর্ট ও JSON ব্যাকআপ অফলাইনে কাজ করার জন্য তৈরি।

APK বানানোর সহজ উপায় (GitHub Actions):
1) ZIP Extract করে পুরো MPR_SQUAD_Android_Project ফোল্ডার GitHub repository-তে upload করুন।
2) GitHub repository খুলে Actions ট্যাবে যান।
3) “Build MPR SQUAD APK” workflow নির্বাচন করে Run workflow চাপুন।
4) কাজ শেষ হলে Artifacts থেকে MPR-SQUAD-debug-APK ডাউনলোড করুন।
5) ZIP খুলে app-debug.apk ফোনে ইনস্টল করুন। প্রয়োজনে Android Settings থেকে ওই ফাইল/ব্রাউজারের Install unknown apps অনুমতি দিন।

গুরুত্বপূর্ণ:
- এই কথোপকথনে APK নিজে compile করে পরীক্ষা করা হয়নি; এটি Android Studio/Gradle build-ready source project।
- অ্যাপের ডেটা ফোনের WebView local storage-এ থাকবে। অ্যাপের ডেটা Clear বা uninstall করলে ডেটা মুছে যেতে পারে। তাই নিয়মিত PDF/JSON backup রাখুন।
- আপনার দেওয়া QR ছবিটি হুবহু artwork হিসেবে বসানো হয়েছে; এটি স্ক্যান করে কাজ করে কি না আলাদা QR scanner দিয়ে যাচাই করুন।
- ছবি অ্যাপের মধ্যে bundled/fixed; অ্যাপ UI-তে বদলানোর অপশন নেই।
