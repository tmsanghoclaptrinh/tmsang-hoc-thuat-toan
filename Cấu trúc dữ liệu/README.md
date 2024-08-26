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

Đang cập nhật

## Dynamic Array

Đang cập nhật

## Ngăn xếp (Stack)

Đang cập nhật

## Hàng đợi (Queue)

Đang cập nhật

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