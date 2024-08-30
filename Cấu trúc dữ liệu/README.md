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

Đang cập nhật

## Hàng đợi ưu tiên (Priority Queue)

Đang cập nhật

## Mảng cộng dồn và mảng hiệu

Đang cập nhật

## Deque và tìm min max trên đoạn tịnh tiến

Đang cập nhật

## Heap

Đang cập nhật

## Bảng băm (Hash table)

Đang cập nhật

## Disjoint Set Union (DSU)

Đang cập nhật

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