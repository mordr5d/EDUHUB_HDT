# Phân tích vi phạm SOLID trong `ClubManager`

Ghi lại **≥ 4 vi phạm** (Nhiệm vụ 1). Các chú thích `SOLID violation` trong `ClubManager.cs` chỉ là gợi ý, hãy tự tìm thêm.

| # | Vị trí (method / dòng) | Nguyên tắc | Vì sao vi phạm | Hậu quả | Cách sửa (class/pattern) |
|---|---|---|---|---|---|
| 1 | `CreateClub` | SRP | | | |
| 2 | `CreateClub` (if/else Gmail/Yahoo) | OCP | | | |
| 3 | `CreateClub`, `AddMemberToClub`, `CreateEvent`, `PrintClubReport` (`File.AppendAllText`) | DIP | | | |
| 4 | `CreateEvent` (vòng lặp gửi email) | SRP + OCP | | | |
| 5 | `PrintClubReport` | OCP | | | |
