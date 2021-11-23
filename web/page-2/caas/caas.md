# Cass
---

## Mô tả:
Now presenting **(cowsay as a service)[https://caas.mars.picoctf.net/]**
---

## Cách làm:
Theo đường dẫn thì https://caas.mars.picoctf.net/cowsay/{message} mình sẽ thử thêm chữ gì đó vào message.
Thì nó ra: 
![1](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/1.png) 
![2](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/2.png) 

Tiếp theo mình thử thêm {7\*7} hoặc {10\*10} vào message thì thấy:
![4](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/4.png) 
![5](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/5.png) 

Hình như là *Server-Side Template Injection* 
Sau đó mình ghi trên url:
![6](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/6.png) 
hoặc
![10](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/10.png) 

thì sẽ hiện ra:
![7](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/7.png) 
![12](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/12.png) 

Giờ ta đọc file falg.txt sẽ ra flag:
![8](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/8.png) 
![13](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/13.png) 

# FLAG:
picoCTF{moooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo0o}

![15](https://github.com/samukma/picoCTF/blob/main/web/page-2/caas/img/15.png)