# Nguyễn Đình Tú

**FinTech · Tài chính và dữ liệu · AI ứng dụng**

Mình đang học Công nghệ Tài chính tại Học viện Công nghệ Bưu chính Viễn thông (PTIT). Portfolio này ghi lại cách mình biến câu hỏi tài chính thành prototype có thể chạy và kiểm tra: dữ liệu lấy từ đâu, phép tính ra sao, phần nào còn là giả định.

## Bắt đầu từ hai dự án sát FinTech nhất

### Financial Statement Evidence API

**Một chỉ số tài chính có thể lần ngược về ô dữ liệu nào?** Dự án đọc báo cáo XLSX/PDF, chuẩn hóa dữ kiện, tính chỉ số bằng Decimal và giữ liên kết về ô nguồn hoặc vùng PDF để người dùng kiểm tra.

<a href="https://github.com/ndt0610/financial-statement-evidence-api"><img src="https://raw.githubusercontent.com/ndt0610/financial-statement-evidence-api/main/docs/images/financial-evidence-source-trace.png" alt="Giao diện truy nguyên doanh thu thuần về ô nguồn trong báo cáo tài chính" width="100%"></a>

[Mở repository: Financial Statement Evidence API](https://github.com/ndt0610/financial-statement-evidence-api) · *Ảnh dùng bộ dữ liệu tổng hợp để minh họa truy nguyên nguồn, không phải báo cáo của doanh nghiệp thật.*

### Equara — FinBERT, tin–giá và danh mục đầu tư

**Từ sắc thái tiêu đề đến nhãn có giải thích:** nhóm tin gần trùng, giảm trọng số tin cũ, đối chiếu giá 5 phiên và hiển thị nhánh đã kích hoạt trong bộ quy tắc thử nghiệm. Cùng repository có nghiên cứu FinBERT cho EGX và danh mục Mỹ Phase 1.

<a href="https://github.com/ndt0610/equara-finbert-egx"><img src="https://raw.githubusercontent.com/ndt0610/equara-finbert-egx/main/docs/images/decision-label-etel.png" alt="Kết quả nhãn thử nghiệm Mua cho ETEL cùng điểm tin, giá 5 phiên và ngưỡng lịch sử" width="100%"></a>

[Mở repository: Equara](https://github.com/ndt0610/equara-finbert-egx) · *Dự án cá nhân; có sử dụng AI coding assistants và ghi rõ phạm vi hỗ trợ. Nhãn không phải khuyến nghị giao dịch.*

## Nghiên cứu tài chính và tích hợp hệ thống

| Dự án | Nội dung có thể kiểm tra |
| --- | --- |
| [Vietnam Yield-Curve Research](https://github.com/ndt0610/ryc-vietnam-yield-curve) | So sánh giữ/bán trái phiếu ở cùng ngày tiền mặt cuối kỳ; kết quả chạy trên kịch bản khai báo, ghi rõ giả định synthetic và độ phân biệt theo ε. |
| [Bitcoin Regtest Transaction Demo](https://github.com/ndt0610/bitcoin-regtest-transaction-demo) | Theo dõi vòng đời giao dịch Bitcoin trên Regtest cục bộ: UTXO, ký, phát giao dịch và xác nhận. |
| [Blockchain Balance API](https://github.com/ndt0610/blockchain-balance-api) | API đọc số dư đa chuỗi với adapter provider và định danh tài sản có cấu trúc. |
| [RAG Document Assistant](https://github.com/ndt0610/rag-document-assistant) | Hỏi đáp trên PDF với truy xuất theo trang, xử lý ingestion bất đồng bộ và trích dẫn nguồn. |

## Học máy, thuật toán và trò chơi

- [3D k-NN Explorer](https://github.com/ndt0610/knn-3d-explorer) — khoảng cách Euclid, xếp hạng láng giềng và biểu diễn dữ liệu 3D tương tác.
- [Gradient-Boosted Trees Workbench](https://github.com/ndt0610/gradient-boosted-trees-workbench) — xem split, gain, trọng số lá và early stopping trong mô hình boosting giáo dục.
- [Q-learning Maze](https://github.com/ndt0610/qlearning-maze) — huấn luyện Q-table có seed, theo dõi reward và kiểm tra đường đi greedy.
- [Q-learning Tic-Tac-Toe](https://github.com/ndt0610/qlearning-tic-tac-toe) — self-play, reward trạng thái kết thúc và đối chiếu với minimax.
- [N-Queens Visualizer](https://github.com/ndt0610/n-queens-visualizer) — quay lui có quan sát tiến trình đặt/hủy hậu.
- [Sudoku Solver and Board](https://github.com/ndt0610/sudoku-solver-visualizer) — bàn chơi tương tác và solver dùng heuristic MRV.

## Công cụ thể hiện qua dự án

Python · SQL · Excel · Power BI · FastAPI · pandas · scikit-learn · Transformers/FinBERT · JavaScript · React · Streamlit · Pygame

Đây là các công cụ xuất hiện trong prototype và bài tập; danh sách không hàm ý kinh nghiệm vận hành hệ thống production. Dự án cá nhân và bài tập học phần được gắn nhãn riêng; hỗ trợ AI coding được ghi rõ tại repository liên quan.
