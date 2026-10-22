# Quy Luật Viết Content

Skill giúp AI viết video ngắn theo cách người xem Việt Nam thật sự xem, thay vì điền vào một khuôn mẫu.

Khi được cho xem bài mẫu, AI thường học ra một quy trình cũ: nêu nhận định, liệt kê ý, kết bằng CTA. AI làm theo rất chuẩn nhưng không hiểu tư duy đằng sau. Kết quả là bài nào cũng giống bài nào.

Skill này không có khuôn. Nó dạy AI cách người xem Việt suy nghĩ khi lướt feed: chọn cách xưng hô, mở vòng tò mò, nói cụ thể bằng chất liệu Việt, để câu trước kéo câu sau. Nhờ vậy AI suy luận lại từ đầu cho từng video.

Làm bởi **Vincent Vu** ([@vincentvuai](https://beacons.ai/vincentvuai)).

Lấy cảm hứng từ [content-principles](https://github.com/aiwithremy/content-principles) của Remy Gaskell. Bản này được viết lại cho người Việt và thị trường Việt Nam.

## Cài đặt

**Cách nhanh nhất:** dán link repo này vào Claude Code (hoặc bất kỳ AI agent nào cài được skill) và nói:

> Cài skill này cho tôi: https://github.com/AIClubVN/quy-luat-content-viet

**Claude Code, cài thủ công:** copy folder `quy-luat-content-viet` vào `~/.claude/skills/`.

**Claude.ai hoặc app Claude**
1. Tải file [`quy-luat-content-viet.zip`](quy-luat-content-viet.zip) trong repo này về máy. Không giải nén.
2. Mở Claude, vào **Customize**, chọn **Skills**.
3. Tải file ZIP lên, rồi bật skill.

**ChatGPT**
1. Tạo một Custom GPT hoặc một Project mới.
2. Mở file [`quy-luat-content-viet/SKILL.md`](quy-luat-content-viet/SKILL.md) và copy toàn bộ nội dung.
3. Dán vào phần **Instructions**. File dưới 6.000 ký tự, vừa giới hạn 8.000 ký tự của Custom GPT.

## Cách dùng

Nhờ AI như bình thường. Ví dụ:
- "Viết kịch bản TikTok 45 giây về cách dùng AI trả lời tin nhắn khách cho shop mỹ phẩm."
- "Cho mình 10 câu hook cho video này."

Hoặc dán kịch bản bạn đã viết và nhờ AI góp ý theo skill Quy Luật Viết Content.

## Giấy phép

Skill được chia sẻ theo giấy phép [CC BY 4.0](LICENSE). Bạn được dùng, chia sẻ và chỉnh sửa, kể cả cho mục đích thương mại, miễn là ghi tên Vincent Vu.

## Theo dõi thêm

Kênh của Vincent Vu: [@vincentvuai](https://beacons.ai/vincentvuai) trên TikTok, Instagram và Facebook.
