# Quyền sử dụng tài nguyên

Hình ảnh được dựng nguyên bản bằng Canvas trong src/render/Art.ts, VoxelModels.ts và CanvasRenderer.ts. Nhịp nhảy ô, mô hình khối và camera cuộn lấy cảm hứng từ Crossy Road, nhưng không dùng mã, hình ảnh hoặc âm thanh của trò chơi đó. Nhân vật bốn hướng, xe hai chiều, vật phẩm, quầy hàng và nhà dùng chung bảng màu/ánh sáng Tết Việt. Tài nguyên hình ảnh là mã vẽ vector đóng gói trong bản build.

Nhạc xuan.wav và nền cho.wav được tổng hợp riêng cho game bằng scripts/generate-audio.mjs. Nhạc dùng giai điệu nguyên bản với thang ngũ cung, mô phỏng sáo và dây gảy; không sao chép bản nhạc có bản quyền. Hiệu ứng ngắn tổng hợp bằng Web Audio. Mã nguồn và tài nguyên nguyên bản được cung cấp theo MIT (xem LICENSE).

Be Vietnam Pro của tác giả được ghi trong fonts/OFL.txt, dùng theo SIL Open Font License 1.1. Phông được đóng gói tại fonts/BeVietnamPro-Regular.ttf.

Giọng tổng hợp đã được loại bỏ khỏi mã nguồn và gói tài nguyên ở lần sửa theo phản hồi. Game chỉ phát nhạc không lời và hiệu ứng không có giọng nói.

Bộ tranh nhà sáu trạng thái trong art/nha-tet-tranh-lua.png được tạo mới bằng imagegen tích hợp theo chỉ đạo của dự án, lấy cảm hứng từ tranh lụa và màu nước Việt Nam. Không sao chép tác phẩm hay mô phỏng một họa sĩ cụ thể. Xem art/ART_DIRECTION.md.
