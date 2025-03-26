

---

### **Danh sách các tính năng chính**

Dựa trên cốt truyện và gamification, đây là các tính năng cốt lõi của ứng dụng:

1. **Tạo nhân vật chuyển sinh**:
    - Người chơi nhập tên và chọn ngoại hình cơ bản (chiến binh, pháp sư, nông dân, v.v.).
    - Khởi đầu với 0 EXP, Level 1, không huy hiệu.
2. **Lựa chọn và nhập mục tiêu cuộc đời**:
    - Cung cấp 7 mục tiêu ban đầu để người chơi chọn (dựa trên 7 chiều cuộc sống: sức khỏe, trí tuệ, tinh thần, xã hội, môi trường, cảm xúc, nghề nghiệp).
    - Sau khi chọn, người chơi nhập chi tiết mục tiêu lớn (ví dụ: “Trở thành kiếm sĩ mạnh nhất trong 1 năm”).
3. **AI (System) tạo kế hoạch**:
    - AI hỏi người chơi về ngày bắt đầu, thời gian mỗi ngày, và chia kế hoạch thành nhiệm vụ nhỏ (theo ngày/tuần/tháng).
    - Tạo danh sách nhiệm vụ cụ thể (to-do list) dựa trên mục tiêu.
4. **Bản đồ hành trình (Journey Map)**:
    - Hiển thị nhiệm vụ dưới dạng các chấm trên bản đồ (phong cách RPG).
    - Theo dõi tiến độ hàng ngày và tổng quát.
5. **Hoàn thành nhiệm vụ**:
    - Người chơi đánh dấu hoàn thành nhiệm vụ qua thông báo hoặc giao diện.
    - Nhận EXP và phần thưởng khi hoàn thành.
6. **Gamification**:
    - **EXP (Điểm kinh nghiệm)**: Tăng khi hoàn thành nhiệm vụ (ví dụ: 10 EXP/nhiệm vụ nhỏ, 20 EXP/nhiệm vụ lớn).
    - **Cấp độ**: Tăng khi đạt 100 EXP (Level 1 → Level 2).
    - **Huy hiệu**: Phần thưởng cho thành tích (ví dụ: “Ý chí thép” sau 3 ngày liên tục, “Hiệp sĩ tập sự” sau 10 nhiệm vụ).
    - **Thanh tiến độ**: Hiển thị % hoàn thành mục tiêu lớn và cấp độ.
7. **Theo dõi mục tiêu cuộc đời**:
    - Hiển thị tiến độ tổng quát của mục tiêu lớn.
    - Kết thúc hành trình khi đạt 100% (kèm phần thưởng lớn).
8. **Hồ sơ nhân vật**:
    - Theo dõi EXP, cấp độ, huy hiệu, và streak (ngày liên tục hoàn thành).

---

### **Ghi lại 7 màn hình chức năng**

Dưới đây là mô tả chi tiết 7 màn hình, được điều chỉnh theo yêu cầu mới (đặc biệt là **Set Life Goal** với 7 mục tiêu để lựa chọn):

#### **1. Introduction (Giới thiệu cốt truyện, tạo nhân vật)**

- **Mô tả**:
    - Animation: Nhân vật tỉnh dậy trong thế giới mới (rừng, ánh sáng lóe lên).
    - AI/System: “Chào mừng đến kiếp sống mới, kẻ chuyển sinh. Ta là Hệ thống, sẽ dẫn dắt ngươi. Hãy cho ta biết ngươi là ai.”
    - Ô nhập tên: “Nhập tên nhân vật” (ví dụ: “Kael”).
    - Chọn ngoại hình: 3-5 lựa chọn (chiến binh với kiếm, pháp sư với gậy, nông dân với cuốc).
    - Nút: “Bắt đầu hành trình”.
- **Gamification**: +10 EXP khi hoàn thành, hiệu ứng ánh sáng.

#### **2. Set Life Goal (Chọn và nhập mục tiêu cuộc đời)**

- **Mô tả**:
    - **Bối cảnh**: Nhân vật đứng trước “Bảy Cánh Cửa Định Mệnh” (mỗi cửa đại diện 1 mục tiêu).
    - **7 mục tiêu để lựa chọn** (dựa trên 7 chiều cuộc sống):
        1. **Sức khỏe**: “Trở thành người khỏe mạnh nhất” (biểu tượng: cơ bắp).
        2. **Trí tuệ**: “Nắm vững tri thức vĩ đại” (biểu tượng: sách).
        3. **Tinh thần**: “Đạt được sự bình an nội tâm” (biểu tượng: hoa sen).
        4. **Xã hội**: “Xây dựng tình bạn bền vững” (biểu tượng: tay nắm).
        5. **Môi trường**: “Bảo vệ thế giới tự nhiên” (biểu tượng: cây xanh).
        6. **Cảm xúc**: “Kiểm soát cảm xúc hoàn hảo” (biểu tượng: trái tim).
        7. **Nghề nghiệp**: “Trở thành bậc thầy trong nghề” (biểu tượng: cúp).
    - **Sau khi chọn**: Ô nhập liệu xuất hiện để nhập chi tiết (ví dụ: Chọn “Sức khỏe” → “Giảm 5kg trong 2 tháng”).
    - Nút: “Xác nhận mục tiêu”.
- **Gamification**: +20 EXP khi xác nhận, hiệu ứng cửa mở ra.

#### **3. Plan Creation (AI/System hỏi để tạo kế hoạch)**

- **Mô tả**:
    - **Bối cảnh**: Nhân vật trong “Phòng Kế Hoạch” với AI/System dạng hologram.
    - **Chat với AI**:
        - “Ngươi muốn bắt đầu từ khi nào?” → Dropdown chọn ngày.
        - “Ngươi có thể dành bao nhiêu thời gian mỗi ngày?” → Ô nhập số phút (ví dụ: “30 phút”).
        - “Ta sẽ chia hành trình thành từng bước. Ngươi muốn xem theo ngày, tuần, hay tháng?” → 3 nút chọn.
    - Nút: “Nhận kế hoạch”.
- **Gamification**: +5 EXP mỗi câu trả lời, +10 EXP khi nhận kế hoạch, hiệu ứng bản đồ phát sáng.

#### **4. Journey Map (Bản đồ hành trình với nhiệm vụ hàng ngày)**

- **Mô tả**:
    - **Bối cảnh**: Bản đồ phong cách RPG (đường mòn qua rừng, núi).
    - **Nội dung**:
        - Các chấm trên bản đồ là nhiệm vụ (ví dụ: “Tập kiếm 30 phút” → Chấm 1).
        - Danh sách nhiệm vụ hôm nay:
            - [ ]  Tập kiếm 30 phút (15 EXP).
            - [ ]  Chạy bộ 20 phút (10 EXP).
        - Thanh tiến độ: “5% đến kiếm sĩ mạnh nhất” + “Level 2 - 80/100 EXP”.
    - Nút: “Bắt đầu nhiệm vụ”.
- **Gamification**: +EXP khi hoàn thành, nhân vật di chuyển trên bản đồ, huy hiệu sau chuỗi ngày.

#### **5. Task Completion (Nhiệm vụ cụ thể + đánh dấu hoàn thành)**

- **Mô tả**:
    - **Thông báo đẩy**: “Hệ thống: Đã đến lúc tập kiếm 30 phút! Hoàn thành để nhận 15 EXP!”.
    - **Giao diện**:
        - Bối cảnh: Nhân vật trước thử thách (kiếm cắm trên đá).
        - Nhiệm vụ: “Tập kiếm 30 phút”.
        - Nút: “Hoàn thành” (kiếm sáng lên) + “Bỏ qua”.
    - **Kết quả**: Animation kiếm rút ra + “+15 EXP” + pop-up “Nhiệm vụ hoàn tất!”.
- **Gamification**: +EXP, huy hiệu “Ý chí thép” nếu hoàn thành 3 ngày liên tục.

#### **6. Character Profile (Hiển thị EXP, cấp độ, huy hiệu)**

- **Mô tả**:
    - **Bối cảnh**: Nhân vật trước gương ma thuật.
    - **Nội dung**:
        - Tên + Level (ví dụ: “Kael - Level 5”).
        - Tổng EXP: “1250”.
        - Thanh tiến độ cấp độ: “80/100 EXP”.
        - Huy hiệu: “Ý chí thép”, “Hiệp sĩ tập sự”.
        - Streak: “5 ngày”.
    - Nút: “Khoe thành tích” (chia sẻ mạng xã hội).
- **Gamification**: Hiệu ứng gương sáng, +10 EXP khi khoe.

#### **7. Life Goal (Theo dõi tiến độ mục tiêu lớn)**

- **Mô tả**:
    - **Bối cảnh**: Nhân vật trước “Cổng Định Mệnh”.
    - **Nội dung**:
        - Mục tiêu: “Trở thành kiếm sĩ mạnh nhất”.
        - Tiến độ: “75% hoàn thành”.
        - Nhiệm vụ còn lại: “20/100”.
        - Khi 100%: Animation cổng mở + “Ngươi đã hoàn thành mục tiêu cuộc đời!”.
- **Gamification**: Huy hiệu mỗi 25% (ví dụ: “Nửa đường vinh quang”), +500 EXP khi hoàn thành.

---
