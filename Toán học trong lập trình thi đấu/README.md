# [Tờ Mờ Sáng học Thuật toán và Lập trình thi đấu](/README.md)

# Toán học trong lập trình thi đấu

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

## Nội dung chính của phần "Toán học trong lập trình thi đấu"

- [Kiến thức nền tảng](#kiến-thức-nền-tảng)
  - [Hệ cơ số](#hệ-cơ-số)
  - [Cấp số cộng](#cấp-số-cộng)
  - [Cấp số nhân](#cấp-số-nhân)
  - [Lý thuyết tập hợp](#lý-thuyết-tập-hợp)
  - [Đại số logic](#đại-số-logic)
  - [Logarithm](#logarithm)
- [Số học](#số-học)
  - [Modulo](#modulo)
  - [Nghịch đảo modulo](#nghịch-đảo-modulo)
  - [Số nguyên tố](#số-nguyên-tố)
  - [Sàng nguyên tố](#sàng-nguyên-tố)
  - [Giải thuật Euclid](#giải-thuật-euclid)
  - [Lũy thừa modulo](#lũy-thừa-modulo)
  - [Lũy thừa nhị phân](#lũy-thừa-nhị-phân)
  - [Phi hàm Euler](#phi-hàm-euler)
  - [Giải phương trình](#giải-phương-trình)
  - [Định lý Wilson](#định-lý-wilson)
  - [Hàm Mobius](#hàm-mobius)
  - [Hàm nhân tính](#hàm-nhân-tính)
- [Tổ hợp](#tổ-hợp)
  - [Hệ số nhị thức](#hệ-số-nhị-thức)
  - [Dãy số Catalan](#dãy-số-catalan)
  - [Bao hàm - Loại trừ](#bao-hàm---loại-trừ)
  - [Bổ đề Burnside](#bổ-đề-burnside)
  - [Công thức Cayley](#công-thức-cayley)
  - [Biến đổi Fourier nhanh - FFT](#biến-đổi-fourier-nhanh---fft)
- [Ma trận](#ma-trận)
  - [Nhân ma trận](#nhân-ma-trận)
  - [Khử nhân ma trận](#khử-nhân-ma-trận)
  - [Truy hồi tuyến tính](#truy-hồi-tuyến-tính)
  - [Ma trận kề](#ma-trận-kề)
  - [Phép khử Gauss](#phép-khử-gauss)
- [Xác suất](#xác-suất)
  - [Cấp](#)
- [Lý thuyết trò chơi](#lý-thuyết-trò-chơi)
  - [Game State](#game-state)
  - [Trò chơi Nim](#trò-chơi-nim)
  - [Định lý Sprague–Grundy](#định-lý-spraguegrundy)

## Kiến thức nền tảng

### Hệ cơ số
- Bài viết tiếng Việt:
    - [Danh sách hệ đếm - Wikipedia](https://vi.wikipedia.org/wiki/Danh_s%C3%A1ch_h%E1%BB%87_%C4%91%E1%BA%BFm)
    - [Hệ cơ số (Hệ đếm)](https://viblo.asia/p/he-co-so-he-dem-m68Z0e72lkG)
- Video tiếng Việt:
    - [Biểu diễn số & chữ cái bằng nhị phân](https://www.youtube.com/watch?v=0OThQYFnilU)
    - [Cách chuyển đổi từ cơ số 2 sang 16 và ngược lại (dễ hiểu)](https://www.youtube.com/watch?v=lklO9DJG7no)
- Bài viết tiếng Anh:
    - [Numeral system](https://en.wikipedia.org/wiki/Numeral_system)
    - [Number System in Maths](https://www.geeksforgeeks.org/number-system-in-maths/)
- Video tiếng Anh:
    - [Number Systems](https://www.youtube.com/playlist?list=PL0o_zxa4K1BXCpQbUdf0htZE8SS0PYjy-)

### Cấp số cộng
- Bài viết tiếng Việt:
    - [Cấp số cộng](https://vi.wikipedia.org/wiki/C%E1%BA%A5p_s%E1%BB%91_c%E1%BB%99ng)
    - [Suy luận logic về công thức tính tổng Cấp số cộng](https://viblo.asia/p/suy-luan-logic-ve-cong-thuc-tinh-tong-cap-so-cong-5OXLAv7xVGr)
- Video tiếng Việt:
    - [Cấp số cộng](https://www.youtube.com/watch?v=tKNNGgdjpOU)
    - [Algorithm - Bài 5 - Cấp số cộng trực quan với animation](https://www.youtube.com/watch?v=dggeHK3mWPQ&list=PLqfkD788zZGCjhbJsmyhInVAhHBSV8Gqg&index=5)
- Bài viết tiếng Anh:
    - [Arithmetic progression](https://en.wikipedia.org/wiki/Arithmetic_progression)
    - [Arithmetic Progression - GeeksforGeeks](https://www.geeksforgeeks.org/what-is-arithmetic-progression/)
- Video tiếng Anh:
    - [Arithmetic Sequences and Arithmetic Series - Basic Introduction](https://www.youtube.com/watch?v=XZJdyPkCxuE)
    - [Intro to arithmetic progressions](https://www.khanacademy.org/math/in-in-grade-10-ncert/x573d8ce20721c073:arithmetic-progressions/x573d8ce20721c073:intro-to-arithmetic-progressions/v/intro-to-arithmetic-progressions-arithmetic-progressions)

### Cấp số nhân
- Bài viết tiếng Việt:
    - [Cấp số nhân](https://vi.wikipedia.org/wiki/C%E1%BA%A5p_s%E1%BB%91_nh%C3%A2n)
    - [Cấp số nhân hiểu ngay không cần nhớ công thức](https://viblo.asia/p/cap-so-nhan-hieu-ngay-khong-can-nho-cong-thuc-3RlL5glw4bB)
- Video tiếng Việt:
    - [Algorithm - Bài 6 - Cấp số nhân hiểu ngay không cần nhớ công thức](https://www.youtube.com/watch?v=nVw9dYGlXbc&list=PLqfkD788zZGCjhbJsmyhInVAhHBSV8Gqg&index=6)
    - [Cấp Số Nhân (Toán 11)](https://www.youtube.com/watch?v=GV40xpC56Ts)
- Bài viết tiếng Anh:
    - [Geometric progression](https://en.wikipedia.org/wiki/Geometric_progression)
    - [Geometric progression - GeeksforGeeks](https://www.geeksforgeeks.org/what-is-geometric-progression/)
- Video tiếng Anh:
    - [Intro to Geometric Progressions - Eddie Woo](https://www.youtube.com/watch?v=yo2DtZDYzKY)
    - [Geometric Series and Geometric Sequences](https://www.youtube.com/watch?v=zRKZ0-kOUZM)

### Lý thuyết tập hợp
- Bài viết tiếng Việt:
    - [Lý thuyết tập hợp](https://vi.wikipedia.org/wiki/L%C3%BD_thuy%E1%BA%BFt_t%E1%BA%ADp_h%E1%BB%A3p)
    - [Lý thuyết tập hợp (Set theory)](https://viblo.asia/p/ly-thuyet-tap-hop-set-theory-EbNVQwOWJvR)
- Video tiếng Việt:
    - [Algorithm - Bài 7 - Lý thuyết tập hợp (Set theory)](https://www.youtube.com/watch?v=4Nfj_dwrTn0&list=PLqfkD788zZGCjhbJsmyhInVAhHBSV8Gqg&index=7)
    - [Georg Cantor - “Cha Đẻ” Của Lý Thuyết Tập Hợp Trầm Cảm Vì Công Trình Bị Phản Đối](https://www.youtube.com/watch?v=hAalyeV_ty4)
- Bài viết tiếng Anh:
    - [Set theory](https://en.wikipedia.org/wiki/Set_theory)
    - [Set Theory - Đại học Stanford](https://plato.stanford.edu/entries/set-theory/)
- Video tiếng Anh:
    - [Exploring Mathematics: Set Theory - Eddie Woo](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N)
    - [Introduction to Set theory - Discrete mathematics](https://www.youtube.com/watch?v=tyDKR4FG3Yw)

### Đại số logic
- Bài viết tiếng Việt:
    - [Đại số Boole](https://vi.wikipedia.org/wiki/%C4%90%E1%BA%A1i_s%E1%BB%91_Boole)
    - [Slide bài giảng Đại số logic và ứng dụng thiết kế máy tính điện tử - Đại học Công nghệ - Đại học Quốc gia](http://uet.vnu.edu.vn/~nguyenhathanh/lectures/thcs2/slides/Bai%205%20Dai%20so%20logic%20va%20ung%20dung.pdf)
- Video tiếng Việt:
    - [Algorithm - Bài 8 - Đại số Logic / Logic Algebra / Boolean Algebra](https://www.youtube.com/watch?v=mo9H5JFfCYE&list=PLqfkD788zZGCjhbJsmyhInVAhHBSV8Gqg&index=8)
    - [Đại số Boolean & cổng logic](https://www.youtube.com/watch?v=feR-Ex5yZjU)
- Bài viết tiếng Anh:
    - [Boolean algebra](https://en.wikipedia.org/wiki/Boolean_algebra)
    - [The Mathematics of Boolean Algebra - Đại học Stanford](https://plato.stanford.edu/entries/boolalg-math/)
- Video tiếng Anh:
    - [Boolean Logic & Logic Gates](https://www.youtube.com/watch?v=gI-qXk7XojA)
    - [The Laws of Boolean Algebra Explained](https://www.youtube.com/watch?v=RMe69AdlFdI)

### Logarithm
- Bài viết tiếng Việt:
    - [Logarit](https://vi.wikipedia.org/wiki/Logarit)
    - [Chương II. Hàm số lũy thừa hàm số mũ và hàm số lôgarit - Toán 12](https://loigiaihay.com/chuong-ii-ham-so-luy-thua-ham-so-mu-va-ham-so-logarit-e1775.html)
- Video tiếng Việt:
    - [Logarit : Hành trình từ cực tiểu đến cực đại](https://www.youtube.com/watch?v=nTuBytg_5m8) - LƯU Ý: Tác giả của kênh Youtube Khoa Học và Chúng Ta này có nhiều video về khoa học ứng dụng hay. Tuy nhiên, ông này đã từng bị trục xuất khỏi nước vì phản động. Vì vậy, hãy thật tỉnh táo khi xem video trên kênh này. Nếu bạn phát hiện ra bất kỳ dấu hiệu nào về việc ông này truyền bá tư tưởng lệch lạc xen kẽ vào trong video, thì hãy thông báo với mình để mình loại bỏ video ra khỏi danh sách nhé.
    - [Ứng dụng Logarit trong thực tế - Thước đo động đất](https://www.youtube.com/watch?v=w4AP_kb2lmk)
- Bài viết tiếng Anh:
    - [Logarithm](https://en.wikipedia.org/wiki/Logarithm)
    - [Intro to Logarithms - Khan Academy](https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs/x2ec2f6f830c9fb89:log-intro/a/intro-to-logarithms)
- Video tiếng Anh:
    - [Logarithms, explained - Steve Kelly](https://www.youtube.com/watch?v=zzu2POfYv0Y)
    - [Logarithms explained Bob Ross style](https://www.youtube.com/watch?v=up21mvokyQ4)

## Số học

### Modulo
- Bài viết tiếng Việt:
    - [Modulo & GCD - VNOI Wiki](https://wiki.vnoi.info/translate/he/So-hoc-Phan-1-Modulo-gcd)
    - [Số học đồng dư (Phần 1): Đồng dư thức và Nghịch đảo modulo](https://viblo.asia/p/so-hoc-dong-du-phan-1-dong-du-thuc-va-nghich-dao-modulo-Az45b0aqZxY)
    - [Số học đồng dư (Phần 2): Phương trình đồng dư tuyến tính](https://viblo.asia/p/so-hoc-dong-du-phan-2-phuong-trinh-dong-du-tuyen-tinh-3RlL5Y6gLbB)
- Video tiếng Việt:
    - [Số học : Extended euclid (Euclid mở rộng), nghịch đảo modulo, phi hàm Euler [C++]](https://www.youtube.com/watch?v=7s-zFNzzmt8)
    - [[Toán Đại học] Định nghĩa và tính chất đồng dư thức - lý thuyết số](https://www.youtube.com/watch?v=zODG4gxh9Po)
- Bài viết tiếng Anh:
    - [Modular Arithmetic - USACO Guide](https://usaco.guide/gold/modular?lang=cpp)
    - [Number Theory - 1](https://www.hackerearth.com/practice/notes/number-theory-1/)
    - [Modular arithmetic](https://en.wikipedia.org/wiki/Modular_arithmetic)
    - [Modular Arithmetic - GeeksforGeeks](https://www.geeksforgeeks.org/modular-arithmetic/)
- Video tiếng Anh:
    - [This completely changed the way I see numbers | Modular Arithmetic Visually Explained](https://www.youtube.com/watch?v=lJ3CD9M3nEQ)
    - [What does a ≡ b (mod n) mean? Basic Modular Arithmetic, Congruence](https://www.youtube.com/watch?v=6dZLq77gSGU)
    - [What is Modular Arithmetic - Introduction to Modular Arithmetic - Cryptography](https://www.youtube.com/watch?v=Eg6CTCu8iio)

### Nghịch đảo modulo
- Bài viết tiếng Việt:
    - [Nghịch đảo modulo - VNOI Wiki](https://wiki.vnoi.info/algo/math/modular-inverse)
    - [Modular Inverse | Nghịch đảo module](https://vnspoj.github.io/wikivn/algebra/module-inverse)
    - [Số học đồng dư (Phần 1): Đồng dư thức và Nghịch đảo modulo](https://viblo.asia/p/so-hoc-dong-du-phan-1-dong-du-thuc-va-nghich-dao-modulo-Az45b0aqZxY)
- Video tiếng Việt:
    - [Số học: Extended euclid (Euclid mở rộng), nghịch đảo modulo, phi hàm Euler [C++]](https://www.youtube.com/watch?v=7s-zFNzzmt8)
- Bài viết tiếng Anh:
    - [Modular Inverse - USACO Guide](https://usaco.guide/gold/modular?lang=cpp#modular-inverse)
    - [Modular Multiplicative Inverse - cp-algorithms](https://cp-algorithms.com/algebra/module-inverse.html)
    - [Modular multiplicative inverse](https://en.wikipedia.org/wiki/Modular_multiplicative_inverse)
- Video tiếng Anh:
    - [How To Find The Inverse of a Number ( mod n ) - Inverses of Modular Arithmetic - Example](https://www.youtube.com/watch?v=shaQZg8bqUM)
    - [Multiplicative Inverse Mod n](https://www.youtube.com/watch?v=lh51Ww46Rng)

### Số nguyên tố
- Bài viết tiếng Việt:
    - [Kiểm tra số nguyên tố - VNOI Wiki](https://wiki.vnoi.info/algo/algebra/primality_check.md)
    - [Số học 2 - Số nguyên tố, Sàng Eratosthenes - VNOI Wiki](https://wiki.vnoi.info/translate/he/Number-Theory-2)
- Video tiếng Việt:
    - [Số nguyên tố : Con số kỳ bí và huyền diệu](https://www.youtube.com/watch?v=KMPAxJtmpl8) - LƯU Ý: Tác giả của kênh Youtube Khoa Học và Chúng Ta này có nhiều video về khoa học ứng dụng hay. Tuy nhiên, ông này đã từng bị trục xuất khỏi nước vì phản động. Vì vậy, hãy thật tỉnh táo khi xem video trên kênh này. Nếu bạn phát hiện ra bất kỳ dấu hiệu nào về việc ông này truyền bá tư tưởng lệch lạc xen kẽ vào trong video, thì hãy thông báo với mình để mình loại bỏ video ra khỏi danh sách nhé.
    - [Thuật Toán Kiểm Tra Số Nguyên Tố](https://www.youtube.com/watch?v=oIUueKdmRo8)
- Bài viết tiếng Anh:
    - Mục ***11.1.1. Primes and Factors*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
    - [Primality tests - cp-algorithms](https://cp-algorithms.com/algebra/primality_tests.html#fermat-primality-test)
    - [Primality test](https://en.wikipedia.org/wiki/Primality_test)
    - [Miller–Rabin primality test](https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test)
    - [Carmichael number](https://en.wikipedia.org/wiki/Carmichael_number)
- Video tiếng Anh:
    - [Primality (1 of 2: Fermat's Test) - Eddie Woo](https://www.youtube.com/watch?v=RcjxwCHRYfE)
    - [Fermat primality test - Khan Academy Labs](https://www.youtube.com/watch?v=oUMotDWVLpw)
    - [Fool-Proof Test for Primes - Numberphile](https://www.youtube.com/watch?v=HvMSRWTE2mI)

### Sàng nguyên tố
- Bài viết tiếng Việt:
    - [Sàng nguyên tố - VNOI Wiki](https://wiki.vnoi.info/algo/algebra/prime_sieve.md)
    - [Số học 2 - Số nguyên tố, Sàng Eratosthenes - VNOI Wiki](https://wiki.vnoi.info/translate/he/Number-Theory-2)
    - [Sàng Eratosthenes - Wikipedia](https://vi.wikipedia.org/wiki/S%C3%A0ng_Eratosthenes)
- Video tiếng Việt:
    - [Thuật Toán Sàng Số Nguyên Tố Eratosthenes](https://www.youtube.com/watch?v=YqT9grg_M60)
- Bài viết tiếng Anh:
    - Mục ***11.1.2. Sieve of Eratosthenes*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
    - [Sieve of Eratosthenes - cp-algorithms](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
    - [Sieve of Eratosthenes - Wikipedia](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)
    - Ngoài Sàng Eratosthenes, còn có một số sàng nguyên tố khác như:
        - [Sàng nguyên tố Atkin](https://en.wikipedia.org/wiki/Sieve_of_Atkin) với ĐPT $O(n)$
        - [Sàng nguyên tố Sundaram](https://en.wikipedia.org/wiki/Sieve_of_Sundaram) với ĐPT $O(n\log n)$
        - [Sàng Pritchard](https://en.wikipedia.org/wiki/Sieve_of_Pritchard) với ĐPT $O\left( \dfrac{n}{\log \log n} \right)$
        - ...
        - Tuy nhiên, khi gặp các bộ dữ liệu $n$ vào khoảng $10^6$ thì các sàng này hầu như chạy chậm hơn so với Sàng Eratosthenes thông thường.
- Video tiếng Anh:
    - [The Sieve of Eratosthenes - Eddie Woo](https://www.youtube.com/watch?v=Lj_SzTGr-G4)
    - [Sieve of Eratosthenes - Khan Academy](https://www.youtube.com/watch?v=klcIklsWzrY)
    - [Sieve Of Eratosthenes (visualized)](https://www.youtube.com/watch?v=dhfhu9Q5g8U)

### Giải thuật Euclid
- Bài viết tiếng Việt:
    - [Thuật toán Euclid - VNOI Wiki](https://wiki.vnoi.info/vi/algo/algebra/euclid)
    - [Giải thuật Euclid - Wikipedia](https://vi.wikipedia.org/wiki/Gi%E1%BA%A3i_thu%E1%BA%ADt_Euclid)
- Video tiếng Việt:
    - [Số học: Extended euclid (Euclid mở rộng), nghịch đảo modulo, phi hàm Euler [C++]](https://youtu.be/7s-zFNzzmt8?si=U8kMD2yVuxpLE5HO&t=1624)
    - [Giải thuật Euclid - Tìm ƯCLN - Giải thích thuật toán](https://www.youtube.com/watch?v=agrVghBxYUw)
- Bài viết tiếng Anh:
    - Mục ***11.1.3. Euclid's Algorithm*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
    - [Euclidean algorithm](https://en.wikipedia.org/wiki/Euclidean_algorithm)
    - [Euclidean algorithms (Basic and Extended) - GeeksforGeeks](https://www.geeksforgeeks.org/euclidean-algorithms-basic-and-extended/)
    - [The Euclidean Algorithm - Khan Academy](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/the-euclidean-algorithm)
    - [The Euclidean Algorithm - W3Schools](https://www.w3schools.com/dsa/dsa_ref_euclidean_algorithm.php)
- Video tiếng Anh:
    - [How to Find the Greatest Common Divisor by Using the Euclidian Algorithm](https://www.youtube.com/watch?v=JUzYl1TYMcU)
    - [Euclidean Algorithm - An example](https://www.youtube.com/watch?v=fwuj4yzoX1o)
    - [GCD - Euclidean Algorithm (Method 1)](https://www.youtube.com/watch?v=yHwneN6zJmU)
    - [GCD - Euclidean Algorithm (Method 2)](https://www.youtube.com/watch?v=svBx8u5bMEg)
    - [Euclidean algorithm - Discrete Mathematics](https://www.youtube.com/watch?v=cOwyHTiW4KE)

### Lũy thừa modulo
- Bài viết tiếng Việt:
    - [Thắc mắc về thuật toán (a^b)%c](https://daynhauhoc.com/t/thac-mac-ve-thuat-toan-a-b-c/81205)
- Video tiếng Việt:
    - [GATBMTT Hướng dẫn Tính lũy thừa modulo 4 cách tínhiới](https://www.youtube.com/watch?v=7UgxGjZX3Yw)
- Bài viết tiếng Anh:
    - Mục ***11.1.4. Modular Exponentiation*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
    - [Modular exponentiation](https://en.wikipedia.org/wiki/Modular_exponentiation)
- Video tiếng Anh:
    - [Modular Exponentiation (Part 1)](https://www.youtube.com/watch?v=_gYUlvcnjs0)
    - [Modular Exponentiation (Part 2)](https://www.youtube.com/watch?v=bg0P_3UiG5I)
    - [Modular exponentiation](https://www.youtube.com/watch?v=EHUgNLN8F1Y)
    - [[Discrete Math] Modular Exponentiation](https://www.youtube.com/watch?v=sL-YtCqDS90)
    - [Modular exponentiation made easy](https://www.youtube.com/watch?v=tTuWmcikE0Q)

### Lũy thừa nhị phân
- Bài viết tiếng Việt:
    - [Lũy thừa nhị phân](https://wiki.vnoi.info/algo/algebra/binary_exponentation.md)
    - [Binary Exponentiation | Luỹ thừa nhị phân](https://vnspoj.github.io/wikivn/algebra/binary-exp)
- Video tiếng Việt:
    - [Thuật toán nhân lũy thừa nhị phân(Binary Exponentiation)](https://www.youtube.com/watch?v=OZufZz1J_ls)
    - [Lũy Thừa Nhị Phân | Thuật Toán Tính Lũy Thừa Trong O(LogN)](https://www.youtube.com/watch?v=29tdEwMlCd4)
- Bài viết tiếng Anh:
    - [Binary Exponentiation - cp-algorithms](https://cp-algorithms.com/algebra/binary-exp.html)
    - [Binary Exponentiation for Competitive Programming](https://www.geeksforgeeks.org/binary-exponentiation-for-competitive-programming/)
- Video tiếng Anh:
    - [Binary Exponentiation - Errichto Algorithms](https://www.youtube.com/watch?v=L-Wzglnm4dM)
    - [Binary Exponentiation](https://www.youtube.com/watch?v=9VEqjAZxmeA)

### Phi hàm Euler
- Bài viết tiếng Việt:
    - [Số học 4 - Phi hàm Euler](https://wiki.vnoi.info/translate/he/Number-Theory-4)
    - [Hàm phi Euler](https://vi.wikipedia.org/wiki/H%C3%A0m_phi_Euler)
- Video tiếng Việt:
    - [Số học: Extended euclid (Euclid mở rộng), nghịch đảo modulo, phi hàm Euler [C++]](https://youtu.be/7s-zFNzzmt8?si=YAJwclJB7-HfTBCW&t=3807)
    - [Phi Hàm Euler | Kiểm Tra 2 Số Nguyên Tố Cùng Nhau](https://www.youtube.com/watch?v=aqW91x9Gi3k)
    - [Phi Hàm Euler Sử Dụng Sàng Số Nguyên Tố Biến Đổi](https://www.youtube.com/watch?v=8Wh54MRZH_U)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - Mục ***11.1.5. Euler’s Theorem*** trong cuốn [Guide to Competitive Programming](https://drive.google.com/file/d/1-V14oys49VJM6oipdcaIGcLzakaR_Hkn/view)
    - [Euler's totient function - Wikipedia](https://en.wikipedia.org/wiki/Euler%27s_totient_function)
    - [Euler's totient function - hackerearth](https://www.hackerearth.com/practice/notes/number-theory-iii/)
    - [Euler's totient function - cp-algorithms](https://cp-algorithms.com/algebra/phi-function.html)
- Video tiếng Anh:
    - [Euler's totient function | Khan Academy](https://youtu.be/qa_hksAzpSg?si=F99tFn-yhRZ0A1c_)
    - [Euler’s Totient Function (Phi Function)](https://youtu.be/DwQ7-k9LkJ4?si=C_5EpMlQMFWA_hNQ)
    - [Euler’s Totient Function (Solved Examples)](https://youtu.be/osge0_lZTaY?si=zYwOb6Efss3GgX_Y)
    - [Euler totient function made easy](https://youtu.be/EcAT1XmHouk?si=9-epQP_o6BMoGGfb)
    - [Euler's phi function |Solved examples |Cryptography](https://youtu.be/JcAxWlWgAY4?si=vzGKxRPZN9UnbulT)

### Giải phương trình
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Định lý Wilson
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Hàm Mobius
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Hàm nhân tính
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

## Tổ hợp

### Hệ số nhị thức
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Dãy số Catalan
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Bao hàm - Loại trừ
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Bổ đề Burnside
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Công thức Cayley
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Biến đổi Fourier nhanh - FFT
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

## Ma trận

### Nhân ma trận
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Khử nhân ma trận
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Truy hồi tuyến tính
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Ma trận kề
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Phép khử Gauss
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

## Xác suất

### Cấp
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

## Lý thuyết trò chơi

### Game State
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Trò chơi Nim
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

### Định lý Sprague–Grundy
- Bài viết tiếng Việt:
    - [Lập](https)
- Video tiếng Việt:
    - [Giới](https)
    - [VNOI](https)
- Bài viết tiếng Anh:
    - [Competitive](https)
- Video tiếng Anh:
    - [Starting](https)
    - [Intro](https)

