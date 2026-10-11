অলুপস (ALUPS) Android অ্যাপ প্রজেক্ট

এই ZIP-টি Android Studio-তে খোলার জন্য সোর্স প্রজেক্ট। এটি নিজে ইনস্টলযোগ্য APK নয়।
APK তৈরি করতে:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. ZIP Extract করে Android Studio থেকে Alups ফোল্ডার Open করুন।
3. Gradle Sync শেষ হতে দিন এবং প্রয়োজন হলে Android SDK 35 ইনস্টল করুন।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5. APK সাধারণত app/build/outputs/apk/debug/app-debug.apk-এ তৈরি হবে।
6. APK ফোনে পাঠিয়ে খুলুন এবং Android চাইলে ওই অ্যাপ/ফাইল ম্যানেজারের জন্য Install unknown apps অনুমতি দিন।

অ্যাপের বর্তমান সুবিধা: হোম-স্ক্রিন লঞ্চার আইকন, কাস্টমার নাম/ঠিকানা/CN/পিস এন্ট্রি, ফোনে লোকাল সেভ, মোট পিস গণনা, Android Print service দিয়ে রসিদ প্রিন্ট।
সীমাবদ্ধতা: Google Sheets-এ অটো-সিঙ্ক এখনো সংযুক্ত নয়। XP-330B-তে সরাসরি ব্লুটুথ প্রিন্টের জন্য প্রিন্টারের সঠিক কানেকশন/প্রোটোকল ও উপযুক্ত SDK দরকার; বর্তমান প্রিন্ট বোতাম Android-এর Print service ব্যবহার করে।
