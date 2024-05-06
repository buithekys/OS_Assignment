# Simple Operating System

## Tiên quyết: Phải được thực thi trên Linux. Nếu máy tính là Window, có thể cân nhắc sử dụng ứng dụng cho phép dùng terminal của Linux
- `Ubuntu` 22.04 LTS
  
## Commands
- `make all`: để compile tất cả các file code
- `./os [tên file input] [tên file output]`: chạy code  

Ví dụ:
make all
./os os_0_mlq_paging os_0_mlq_paging.output


## Cấu trúc của BTL:
```
 ┣ 📂include        # Các file header.
 ┣ 📂input          # Một vài Input có sẵn.
 ┣ 📂obj            # Các Object file dùng cho sau khi make all.
 ┣ 📂output         # Một vài output mẫu.
 ┣ 📂src            # File code.
 ┣ 📜Makefile       # File để compile toàn bộ code. 
```
