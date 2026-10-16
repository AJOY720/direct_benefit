DIRECT BENEFIT — PWA DEMO

এই ডেমোতে আছে:
- Direct Benefit নাম ও মোবাইল responsive interface
- Admin Login এবং Member Login UI
- Admin-এর জন্য member add/edit/delete demo
- Member এবং Admin-এর আলাদা menu
- Dashboard, Team Shopee, Activation, Fund, My Shopee, Network, Income, Repurchase, Withdraw, Wallet, Settings, Harmony Bonus, Logout
- PWA manifest/service worker

Demo login (শুধু prototype পরীক্ষা করতে):
Admin: username admin / password AdminDemo123
Member: username member / password MemberDemo123

Android/GitHub Pages:
1. ZIP Extract করুন।
2. GitHub-এ নতুন repository তৈরি করুন।
3. ZIP-এর ভেতরের ফাইলগুলি repository root-এ upload করুন।
4. Settings > Pages > Deploy from a branch > main > /(root) > Save করুন।
5. আপনার প্রকাশিত GitHub Pages URL Chrome-এ খুলুন।
6. Chrome menu > Add to Home screen / Install app।

অত্যন্ত গুরুত্বপূর্ণ:
এই Login frontend demo মাত্র, নিরাপদ authentication নয়। ডেমো credentials app.js-এ দেখা যায়; কোনো বাস্তব password, ব্যক্তিগত তথ্য বা আর্থিক লেনদেন ব্যবহার করবেন না। localStorage ডেটা শুধু ওই browser/device-এ থাকে, একাধিক ফোনে sync হয় না।
বাস্তব ব্যবহারের জন্য Firebase/Supabase-এর মতো backend-এ secure authentication, role-based access rules, database, backups, audit logs এবং server-side transaction validation তৈরি করতে হবে। Fund/Income/Withdraw/Bonus বর্তমানে কার্যকর আর্থিক ফিচার নয়।
