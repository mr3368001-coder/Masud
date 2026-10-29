# Arning Many — Flutter starter

এটি Arning Many অ্যাপের **প্রাথমিক UI প্রোটোটাইপ**। বাংলা/ইংরেজি টগল, ভিডিও লিস্ট, অ্যাডমিন ডেমো কন্ট্রোল, এবং বিকাশে ম্যানুয়াল উইথড্র আবেদন স্ক্রিন আছে।

## গুরুত্বপূর্ণ সীমাবদ্ধতা
- এটি এখনো production app নয়; কোনো বাস্তব login, database, cloud sync বা payment integration নেই।
- Admin mode শুধু demo toggle; বাস্তবে অবশ্যই secure admin authentication ও server-side permissions লাগবে।
- অ্যাপ বন্ধ করলে ডেমো ডেটা হারিয়ে যাবে।
- YouTube views, likes, subscriptions বা comments-এর বিনিময়ে পুরস্কার দেবেন না। YouTube-এর নীতিমালা মেনে কেবল অনুমোদিত কাজ/প্রচার ব্যবহার করুন।
- বিকাশে টাকা ম্যানুয়ালি পাঠানোর আগে ব্যবহারকারীর পরিচয়, অনুরোধ ও লেনদেন যাচাই করুন।

## Android APK বানানো
1. Flutter SDK ও Android Studio ইনস্টল করুন।
2. এই ফোল্ডারটি প্রজেক্ট হিসেবে খুলুন।
3. টার্মিনালে চালান:
   - `flutter pub get`
   - `flutter run`
   - `flutter build apk --release`
4. APK পাবেন: `build/app/outputs/flutter-apk/app-release.apk`

## পরবর্তী production ধাপ
- Firebase Authentication বা সমমানের নিরাপদ লগইন
- Firestore/ব্যাকএন্ডে ইউজার, ভিডিও, পয়েন্ট ও withdrawal request
- সার্ভার-সাইড reward validation এবং abuse prevention
- Admin role access control
- Privacy policy, terms, support contact, payment audit log
