# [Tờ Mờ Sáng học Thuật toán và Lập trình thi đấu](/README.md)

# Cấu trúc dữ liệu (Data Structures)

> Tổng hợp danh sách những tài liệu hay và bổ ích về **Thuật toán và Lập trình thi đấu**
> 
> Người tổng hợp: **[Trần Minh Sáng](https://www.facebook.com/sangtran.04/)**

<p align="left">
  <a href="#"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhits.dwyl.com%2Ftmsanghoclaptrinh%2Ftmsang-hoc-thuat-toan.json&label=visitors&color=blue"></a>
  <a href="#"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/tmsanghoclaptrinh/tmsang-hoc-thuat-toan"></a>
</p>
<p align="left">
  <a href="https://github.com/tmsanghoclaptrinh"><img src="https://img.shields.io/badge/author-tmsanghoclaptrinh-41454A?logo=github&labelColor=grey"></a>
  <a href="https://facebook.com/clb.it.ngoctao"><img src="https://img.shields.io/badge/facebook-clb.it.ngoctao-41454A?logo=facebook&logoColor=white&labelColor=blue"></a>
  <a href="https://www.youtube.com/@tmsanghoclaptrinh"><img src="https://img.shields.io/badge/youtube-tmsanghoclaptrinh-41454A?logo=youtube&logoColor=white&labelColor=red"></a>
  <a href="https://discord.gg/ajXr5kRKkk"><img src="https://img.shields.io/discord/994125923819458590?logo=discord&logoColor=white&labelColor=5865F2&color=green" alt="chat on Discord"></a>
</p>
<p align="left">
  <a href="https://tmsanghoclaptrinh.com"><img src="https://img.shields.io/badge/blog-tmsanghoclaptrinh.com-white"></a>
  <a href="https://dev.to/tmsanghoclaptrinh"><img src="https://img.shields.io/badge/dev.to-tmsanghoclaptrinh-white"></a>
</p>

### Series video "Lên trình Thuật toán - Lập trình thi đấu": 

[![](https://markdown-videos-api.jorgenkh.no/youtube/AgwnOQbJVvU)](https://www.youtube.com/watch?v=AgwnOQbJVvU&list=PLqfkD788zZGCjhbJsmyhInVAhHBSV8Gqg&index=1)

## Cài đặt extension [Random Algorithm Topics](https://chromewebstore.google.com/detail/random-algorithm-topics/cfbnefdpfhohjhehglbjkchobnaknbkm) trên Google Chrome để học ngẫu nhiên một chủ đề trong danh sách mỗi khi mở 1 tab mới trên trình duyệt

<img src="../media/chrome_logo.png" height=16/> [Install on Google Chrome](https://chromewebstore.google.com/detail/random-algorithm-topics/cfbnefdpfhohjhehglbjkchobnaknbkm)

<img src="../media/screenshot.jpeg" alt="Extension Random Algorithm Topics screenshot">

## Nội dung chính của phần "Cấu trúc dữ liệu (Data Structures)"

- [Tổng quan về cấu trúc dữ liệu](#tổng-quan-về-cấu-trúc-dữ-liệu)
- [Mảng (Array) và Danh sách liên kết (Linked list)](#mảng-array-và-danh-sách-liên-kết-linked-list)
- [Dynamic Array](#dynamic-array)
- [Ngăn xếp (Stack)](#ngăn-xếp-stack)
- [Hàng đợi (Queue)](#hàng-đợi-queue)
- [Set và Multiset](#set-và-multiset)
- [Hàng đợi ưu tiên (Priority Queue)](#hàng-đợi-ưu-tiên-priority-queue)
- [Mảng cộng dồn và mảng hiệu](#mảng-cộng-dồn-và-mảng-hiệu)
- [Deque và tìm min max trên đoạn tịnh tiến](#deque-và-tìm-min-max-trên-đoạn-tịnh-tiến)
- [Heap](#heap)
- [Bảng băm (Hash table)](#bảng-băm-hash-table)
- [Disjoint Set Union (DSU)](#disjoint-set-union-dsu)
- [Cây Phân Đoạn (Segment Tree - Interval Tree)](#cây-phân-đoạn-segment-tree---interval-tree)
- [Chia căn](#chia-căn)
- [Fenwick Tree (Binary Indexed Tree)](#fenwick-tree-binary-indexed-tree)
- [Heavy Light Decomposition (HLD)](#heavy-light-decomposition-hld)
- [Persistent Data Structures](#persistent-data-structures)
- [Lowest Common Ancestor (LCA) - Binary Lifting](#lowest-common-ancestor-lca---binary-lifting)
- [Bài toán RMQ & bài toán LCA](#bài-toán-rmq--bài-toán-lca)
- [Trie](#trie)
- [Suffix Array](#suffix-array)
- [Palindrome Tree](#palindrome-tree)
- [Skip List](#skip-list)
- [Range Tree](#range-tree)

## Tổng quan về cấu trúc dữ liệu

- Bài viết tiếng Việt:
  - [Tổng quan về Cấu Trúc Dữ Liệu - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/data-structures-overview)
  - [Cấu trúc dữ liệu - Wikipedia](https://vi.wikipedia.org/wiki/C%E1%BA%A5u_tr%C3%BAc_d%E1%BB%AF_li%E1%BB%87u)
  - [Cấu trúc dữ liệu là gì? Tổng hợp các loại cấu trúc dữ liệu](https://funix.edu.vn/chia-se-kien-thuc/cau-truc-du-lieu-la-gi-tong-hop-cac-loai-cau-truc-du-lieu/)
- Video tiếng Việt:
  - [8 Cấu Trúc Dữ Liệu cơ bản mà Dev nào cũng nên biết - Tôi Đi Code Dạo](https://www.youtube.com/watch?v=YYta5uWViJc)
  - [Cấu trúc dữ liệu và thuật toán - Ông Dev](https://youtu.be/Q7UuJAhysZg?si=-QC56TTkFOLESK6r)
  - [Thông não cơ bản về Cấu trúc dữ liệu & Giải thuật. Môn này quan trọng thế nào?](https://www.youtube.com/watch?v=HmA2gjp5wWI)
- Bài viết tiếng Anh:
  - [Algorithm Gym :: Data structures - Codeforces Blog](https://codeforces.com/blog/entry/15729)
  - [Data Structures](https://www.topcoder.com/thrive/articles/Data%20Structures)
  - [Data Structures Tutorial - GeeksforGeeks](https://www.geeksforgeeks.org/data-structures/)
  - [Data structure - Wikipedia](https://en.wikipedia.org/wiki/Data_structure)
  - [Data Structures & Algorithms - Tech Dev Guide with Google](https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/)
- Video tiếng Anh:
  - [What Are Data Structures? - CS Dojo](https://www.youtube.com/watch?v=bum_19loj9A)
  - [Data Structures: Crash Course Computer Science](https://www.youtube.com/watch?v=DuDz6B4cqVc)
  - [Data Structures and Algorithms in 15 Minutes](https://www.youtube.com/watch?v=oz9cEqFynHU)
  - [Learn Data Structures and Algorithms for free](https://www.youtube.com/watch?v=CBYHwZcbD-s)
  - [CS50x 2024 - Lecture 5 - Data Structures](https://www.youtube.com/watch?v=0euvEdPwQnQ)
  - [Data Structures - Full Course Using C and C++ - freeCodeCamp](https://www.youtube.com/watch?v=B31LgI4Y4DQ)
  - [Data Structures and Algorithms for Beginners - Programming with Mosh](https://www.youtube.com/watch?v=BBpAmxU_NQo)

## Mảng (Array) và Danh sách liên kết (Linked list)

- Bài viết tiếng Việt:
  - [Mảng và danh sách liên kết - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/array-vs-linked-lists)
  - [Xử lý mảng trong C++ và những điều cần lưu ý](https://stringee.com/vi/blog/post/xu-ly-mang-trong-c)
  - [Mảng 1 chiều trong C++ (Arrays)](https://howkteam.vn/course/khoa-hoc-lap-trinh-c-can-ban/mang-1-chieu-trong-c-arrays-1377)
  - [Mảng - Array - Slide Đại học Công nghệ - Đại học Quốc gia (UET)](https://uet.vnu.edu.vn/~sonpb/THCS4/Lecture05_Mang.pdf)
  - [Danh sách liên kết - Wikipedia](https://vi.wikipedia.org/wiki/Danh_s%C3%A1ch_li%C3%AAn_k%E1%BA%BFt)
  - [Danh Sách Liên Kết - Linked List](https://blog.28tech.com.vn/danh-sach-lien-ket-linked-list)
  - [Ôn tập struct và bộ nhớ động Linked Lists - Slide Đại học Công nghệ - Đại học Quốc gia (UET)](https://uet.vnu.edu.vn/~tqlong/2018ltnc/Support-Lec9&10-LinkedLists.pdf)
- Video tiếng Việt:
  - [Array - Mảng](https://www.youtube.com/watch?v=IRoOEsNqgzM)
  - [Mảng Một Chiều Và Các Bài Toán Quen Thuộc Về Mảng Trong Ngôn Ngữ Lập Trình C](https://www.youtube.com/watch?v=DrKvp90X0Uo)
  - [Giới thiệu Linked list](https://www.youtube.com/watch?v=XduwHI8bbcA)
  - [Linked list phần 2](https://www.youtube.com/watch?v=ZaG5n_6ehIw)
  - [Linked list phần 3: CODE](https://www.youtube.com/watch?v=OJz-DuvFd24)
  - [Danh sách liên kết và cây nhị phân](https://www.youtube.com/playlist?list=PLux-_phi0Rz1k7dQ7iWAw4xDD-KBHcW0F)
  - [Danh Sách Liên Kết Đơn Ngôn Ngữ Lập Trình C++](https://www.youtube.com/watch?v=mdG5TEiJTx8)
- Bài viết tiếng Anh:
  - [Linked list - Wikipedia](https://en.wikipedia.org/wiki/Linked_list)
  - [VisuAlgo](https://visualgo.net/en/list?slide=1)
  - [Linked List Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/linked-list-data-structure/)
  - [DSA Linked Lists - W3Schools](https://www.w3schools.com/dsa/dsa_theory_linkedlists.php)
  - [Linked list cheatsheet for coding interviews](https://www.techinterviewhandbook.org/algorithms/linked-list/)
  - [Singly Linked List - HackerEarth](https://www.hackerearth.com/practice/data-structures/linked-list/singly-linked-list/tutorial/)
- Video tiếng Anh:
  - [CS50x 2024 - Lecture 2 - Arrays](https://www.youtube.com/watch?v=4vU4aEFmTSo)
  - [An Overview of Arrays and Memory](https://www.youtube.com/watch?v=pmN9ExDf3yQ)
  - [Arrays in C++](https://www.youtube.com/watch?v=ENDaJi08jCU)
  - [CS50x 2024 - Lecture 5 - Data Structures](https://www.youtube.com/watch?v=0euvEdPwQnQ)
  - [Introduction to Linked List](https://www.youtube.com/watch?v=R9PTBwOzceo)
  - [Introduction to Linked Lists](https://www.youtube.com/watch?v=WwfhLC16bis)
  - [Data Structures: Linked Lists](https://www.youtube.com/watch?v=njTh_OwMljA)
  - [Linked Lists for Technical Interviews](https://www.youtube.com/watch?v=Hj_rA0dhr2I)
  - [Linked List - Implementation in C/C++](https://www.youtube.com/watch?v=vcQIFT79_50)

## Dynamic Array

- Bài viết tiếng Việt:
  - [Cấp phát mảng động (Dynamically allocating arrays)](https://howkteam.vn/course/khoa-hoc-lap-trinh-c-can-ban/cap-phat-mang-dong-dynamically-allocating-arrays-2743)
  - [Cấp Phát Mảng Động](https://blog.28tech.com.vn/c-cap-phat-mang-dong)
  - [Con trỏ và Mảng động - Slide Đại học Công nghệ - Đại học Quốc gia (UET)](https://uet.vnu.edu.vn/~diepht/s12_int2202/lect10_pointer.pdf)
  - [Vector Trong C++](https://blog.28tech.com.vn/stl-vector-trong-c)
  - [Sử dụng vector trong lập trình C++ - giải bài toán lập trình muôn thủa](https://viblo.asia/p/su-dung-vector-trong-lap-trinh-c-giai-bai-toan-lap-trinh-muon-thua-Az45bnGQ5xY)
- Video tiếng Việt:
  - [Implement DynamicArray](https://www.youtube.com/watch?v=MtSDY_kuM7o)
  - [Cấp phát mảng động](https://www.youtube.com/watch?v=vn4Q8hDz_OQ)
  - [Mảng động-dynamic array](https://www.youtube.com/watch?v=g_25amR5vM8)
  - [Con Trỏ Trong Ngôn Ngữ C | Truyền Tham Chiếu | Cấp Phát Động](https://www.youtube.com/watch?v=9kaUEMbXEk4)
- Bài viết tiếng Anh:
  - Mục ***5.1 Dynamic Arrays*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
  - [Dynamic array - Wikipedia](https://en.wikipedia.org/wiki/Dynamic_array)
  - [How do Dynamic arrays work? - GeeksforGeeks](https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/)
  - [Difference between Static Arrays and Dynamic Arrays - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-static-arrays-and-dynamic-arrays/)
- Video tiếng Anh:
  - [Data Structures and Dynamic Arrays - MIT OpenCourseWare](https://www.youtube.com/watch?v=CHhwJjR0mZA&t=16s)
  - [Dynamic Arrays - Bro Code](https://www.youtube.com/watch?v=jzJlq35dQII)
  - [The Simple and Elegant Idea behind Efficient Dynamic Arrays](https://www.youtube.com/watch?v=Ij7NQ-0mIVA)
  - [Static Arrays vs. Dynamic Arrays](https://www.youtube.com/watch?v=qTb1sZX74K0)
  - [Dynamic Arrays in C++ (std::vector)](https://www.youtube.com/watch?v=PocJ5jXv8No)
  - [Optimizing the usage of std::vector in C++](https://www.youtube.com/watch?v=HcESuwmlHEY)

## Ngăn xếp (Stack)

- Bài viết tiếng Việt:
  - [Stack (ngăn xếp) - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/Stack)
  - [Ngăn xếp - Wikipedia](https://vi.wikipedia.org/wiki/Ng%C4%83n_x%E1%BA%BFp)
  - [Stack - Cấu trúc dữ liệu ngăn xếp](https://howkteam.vn/course/cau-truc-du-lieu-va-giai-thuat/stack-cau-truc-du-lieu-ngan-xep-4271)
- Video tiếng Việt:
  - [Stack - Ông Dev](https://www.youtube.com/watch?v=BxxG5aFEtBE)
  - [Stack Implementations - Ông Dev](https://www.youtube.com/watch?v=bLafmb5KeWE)
  - [Stack Code - Ông Dev](https://www.youtube.com/watch?v=_v4kcYNJDLQ)
  - [Cách Hoạt Động của CTDL Ngăn Xếp](https://www.youtube.com/watch?v=MQZ1TH0l7sk)
  - [Memory layout in C: Một chương trình C được tổ chức trong memory như thế nào? Heap và Stack là gì?](https://www.youtube.com/watch?v=9890mLEpECg)
- Bài viết tiếng Anh:
  - [Stack (abstract data type) - Wikipedia](https://en.wikipedia.org/wiki/Stack_%28abstract_data_type%29)
  - [DSA Stacks - W3Schools](https://www.w3schools.com/dsa/dsa_data_stacks.php)
  - [Stack Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/stack-data-structure/)
  - [Basics of Stacks - HackerEarth](https://www.hackerearth.com/practice/data-structures/stacks/basics-of-stacks/tutorial/)
- Video tiếng Anh:
  - [Introduction to Stacks](https://www.youtube.com/watch?v=I37kGX-nZEI)
  - [Learn Stack data structures in 10 minutes](https://www.youtube.com/watch?v=KInG04mAjO0)
  - [Data structures: Introduction to stack](https://www.youtube.com/watch?v=F1F2imiOJfk)
  - [Pointers and dynamic memory - stack vs heap](https://www.youtube.com/watch?v=_8-ht2AKyH4)
  - [Introduction to Stacks and Queues - CS Dojo](https://www.youtube.com/watch?v=A3ZUpyrnCbM)

## Hàng đợi (Queue)

- Bài viết tiếng Việt:
  - [Hàng đợi - Wikipedia](https://vi.wikipedia.org/wiki/H%C3%A0ng_%C4%91%E1%BB%A3i)
  - [Stack và Queue thì ứng dụng được gì vào dự án thực tế???](https://viblo.asia/p/stack-va-queue-thi-ung-dung-duoc-gi-vao-du-an-thuc-te-r1QLxB8o4Aw)
  - [Cấu trúc dữ liệu và thuật toán | Hàng đợi (Queue)](https://www.tailieubkhn.com/2023/08/cau-truc-du-lieu-va-thuat-toan-hang-doi-queue.html)
  - [Một số dạng hàng đợi](https://tek4.vn/khoa-hoc/cau-truc-du-lieu-va-thuat-toan/mot-so-dang-hang-doi)
  - [Queue và Deque](https://howkteam.vn/course/cau-truc-du-lieu-va-giai-thuat/queue-va-deque-4272)
- Video tiếng Việt:
  - [Cấu Trúc Dữ Liệu Hàng Đợi Trong C++ | Cách Hoạt Động Của Hàng Đợi (Queue)](https://www.youtube.com/watch?v=gYG70ULXbW4)
  - [Cài Đặt Hàng Đợi Bằng Danh Sách Liên Kết Và Mảng 1 Chiều](https://www.youtube.com/watch?v=Y4JgOv6N_WY)
  - [Queue - Ông Dev](https://www.youtube.com/watch?v=qpqSiYjS9-4)
  - [Queue Implementations - Ông Dev](https://www.youtube.com/watch?v=EFdvAXaPYVY)
  - [Queue Code - Ông Dev](https://www.youtube.com/watch?v=frMLRE88cmg)
- Bài viết tiếng Anh:
  - [Queue (abstract data type) - Wikipedia](https://en.wikipedia.org/wiki/Queue_%28abstract_data_type%29)
  - [DSA Queues - W3Schools](https://www.w3schools.com/dsa/dsa_data_queues.php)
  - [Queue Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/queue-data-structure/)
  - [Basics of Queues - HackerEarth](https://www.hackerearth.com/practice/data-structures/queues/basics-of-queues/tutorial/)
- Video tiếng Anh:
  - [Queues in 3 minutes](https://www.youtube.com/watch?v=D6gu-_tmEpQ)
  - [Data structures: Array implementation of Queue](https://www.youtube.com/watch?v=okr-XE8yTO8)
  - [Data structures: Linked List implementation of Queue](https://www.youtube.com/watch?v=A5_XdiK4J8A)
  - [Learn Queue data structures in 10 minutes](https://www.youtube.com/watch?v=nqXaPZi99JI)
  - [Introduction to Stacks and Queues - CS Dojo](https://www.youtube.com/watch?v=A3ZUpyrnCbM)
  - [What is a Message Queue?](https://www.youtube.com/watch?v=xErwDaOc-Gs)

## Set và Multiset

- Bài viết tiếng Việt:
  - [[STL]. Set Trong C++](https://blog.28tech.com.vn/stl-set-trong-c)
  - [[STL]. Các Hàm Thông Dụng Của Set Trong C++](https://blog.28tech.com.vn/stl-cac-ham-thong-dung-cua-set-trong-c)
  - [[STL]. Multiset Trong C++](https://blog.28tech.com.vn/stl-multiset-trong-c)
  - [[STL]. Unordered_set Trong C++](https://blog.28tech.com.vn/stl-unorderedset-trong-c)
  - [Thư viện STL C++ (phần 2) - Tập hợp (Set) và một số ứng dụng](https://viblo.asia/p/bai-15-thu-vien-stl-c-phan-2-tap-hop-set-va-mot-so-ung-dung-bWrZnQynKxw)
  - [Multiset trong C++ là gì](https://laptrinhcanban.com/cpp/lap-trinh-cpp-co-ban/multiset-trong-cpp/multiset-trong-cpp-la-gi/)
- Video tiếng Việt:
  - [Cấu Trúc Dữ Liệu Set Trong C++ | Multiset | Unordered_set](https://youtu.be/lQ0KTlXDRR0?si=ZKWZ7OA46MoQpjyC)
  - [Set,Multiset và Unordered_set trong thư viện STL của C++](https://www.youtube.com/watch?v=VA8xzJzuEoA)
  - [Hướng Dẫn Bài Tập Áp Dụng Set Và Map Trong C++](https://www.youtube.com/watch?v=JcSs5ryBAKg)
- Bài viết tiếng Anh:
  - Mục ***5.2.1 Sets and Multisets*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
  - [What is the difference between set and multiset in STL? - Quora](https://www.quora.com/What-is-the-difference-between-set-and-multiset-in-STL)
  - [Difference Between set, multiset, unordered_set, unordered_multiset in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-set-multiset-unordered_set-unordered_multiset-in-cpp/)
  - [Set (abstract data type) - Wikipedia](https://en.wikipedia.org/wiki/Set_%28abstract_data_type%29)
  - [Set in C++ Standard Template Library (STL)](https://www.geeksforgeeks.org/set-in-cpp-stl/)
  - [Multiset in C++ Standard Template Library (STL)](https://www.geeksforgeeks.org/multiset-in-cpp-stl/)
- Video tiếng Anh:
  - [std::set In C++](https://www.youtube.com/watch?v=1YpxRmsDuls)
  - [Multiset In C++](https://www.youtube.com/watch?v=xxA2QjKj73w)
  - [std::unordered_set In C++](https://youtu.be/Yevgn0yu5mI?si=FqPbJnAGh6PFhlxn)
  - [std::unordered_multiset In C++](https://www.youtube.com/watch?v=hmc6ck5IsRQ)
  - [C++ Programming Language Tutorial | Set in C++ STL | GeeksforGeeks](https://www.youtube.com/watch?v=YuZPHhniZtw)
  - [C++ Programming Language Tutorial | Multiset in C++ STL | GeeksforGeeks](https://www.youtube.com/watch?v=xelzlR_OGnI)
  - [C++ STL Tutorial: Sets and MultiSet](https://www.youtube.com/watch?v=PKE_Y9_gHMo)

## Hàng đợi ưu tiên (Priority Queue)

- Bài viết tiếng Việt:
  - [Tổng quan về Priority Queue](https://howkteam.vn/course/cau-truc-du-lieu-va-giai-thuat/tong-quan-ve-priority-queue-4384)
  - [Priority Queue (hàng đợi ưu tiên) là gì? Hướng dẫn cách thiết lập mức độ ưu tiên cho hàng đợi cuộc gọi](https://duhunggroups.com/priority-queue-hang-doi-uu-tien-la-gi-huong-dan-cach-thiet-lap-muc-do-uu-tien-cho-hang-doi-cuoc-goi/)
  - [Sử dụng thư viện STL trong C++ : Priority Queue](https://hoccungchuyengia.com/su-dung-thu-vien-stl-trong-c-priority-queue/)
- Video tiếng Việt:
  - [Cấu Trúc Dữ Liệu Hàng Đợi Ưu Tiên | Priority_queue trong C++](https://www.youtube.com/watch?v=DRcAJNhtwbY)
  - [Heap Và Hàng Đợi Ưu Tiên (Priority Queue)](https://www.youtube.com/watch?v=KGukb-Z1ebA)
  - [Heap (Đống) - Priority Queue (Hàng đợi ưu tiên)](https://www.youtube.com/watch?v=BXYotZVWBm4)
- Bài viết tiếng Anh:
  - Mục ***5.2.3 Priority Queues*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
  - [Priority queue - Wikipedia](https://en.wikipedia.org/wiki/Priority_queue)
  - [What is Priority Queue | Introduction to Priority Queue - GeeksforGeeks](https://www.geeksforgeeks.org/priority-queue-set-1-introduction/)
  - [Priority Queue in C++ Standard Template Library (STL) - GeeksforGeeks](https://www.geeksforgeeks.org/priority-queue-in-cpp-stl/)
- Video tiếng Anh:
  - [Heap - Heap Sort - Heapify - Priority Queues - Abdul Bari](https://www.youtube.com/watch?v=HqPJF2L5h9U)
  - [Priority Queue Introduction](https://www.youtube.com/watch?v=wptevk0bshY)
  - [Priority Queue](https://www.youtube.com/watch?v=NlEwbC6Nt0c)
  - [Learn Priority Queue data structures in 5 minutes](https://www.youtube.com/watch?v=7z_HXFZqXqc)
  - [Heaps, heapsort, and priority queues - Inside code](https://www.youtube.com/watch?v=pLIajuc31qk)
  - [Priority Queue in C++ STL | GeeksforGeeks](https://www.youtube.com/watch?v=vc7i0bBuQEM)

## Mảng cộng dồn và mảng hiệu

- Bài viết tiếng Việt:
  - [Mảng cộng dồn và mảng hiệu - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/prefix-sum-and-difference-array.md)
  - [Quy hoạch động 5.5: Mảng tổng tiền tố và Mảng hiệu (phần 1)](https://viblo.asia/p/quy-hoach-dong-55-mang-tong-tien-to-va-mang-hieu-phan-1-r1QLx6104Aw)
  - [Quy hoạch động 5.5: Mảng tổng tiền tố và Mảng hiệu (phần 2)](https://viblo.asia/p/quy-hoach-dong-55-mang-tong-tien-to-va-mang-hieu-phan-2-GAWVpaRo405)
- Video tiếng Việt:
  - [Mảng Cộng Dồn Trên Mảng 1 Chiều Và 2 Chiều | Truy Vấn Tổng Trên Đoạn](https://www.youtube.com/watch?v=KxQkpu842rc)
  - [Mảng Cộng Dồn (Prefix Sum) Phần 1](https://www.youtube.com/watch?v=F68H8ESSOIs)
  - [Mảng Cộng Dồn (Prefix Sum) Phần 2](https://www.youtube.com/watch?v=FhWsl8bhpqA)
  - [Mảng Cộng Dồn (Prefix Sum) Phần 3](https://youtu.be/zi0E7Zsj1qM?si=kmctFZpzu7b_KWT-)
- Bài viết tiếng Anh:
  - [Prefix sum array and difference array](https://wcipeg.com/wiki/Prefix_sum_array_and_difference_array)
  - [Introduction to Prefix Sums - USACO Guide](https://usaco.guide/silver/prefix-sums?lang=cpp)
  - [More on Prefix Sums - USACO Guide](https://usaco.guide/silver/more-prefix-sums?lang=cpp)
  - [Prefix Sum Array – Implementation and Applications in Competitive Programming - GeeksforGeeks](https://www.geeksforgeeks.org/prefix-sum-array-implementation-applications-competitive-programming/)
  - [An Introduction To Difference Arrays - Codeforces Blog](https://codeforces.com/blog/entry/78762)
  - [Difference Array | Range update query in O(1) - GeeksforGeeks](https://www.geeksforgeeks.org/difference-array-range-update-query-o1/)
- Video tiếng Anh:
  - [Prefix Sums - Problems, Code in C++ & Python](https://www.youtube.com/watch?v=PhgtNY_-CiY)
  - [Prefix Sum Algorithm | Prefix Sum Array | Difference Array | Range Sum QueryO(1)](https://www.youtube.com/watch?v=pVS3yhlzrlQ)
  - [Prefix and Partial Sums](https://www.youtube.com/playlist?list=PLolmUFFwpoZXikmXzvaiKXJInVoA6_dpw)
  - [Subarray Sum Equals K - Prefix Sums - Leetcode 560 - Python](https://www.youtube.com/watch?v=fFVZt-6sgyo)
  - [Prefix Sum Array Explained](https://www.youtube.com/watch?v=7pJo_rM0z_s)
  - [Difference Array | Range update in O(1)](https://www.youtube.com/watch?v=R-PBfqsRGP0)

## Deque và tìm min max trên đoạn tịnh tiến

- Bài viết tiếng Việt:
  - [Deque - hàng đợi hai đầu - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/Deque)
  - [Hàng đợi hai đầu (deque) và Bài toán tìm max-min trong đoạn tịnh tiến - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/deque-min-max)
  - [Deque và Tìm min - max trên đoạn tịnh tiến](https://viblo.asia/p/deque-va-tim-min-max-tren-doan-tinh-tien-maGK7Bda5j2)
  - [Queue và Deque](https://howkteam.vn/course/cau-truc-du-lieu-va-giai-thuat/queue-va-deque-4272)
- Video tiếng Việt:
  - [Cấu Trúc Dữ Liệu Hàng Đợi Hai Đầu | Deque In C++](https://www.youtube.com/watch?v=MoD_cqJ9s6g)
  - [stack - deque (Tìm số nhỏ/lớn hơn gần nhất, tìm max min trên đoạn tịnh tiến) [C++]](https://www.youtube.com/watch?v=85S-YtmEuDo)
- Bài viết tiếng Anh:
  - [std::deque](https://cplusplus.com/reference/deque/deque/)
  - [Deque in C++ Standard Template Library (STL)](https://www.geeksforgeeks.org/deque-cpp-stl/)
  - [Double-ended queue - Wikipedia](https://en.wikipedia.org/wiki/Double-ended_queue)
- Video tiếng Anh:
  - [std::deque In C++](https://www.youtube.com/watch?v=uGWeixb7HMo)
  - [Deque - Data Structure](https://www.youtube.com/watch?v=5VDQxLAlfu0)
  - [Double-Ended Queue in Data Structure](https://www.youtube.com/watch?v=OnlgK0gjtB8)
  - [Deque In Data Structure | Introduction To Deque With Example](https://www.youtube.com/watch?v=OBftGLwEdEw)
  - [Sliding Window Maximum using Deque](https://www.youtube.com/watch?v=4JstGzs6Q9I)
  - [Deque Animation](https://www.youtube.com/watch?v=xC4m6O7VDJU)

## Heap

- Bài viết tiếng Việt:
  - [Binary Heap - VNOI Wiki](https://wiki.vnoi.info/translate/wcipeg/Binary-Heap)
  - [Đống (cấu trúc dữ liệu) - Wikipedia](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%91ng_%28c%E1%BA%A5u_tr%C3%BAc_d%E1%BB%AF_li%E1%BB%87u%29)
  - [Heap và priority_queue của C++](https://viblo.asia/p/heap-va-priority-queue-cua-c-gAm5ymYX5db)
- Video tiếng Việt:
  - [Heap (Đống) - Priority Queue (Hàng đợi ưu tiên)](https://www.youtube.com/watch?v=BXYotZVWBm4)
  - [Heap Và Hàng Đợi Ưu Tiên (Priority Queue)](https://www.youtube.com/watch?v=KGukb-Z1ebA)
- Bài viết tiếng Anh:
  - [Binary heap](https://wcipeg.com/wiki/Binary_heap)
  - [Heap (data structure) - Wikipedia](https://en.wikipedia.org/wiki/Heap_%28data_structure%29)
  - [Introduction to Heap - GeeksforGeeks](https://www.geeksforgeeks.org/introduction-to-heap/)
  - [Heap Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/heap-data-structure/)
  - [Heaps/Priority Queues - HackerEarth](https://www.hackerearth.com/practice/data-structures/trees/heapspriority-queues/tutorial/)
  - [VisuAlgo](https://visualgo.net/en/heap?slide=1)
- Video tiếng Anh:
  - [Heap - Heap Sort - Heapify - Priority Queues - Abdul Bari](https://www.youtube.com/watch?v=HqPJF2L5h9U)
  - [Heaps in 3 minutes - Intro](https://www.youtube.com/watch?v=0wPlzMU-k00)
  - [Heaps in 6 minutes — Methods](https://www.youtube.com/watch?v=pAU21g-jBiE)
  - [Heaps, heapsort, and priority queues - Inside code](https://www.youtube.com/watch?v=pLIajuc31qk)
  - [Data Structures: Heaps - HackerRank](https://www.youtube.com/watch?v=t0Cq6tVNRBA)
  - [Heaps and Heap Sort - MIT OpenCourseWare](https://www.youtube.com/watch?v=B7hVxCmfPtM)
  - [What Is a Binary Heap? - Spanning Tree](https://www.youtube.com/watch?v=AE5I0xACpZs)

## Bảng băm (Hash table)

- Bài viết tiếng Việt:
  - [Bảng băm (Hash Table) - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/hash-table)
  - [Bảng băm - Wikipedia](https://vi.wikipedia.org/wiki/B%E1%BA%A3ng_b%C4%83m)
  - [Bảng băm – Hash tables](https://nguyenvanhieu.vn/bang-bam-hash-tables/)
  - [Bảng băm (Hash table)](https://cuuduongthancong.com/atc/1371/bai-3-bang-bam-%28hash-table%29)
  - [Tìm hiểu về hash table](https://viblo.asia/p/tim-hieu-ve-hash-table-RnB5p0gY5PG)
- Video tiếng Việt:
  - [Giới thiệu về hash table (bảng băm)](https://www.youtube.com/watch?v=OpItfJ_5l_4)
  - [Cài đặt hash tables - xử lý va chạm bằng linked list](https://www.youtube.com/watch?v=GQs3FhwEmy0)
  - [Ứng dụng hash làm từ điển (Simple Dictionary)](https://www.youtube.com/watch?v=tRYXvuYcCBs)
  - [Hash table, hash function](https://www.youtube.com/watch?v=uKIFNzqX2a8)
  - [Hashtable Separate Chaining](https://www.youtube.com/watch?v=kBS3xQTVzVg)
  - [Hashtable Open Addressing](https://www.youtube.com/watch?v=UhBql4zi_nk)
  - [Hashtable Linear Probing](https://www.youtube.com/watch?v=i9e3pqoav5Q)
  - [Hashtable Quadratic Probing](https://www.youtube.com/watch?v=0AW6TJM9yFA)
  - [Hashtable Double Hashing](https://www.youtube.com/watch?v=Ix1PJgPvdVc)
  - [Hashtable Open Addressing Removal](https://www.youtube.com/watch?v=dHTVTsJ6kDM)
  - [Hashtable Open Addressing Code](https://www.youtube.com/watch?v=7zjm0IaVOIs)
  - [Hash function (Hàm băm) - Nghe tên kinh dị phết nhưng ý nghĩa thì là gì?](https://www.youtube.com/watch?v=vOmBRzAgH8I)
- Bài viết tiếng Anh:
  - [Basics of Hash Tables - HackerEarth](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
  - [Hash table - Wikipedia](https://en.wikipedia.org/wiki/Hash_table)(https://www.youtube.com/watch?v=vOmBRzAgH8I)
  - [Hash Table Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/hash-table-data-structure/)
  - [Hashing in Data Structure - GeeksforGeeks](https://www.geeksforgeeks.org/hashing-data-structure/)
  - [DSA Hash Tables - W3Schools](https://www.w3schools.com/dsa/dsa_theory_hashtables.php)
  - [VisuAlgo](https://visualgo.net/en/hashtable?slide=1)
  - [Hash Table Data structure
](https://www.tutorialspoint.com/data_structures_algorithms/hash_data_structure.htm)
- Video tiếng Anh:
  - [Hash tables in 4 minutes](https://www.youtube.com/watch?v=knV86FlSXJ8)
  - [Hash Tables and Hash Functions](https://www.youtube.com/watch?v=KyUTuwz_b7Q)
  - [Learn Hash Tables in 13 minutes](https://www.youtube.com/watch?v=FsfRsGFHuv4)
  - [Hashing - MIT OpenCourseWare](https://www.youtube.com/watch?v=Nu8YGneFCWE)
  - [Data Structures: Hash Tables - HackerRank](https://www.youtube.com/watch?v=shs0KM3wKv8)
  - [CS50 2019 - Lecture 5 - Hash Table](https://www.youtube.com/watch?v=btT4bCOvqjs)
  - [Understanding and implementing a Hash Table (in C)](https://www.youtube.com/watch?v=2Ti5yvumFTU)
  - [Hash Tables - CS50 Shorts](https://www.youtube.com/watch?v=nvzVHwrrub0)

## Disjoint Set Union (DSU)

- Bài viết tiếng Việt:
  - [Disjoint Set Union - VNOI Wiki](https://wiki.vnoi.info/algo/data-structures/disjoint-set-union)
  - [Tổng quan về Disjoint Sets Union và cách xây dựng DSU](https://howkteam.vn/course/cau-truc-du-lieu-va-giai-thuat/tong-quan-ve-disjoint-sets-union-va-cach-xay-dung-dsu-4385)
  - [Cấu trúc dữ liệu cho các tập hợp không giao nhau - Wikipedia](https://vi.wikipedia.org/wiki/C%E1%BA%A5u_tr%C3%BAc_d%E1%BB%AF_li%E1%BB%87u_cho_c%C3%A1c_t%E1%BA%ADp_h%E1%BB%A3p_kh%C3%B4ng_giao_nhau)
  - [Disjoint Set Union (DSU)](https://hackmd.io/@jalsol/DSU)
  - [Cấu trúc các tập không giao nhau – Disjoint Set Union (DSU)](https://codedream.edu.vn/disjoint-set-union-dsu/)
- Video tiếng Việt:
  - [Cấu Trúc Dữ Liệu Các Tập Hợp Rời Nhau | Disjoint Set Union DSU | Union Find](https://www.youtube.com/watch?v=fWLCQAwDt-0)
  - [DSU Disjoint Sets Union](https://www.youtube.com/watch?v=N-cfIxbDJe8)
- Bài viết tiếng Anh:
  - [Disjoint Set Union - cp-algorithms](https://cp-algorithms.com/data_structures/disjoint_set_union.html)
  - [Disjoint Set Union - USACO Guide](https://usaco.guide/gold/dsu?lang=cpp)
  - [Disjoint Set Union (Union Find) - HackerEarth](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/)
  - [Disjoint Set Union - CodeChef](https://www.codechef.com/learn/course/dsu)
  - [Introduction to Disjoint Set Data Structure | DSU - CodeForces Blog](https://codeforces.com/blog/entry/120381)
  - [Disjoint-set data structure - Wikipedia](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)
  - [Introduction to Disjoint Set (Union-Find Algorithm) - GeeksforGeeks](https://www.geeksforgeeks.org/introduction-to-disjoint-set-data-structure-or-union-find-algorithm/)
  - [Disjoint Set Data Structures - GeeksforGeeks](https://www.geeksforgeeks.org/disjoint-set-data-structures/)
- Video tiếng Anh:
  - [Disjoint Set Data Structure - Union Find Tutorial](https://www.youtube.com/watch?v=PGZ64ob440I)
  - [Disjoint Sets Data Structure - Weighted Union and Collapsing Find - Abdul Bari](https://www.youtube.com/watch?v=wU6udHRIkcc)
  - [Union Find in 5 minutes](https://www.youtube.com/watch?v=ayW5B2W9hfo)
  - [Disjoint Set | Union by Rank | Union by Size | Path Compression](https://www.youtube.com/watch?v=aBxjDBC4M1U)
  - [Disjoint Set | UNION and FIND](https://www.youtube.com/watch?v=eTaWFhPXPz4)
  - [Union Find Introduction](https://www.youtube.com/watch?v=ibjEGG7ylHk)
  - [Union Find Kruskal's Algorithm](https://www.youtube.com/watch?v=JZBQLXgSGfs)
  - [Union Find - Union and Find Operations](https://www.youtube.com/watch?v=0jNmHPfA_yE)
  - [Union Find Path Compression](https://www.youtube.com/watch?v=VHRhJWacxis)
  - [Union Find Code](https://www.youtube.com/watch?v=KbFlZYCpONw)

## Cây Phân Đoạn (Segment Tree - Interval Tree)

Đang cập nhật

## Chia căn

Đang cập nhật

## Fenwick Tree (Binary Indexed Tree)

Đang cập nhật

## Heavy Light Decomposition (HLD)

Đang cập nhật

## Persistent Data Structures

Đang cập nhật

## Lowest Common Ancestor (LCA) - Binary Lifting

Đang cập nhật

## Bài toán RMQ & bài toán LCA

Đang cập nhật

## Trie

Đang cập nhật

## Suffix Array

Đang cập nhật

## Palindrome Tree

Đang cập nhật

## Skip List

Đang cập nhật

## Range Tree

Đang cập nhật