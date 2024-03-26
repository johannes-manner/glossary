---
title: মাপযোগ্যতা (Scalability)
status: Completed
category: বৈশিষ্ট্য
tags: ["মৌলিক", "বৈশিষ্ট্য", ""]
---

মাপযোগ্যতা বলতে বোঝায় একটি সিস্টেম কতটা ভালোভাবে বৃদ্ধি  করতে  পারে। সিস্টেমের যা করা উচিত তা করার ক্ষমতাকে  এটি বৃদ্ধি করে।
উদাহরণস্বরূপ, একটি কুবারনেটিস ([Kubernetes](/bn/kubernetes/)) ক্লাস্টার([cluster](/bn/cluster/))স্কেল কন্টেইনারাইজড ([containerized](/bn/containerization/)) অ্যাপের সংখ্যা বৃদ্ধি বা হ্রাস করে, কিন্তু সেই পরিমাপযোগ্যতা বিভিন্ন কারণের উপর নির্ভর করে।
এটিতে কতগুলি নোড ([nodes](/bn/nodes/)) রয়েছে, প্রতিটি নোড কতগুলি কন্টেইনার পরিচালনা করতে পারে এবং কন্ট্রোল প্যানেলটি কতগুলি রেকর্ড এবং অপারেশানের ভারবহন করতে পারে?


একটি মাপযোগ্য সিস্টেম আরও ক্ষমতা যোগ করা সহজ করে তোলে। 
আমরা দুটি পরিমাপ পদ্ধতির মধ্যে পার্থক্য করি। একদিকে, অনুভূমিক পরিমাপ ([horizontal scaling](/bn/horizontal-scaling/)) রয়েছে যা বর্ধিত লোড পরিচালনা করতে আরও নোড যোগ করে।
বিপরীতে, উল্লম্ব পরিমাপে ([vertical scaling](/bn/vertical-scaling/)) পৃথক নোডগুলিকে আরও বেশি লেনদেন করার জন্য আরও শক্তিশালী করা হয় (যেমন একটি পৃথক মেশিনে আরও মেমরি বা CPU যোগ করে)। 
একটি মাপযোগ্য সিস্টেম সহজেই পরিবর্তন করতে এবং ব্যবহারকারীর চাহিদা মেটাতে সক্ষম।