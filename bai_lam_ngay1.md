

# Nguyễn Văn Mạnh Tùng
## Bài tập luyện tập ngày 1
### Phần 3
> Em sử dụng Windows PowerShell
1. 
```PowerShell
Pwd
Kết quả:
D:\Project_CNTT\testNMCNTT\trung-tam-tieng-anh
```
2.  
```PowerShell
ls -Force
Kết quả:
    Directory: D:\Project_CNTT\testNMCNTT\trung-tam-tieng-anh
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   8:30 PM                archive
d-----        10/20/2026   8:33 PM                data
d-----        10/20/2026   8:30 PM                docs
d-----        10/20/2026   8:33 PM                logs
d-----        10/20/2026   8:30 PM                media
d-----        10/20/2026   8:35 PM                Trung Tam Tieng Anh FINAL
------        10/19/2026  10:04 AM            902 bai_lam_ngay1.md
```
3. 
```PowerShell
mv '.\Trung Tam Tieng Anh FINAL\lich_hoc.txt' ".\docs"
mv ".\Trung Tam Tieng Anh FINAL\anh_lop_hoc.JPG" ".\media"
mv ".\Trung Tam Tieng Anh FINAL\logo_trung_tam.PNG" ".\media"
```
4. 
```PowerShell
cp ".\media\logo_trung_tam.PNG" ".\archive\"
```
5. 
```PowerShell
rm ".\Trung Tam Tieng Anh FINAL\temp_201.tmp"
rm ".\Trung Tam Tieng Anh FINAL\temp_202.tmp"
```
6. 
```PowerShell
cd ".\logs"
ls
cd..
```
7. 
```PowerShell
cd docs
cp "..\media\anh_lop_hoc.JPG" "..\archive\"
cd..
```
8.
```PowerShell
 Get-ChildItem -r -force
```
