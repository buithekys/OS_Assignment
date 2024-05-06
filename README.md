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
 ┣ 📂include        # Header files.
 ┣ 📂input          # Samples input used for verification.
 ┣ 📂obj            # Include objects file after run make all.
 ┣ 📂output         # Samples output of the operating system.
 ┣ 📂src            # Source files.
 ┣ 📜Makefile       # Include scripts to compile source code. 
```
