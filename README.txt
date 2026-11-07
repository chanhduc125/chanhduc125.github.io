HSK OFFLINE STUDY — HSK 2.0 CẤP 1–4

- HSK 1: khoảng 150 mục từ
- HSK 2: khoảng 150 mục từ
- HSK 3: khoảng 300 mục từ
- HSK 4: 598 mục từ mới (theo bộ clem109; có tài liệu tham chiếu HSK 2.0 thường ghi 598).

CÁCH DÙNG
1. Giải nén ZIP, mở index.html bằng Chrome/Edge.
2. Lần đầu cần Internet để tải danh sách HSK 1–4, thư viện Hanzi Writer, dữ liệu nét chữ và bộ chuyển Pinyin.
3. Chọn tab HSK 1/2/3/4. Rê vào thẻ từ để nghe phát âm và xem nét chữ.
4. Rê vào ngôi sao ☆ bên dưới mỗi từ để mở một câu ví dụ riêng. Từ đang học được tô đỏ đậm; Pinyin nằm ngay dưới; rê vào câu để tự đọc.
5. Bấm “Lưu dữ liệu nét & ví dụ offline” để lưu bộ câu, thư viện Pinyin và dữ liệu nét vào IndexedDB. Mỗi ký tự phải được tải ít nhất một lần trước khi dùng offline.

CÂU VÍ DỤ
Ứng dụng chọn tối đa một câu có ngữ cảnh cho từng từ, ưu tiên bộ câu tiếng Trung có phân tách từ vựng và nghĩa từng từ; mỗi câu chỉ gán cho một mục từ để tránh lặp lại và tô đỏ đúng vị trí từ đang học. Nếu bộ dữ liệu câu và ví dụ gốc không có câu phù hợp, ứng dụng sẽ báo chưa có câu thay vì ghép từ vào câu mẫu chung. Bộ câu chính được tải online lần đầu và lưu trong IndexedDB để dùng offline sau khi đã tải.

PHÁT ÂM
Sử dụng SpeechSynthesis zh-CN của hệ điều hành. Muốn nghe offline cần cài giọng tiếng Trung trên máy. Trình duyệt không có giọng zh-CN sẽ không thể đọc.

NGUỒN & GIẤY PHÉP
- Từ vựng: https://github.com/clem109/hsk-vocabulary (MIT)
- Câu ví dụ: https://github.com/no7z/hsk-sentences-audio (bộ câu HSK 3.0, CC BY-SA 4.0); ứng dụng chọn các câu có token khớp chính xác với từ HSK 2.0 đang học.
- Nét chữ: https://github.com/chanind/hanzi-writer-data ; https://github.com/skishore/makemeahanzi (Arphic Public License)
- Engine: https://github.com/chanind/hanzi-writer (MIT)
- Pinyin: https://github.com/zh-lx/pinyin-pro (MIT)

LƯU Ý
Dữ liệu từ vựng tải từ các tệp JSON raw trên GitHub ở lần chạy đầu. Ứng dụng cache cục bộ trong IndexedDB. Danh sách từ vựng hiển thị vẫn là HSK 2.0. Nguồn câu ví dụ phụ trợ được chấm theo HSK 3.0, vì vậy một số từ riêng của danh sách HSK 2.0 có thể chưa có câu khớp phù hợp.
