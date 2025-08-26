# Nvidia Custom Resolutions Backup Tool  
**(Công cụ sao lưu và khôi phục độ phân giải tùy chỉnh cho NVIDIA)**

---

## Features | Tính năng

- Backup custom resolutions to binary (.bin) or Registry (.reg) files.  
- Sao lưu độ phân giải tùy chỉnh ra file nhị phân (.bin) hoặc file Registry (.reg).  
- Restore from .bin or .reg files.  
- Khôi phục từ file .bin hoặc .reg.  
- Clear all custom resolutions.  
- Xóa toàn bộ các độ phân giải tùy chỉnh.  
- Restart NVIDIA driver to apply changes without rebooting Windows.  
- Khởi động lại driver NVIDIA để áp dụng thay đổi mà không cần khởi động lại máy.

---

## Important Notes | Lưu ý quan trọng

- Use `.bin` files for backups if you plan to restore on different machines, since `.bin` only stores resolution data, while `.reg` files include system-specific registry paths.  
- Nên dùng file `.bin` nếu bạn muốn khôi phục trên máy khác vì `.bin` chỉ chứa dữ liệu độ phân giải, còn `.reg` chứa đường dẫn registry có thể không đúng trên hệ khác.  
- Restart the driver or system after restoring or clearing custom resolutions for changes to take effect.  
- Khởi động lại driver hoặc máy tính sau khi thay đổi để áp dụng.  
- Custom resolutions will not appear in NVIDIA Control Panel until enabled manually.  
- Các độ phân giải tùy chỉnh sẽ không hiện trong NVIDIA Control Panel nếu chưa kích hoạt trong menu Custom Resolutions.

---

## Technology | Công nghệ sử dụng

This app uses Microsoft's **devcon** utility (embedded in the executable) to restart the NVIDIA driver without rebooting Windows.  
Ứng dụng dùng tiện ích **devcon** của Microsoft (được nhúng trong file) để khởi động lại driver NVIDIA mà không cần khởi động lại Windows.

---

## Changelog | Lịch sử cập nhật

- **1.0.2.2**: Improved active device detection method.  
- **1.0.2.0**: Added device selection for multiple NVIDIA GPUs; minor fixes.  
- **1.0.1.1**: Fixed driver restart verification.  
- **1.0.1.0**: Improved device search and driver restart reliability; reduced executable size.  
- **1.0.0.0**: Initial release.

---

## Download | Tải về

[Original Mediafire link from applejack](http://www.mediafire.com/?bug4ml9377isax5)  
(Link gốc từ applejack trên Mediafire)

---

## Author & Source | Tác giả & Nguồn gốc

Developed by **applejack**, originally posted on Guru3D forum in 2013.  
Phát triển bởi **applejack**, đăng tải trên diễn đàn Guru3D từ năm 2013.

Discussion & details:  
https://forums.guru3d.com/threads/nvidia-custom-resolutions-backup-tool.373845/

---

## Quick Usage | Hướng dẫn nhanh

1. Run as Administrator.  
2. Select your NVIDIA device if multiple cards present.  
3. Backup your custom resolutions before making changes.  
4. Clear or restore custom resolutions as needed.  
5. Restart driver to apply changes.  
6. Enable desired custom resolutions manually in NVIDIA Control Panel.

---

## Disclaimer | Lưu ý

Use carefully and backup before modifying. Designed for Windows 7+ and NVIDIA GPUs only.  
Sử dụng cẩn thận và sao lưu trước khi chỉnh sửa. Dành cho Windows 7 trở lên và card NVIDIA.

---

**Thanks to applejack for this great tool!**  
Cảm ơn applejack vì công cụ tuyệt vời này!
