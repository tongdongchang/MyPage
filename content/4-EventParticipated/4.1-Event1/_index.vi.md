---
title: "Sự kiện 1"
date: 2026-05-02
weight: 4
chapter: false
pre: " <b> 3.1. </b> "
---

### Mục đích sự kiện
- Giới thiệu các xu hướng **Platform Engineering** hiện đại và lộ trình nghề nghiệp.
- Trình bày phương pháp và công cụ **DevOps cho Generative AI (GenAIOps)** trên AWS.
- Chia sẻ kinh nghiệm triển khai **GenAI đa phương thức** ở quy mô production.
- Khám phá cách tận dụng **Amazon CloudFront** làm nền tảng cho mọi loại workload, từ edge tới origin.

### Danh sách diễn giả
Sự kiện quy tụ nhiều chuyên gia từ AWS và cộng đồng công nghệ, bao gồm:
- **Ông Phúc Đặng** – Engineering Manager, GotymeX
- **Ông Pháp Nguyễn** – Cloud Engineer, VPBank
- **Ông Trình Nguyễn** – DevOps Engineer, FCAJ
- Cùng các khách mời khác từ hệ sinh thái AWS.

### Nội dung nổi bật
Sự kiện buổi sáng được chia thành năm phiên chính:

**1. Xây dựng Platform Engineering hiện đại và lộ trình nghề nghiệp (09:00 – 09:45)**
- Khám phá văn hóa công ty, cơ hội thực tập và cách tương tác với diễn giả qua nền tảng Q&A.
- Giới thiệu Platform Engineering – cầu nối giữa phát triển và vận hành, giúp tăng tốc độ phát hành và độ tin cậy của hệ thống.
- Vạch ra lộ trình nghề nghiệp: Kỹ sư phần mềm → Kỹ sư Platform → Kiến trúc sư.

**2. GenAIOps thiết yếu – DevOps cho ứng dụng Generative AI (09:45 – 10:15)**
- Ôn lại các nguyên tắc DevOps cốt lõi trên AWS và các tài nguyên học tập liên quan.
- Trình bày các mô hình GenAIOps thực tế: sử dụng Amazon Bedrock, AgentCore Observability, EKS và Langfuse để quan sát và quản lý vòng đời của ứng dụng GenAI.

**3. Vận chuyển mã nguồn trong kỷ nguyên Agentic (10:15 – 10:45)**
- Thảo luận về “làm thế nào để vận chuyển mã nguồn nhanh chóng và an toàn trong thời đại của các tác tử AI”.
- Giới thiệu các công cụ: đánh giá mã bằng AI, kiểm thử tự động, pipeline tự phục hồi.
- Demo trực tiếp quy trình CI/CD được tích hợp với một tác tử AI.

**4. GenAI đa phương thức cấp production trên AWS (11:00 – 11:30)**
- Trình bày ngăn xếp ứng dụng AI mới: tìm kiếm đa phương thức với Nova Embeddings, GraphRAG cho tri thức doanh nghiệp.
- Kiến trúc quy trình đa tác tử (multi‑agent) phối hợp các tác vụ phức tạp.
- Đảm bảo an toàn và khả năng quan sát (observability) cho GenAI trên production.

**5. Từ Edge tới Origin: CloudFront làm nền tảng (11:30 – 12:00)**
- Cho thấy Amazon CloudFront có thể làm nền tảng cho mọi loại workload, không chỉ là CDN.
- Chiến lược tối ưu chi phí: caching, nén, lựa chọn region.
- Các tính năng bảo mật: WAF, Shield, OAC; cải thiện độ tin cậy và hiệu năng.

### Những gì tôi học được
**Tư duy nền tảng**
- Platform Engineering không chỉ là công cụ – đó là văn hóa chia sẻ trách nhiệm giữa Dev và Ops.
- Internal Developer Platform (IDP) giúp giảm tải nhận thức cho lập trình viên, cho phép họ tập trung vào code.

**DevOps cho AI**
- GenAIOps mở rộng các nguyên tắc DevOps truyền thống: cần theo dõi chất lượng đầu ra của mô hình, quản lý prompt và kiểm soát chi phí suy luận.
- Các công cụ như Langfuse và Bedrock Agents cho phép quan sát và tự động hóa.

**Xu hướng Agentic**
- Các tác tử AI không còn chỉ là chatbot – chúng có thể lập kế hoạch, sử dụng công cụ và gọi API để hoàn thành mục tiêu.
- Pipeline phải được thiết kế với khả năng rollback tự động và có sự phê duyệt của con người ở các bước quan trọng.

**Kiến trúc GenAI đa phương thức**
- Tìm kiếm đa phương thức (văn bản, hình ảnh, âm thanh) làm phong phú trải nghiệm người dùng.
- GraphRAG cải thiện độ chính xác bằng cách kết hợp đồ thị tri thức với truy xuất.

**CloudFront vượt ra ngoài CDN**
- CloudFront có thể hoạt động như reverse proxy, bảo vệ origin và giảm tải cho backend.
- Edge computing (Lambda@Edge, CloudFront Functions) cho phép chạy logic ngay tại edge.

### Ứng dụng vào công việc của tôi
- **Dự án website nghe nhạc**: Áp dụng CloudFront làm CDN cho frontend React và reverse proxy cho backend Django, cải thiện tốc độ tải và bảo mật.
- **DevOps**: Tích hợp thực hành GenAIOps vào các tính năng AI tương lai (ví dụ: gợi ý bài hát bằng machine learning).
- **Platform Engineering**: Tạo môi trường phát triển nội bộ với các template CloudFormation để nhóm có thể nhanh chóng tái tạo cơ sở hạ tầng.
- **Học tập**: Sử dụng Langfuse để quan sát các mô hình GenAI thử nghiệm, hiểu sâu hơn về khả năng quan sát.

### Trải nghiệm sự kiện
Sự kiện diễn ra trong không khí cởi mở và tương tác cao. Phiên Q&A cho phép tôi hỏi trực tiếp các chuyên gia về lộ trình nghề nghiệp và cách bắt đầu với Platform Engineering.

Các bản demo trực tiếp – đặc biệt là “Shipping Code in the Agentic Era” – đã cho tôi hình dung rõ ràng về cách một tác tử AI có thể tự động xem xét mã và đề xuất cải tiến ngay trong một pull request.

Tôi đặc biệt ấn tượng với bài nói về CloudFront: trước đây tôi chỉ nghĩ CloudFront đơn thuần là CDN, nhưng giờ tôi hiểu nó có thể làm nền tảng cho bảo mật, tối ưu chi phí và cả edge computing.

### Bài học rút ra
- **Luôn bắt đầu từ nhu cầu người dùng**: Dù là GenAI hay Platform Engineering, mọi giải pháp phải giải quyết vấn đề kinh doanh thực tế.
- **Tiếp cận theo từng giai đoạn**: Đừng áp dụng mọi công nghệ mới cùng một lúc. Xây dựng lộ trình, chạy thử nghiệm (pilot) trước, sau đó mở rộng.
- **Đầu tư vào khả năng quan sát**: Đặc biệt với các hệ thống GenAI, việc giám sát và đo lường chất lượng đầu ra là rất quan trọng.
- **Tận dụng dịch vụ được quản lý**: AWS cung cấp nhiều dịch vụ giúp giảm gánh nặng vận hành và cho phép các nhóm tập trung vào logic nghiệp vụ.