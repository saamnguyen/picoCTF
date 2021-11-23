# It is my birthday

## Mô tả:

I sent out 2 invitations to all of my friends for my birthday! I'll know if they get stolen because the two invites look similar, and they even have the same md5 hash, but they are slightly different! You wouldn't believe how long it took me to find a collision. Anyway, see if you're invited by submitting 2 PDFs to my website. http://mercury.picoctf.net:11590/
---


## Gợi ý:
1. Look at the category of this problem.
2. How may a PHP site check the rules in the description?
---

## Cách làm
Giờ mình thử tìm kiếm trên **[Google](google.com)** là "MD5 Collision" và mình tìm thấy trang **[Link]https://www.mscs.dal.ca/~selinger/md5collision/** . Mình thấy 2 file ở web đó là ~~hello~~ và ~~erase~~. Down 2 file đấy về rồi đổi thành tệp pdf.
Sau đó upload 2 file vừa đổi thành pdf lên **[link](http://mercury.picoctf.net:11590/)** bài it is my birth ở picoCTF
Flag sẽ hiện ở dòng 37.
---

## Flag
// FLAG: picoCTF{c0ngr4ts_u_r_1nv1t3d_5c8c5ce2}

- Bài này dựa trên sự va chạm của Hàm Băm MD5. Có nghĩa là đầu vào khác nhau nhưng sau khi băm lại ra chung một mã băm ~~ Có lẽ vậy ^^ ~~