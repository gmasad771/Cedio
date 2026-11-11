IT Doctor Online — Multi-page template

ফোল্ডার:
- index.html = হোম পেজ
- services/ = সেবাসমূহ
- courses/ = কোর্সসমূহ
- products/ = প্রোডাক্টস
- faq/ = প্রশ্নোত্তর
- contact/ = যোগাযোগ

পরিবর্তন:
- মূল HTML-এর ডিজাইন, কনটেন্ট, স্টাইল, স্ক্রিপ্ট, ট্র্যাকিং কোড ও বিদ্যমান ফিচারগুলো রেখে প্রতিটি মেনুর জন্য আলাদা পেজ তৈরি করা হয়েছে।
- নেভিগেশন এখন আলাদা পেজে যায়।
- _redirects ফাইলটি Netlify-তে /services, /courses ইত্যাদি clean URL সমর্থন করে।

প্রকাশ:
1. ZIP আনজিপ করুন।
2. Netlify-তে পুরো ফোল্ডার deploy করলে _redirects দিয়ে /services এর মতো URL কাজ করবে।
3. অন্য hosting-এ deploy করলে clean URL rewrite rules সেট করুন। সাধারণ static hosting-এ বিকল্প হিসেবে /services/ ব্যবহার করতে হতে পারে।
4. Google Sites-এর মধ্যে সরাসরি এই HTML template import করা যায় না; custom HTML hosting-এ প্রকাশ করে Google Sites-এ link/embed করতে হয়।
5. ডোমেইন DNS ও hosting configuration ঠিক করে custom domain যুক্ত করুন।

নোট: যোগাযোগ/অর্ডার ফর্ম, analytics, payment এবং WhatsApp flow-এর মূল সেটিংস অপরিবর্তিত রাখা হয়েছে। প্রকাশের পর বাস্তবে পরীক্ষা করুন।
