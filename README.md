# Cẩm nang sống đáng đồng tiền · bản tiếng Việt

Bản dịch tiếng Việt của 《高性价比人生指南》, một cuốn sách mã nguồn mở xếp các lời khuyên
sống khoẻ, sống an toàn theo "đáng đồng tiền": mỗi mục ghi rõ tốn gì, được gì, bằng chứng
mạnh tới đâu, và chỉ dẫn bài báo khoa học hoặc tài liệu chính thức.

**Đọc online:** https://kms-hoangdao.github.io/how-to-live-better-vi/

## Nguồn

- Sách gốc: [eternity4719/HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter)
  (Unlicense, public domain). Bản dịch theo commit ghi trong file `UPSTREAM_REV`.
- Giao diện đọc: [cdyforever/how-to-live-better](https://github.com/cdyforever/how-to-live-better),
  `build.py` được Việt hoá phần hiển thị.

## Tình trạng

Đang dịch thử: **chương 1 (Đừng chết sớm), chương 2 (Đừng chết dần chết mòn), chương 4 (Đừng phí thời gian)**.
Các chương khác sẽ dịch sau.

## Lưu ý về bản dịch

- Bản dịch do AI thực hiện, có thể còn sai sót. Gặp lỗi thì mở issue giúp mình.
- Sách viết cho người đọc ở Trung Quốc. Luật, số điện thoại khẩn cấp, bảo hiểm, thủ tục…
  được **dịch sát và đánh dấu `(ND: ...)`**. Riêng số khẩn cấp có kèm số tương ứng ở Việt Nam
  (113 công an, 114 cứu hoả, 115 cấp cứu); các luật, hotline và thủ tục khác không tự thay bằng thông tin Việt Nam.
- Số liệu viết theo kiểu Việt Nam (dấu phẩy thập phân: 92,9%). Phần "Nguồn" giữ nguyên như bản gốc.
- Không thay thế tư vấn của bác sĩ hay luật sư.

## Cấu trúc

- `book/NN-*.md`: các chương đã dịch. Tiền tố trường (`- 成本：`, `- 说人话：`…) và dòng
  `<!-- 成本标签: ... -->` **cố ý giữ nguyên tiếng Trung**, vì `build.py` dùng chúng làm khoá
  để tính hạng "đáng làm" giống hệt bản gốc. Nhãn tiếng Việt chỉ thêm vào lúc dựng trang.
- `build.py`: dựng `index.html`, một file duy nhất, không phụ thuộc gì, đọc offline được.

## Dựng lại trang

```bash
python3 build.py all -o index.html
```

## Giấy phép

Nội dung gốc là Unlicense (public domain). Bản dịch và script cũng không giữ bản quyền.
