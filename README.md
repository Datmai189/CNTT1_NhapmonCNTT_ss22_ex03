1. Vấn đề là gì?
AI đưa ra một câu lệnh Terminal để sửa lỗi “Path not found”, nhưng lệnh có thể sai do AI Hallucination, không phù hợp với hệ điều hành hoặc can thiệp nguy hiểm vào hệ thống
2. Yêu cầu đề bài
- Phân tích tình huống theo mô hình IPO
- Kiểm chứng câu lệnh bằng Stack Overflow hoặc tài liệu chính thức
- Kết luận lệnh an toàn hay không an toàn
- Viết prompt yêu cầu AI tự giải thích câu lệnh trước khi thực thi
3. Cách làm
Input: Câu lệnh AI cung cấp, hệ điều hành và phiên bản Python
Process: Không chạy ngay; tìm lỗi bằng "Path not found" Python site:stackoverflow.com hoặc kiểm tra tại docs.python.org. Đặc biệt cẩn thận nếu lệnh có sudo, rm -rf hoặc sửa PATH
Output: Chỉ chạy khi lệnh phù hợp với tài liệu chính thức; nếu chưa xác minh được thì coi là không an toàn
Prompt hỏi ngược AI:
Hãy giải thích tác dụng, rủi ro và cách hoàn tác câu lệnh này. Cung cấp nguồn chính thức và một phương án an toàn hơn trước khi tôi thực thi
