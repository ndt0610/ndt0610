# Nguyễn Đình Tú

**Công nghệ Tài chính (PTIT) · Phân tích tài chính · Dữ liệu số**

Mình đang chuẩn bị thực tập trong mảng phân tích nghiệp vụ, vận hành dữ liệu hoặc ngân hàng số. Portfolio tập trung vào những việc có thể kiểm tra trong dự án: dữ liệu lấy từ đâu, cách xử lý ra sao và phần nào vẫn là giả định. Bài tập học phần và dự án cá nhân được ghi riêng.

## Hai dự án nên xem trước

### Financial Statement Evidence API

**Một chỉ số trên màn hình truy ngược về dòng nào trong báo cáo?** Prototype đọc XLSX/PDF, giữ vị trí nguồn cho dữ kiện và tính toán để người xem kiểm tra căn cứ.

<a href="https://github.com/ndt0610/financial-statement-evidence-api"><img src="https://raw.githubusercontent.com/ndt0610/financial-statement-evidence-api/main/docs/images/financial-evidence-source-trace.png" alt="Giao diện truy nguyên doanh thu thuần về ô nguồn trong báo cáo tài chính" width="590"></a>

[Mở repository: Financial Statement Evidence API](https://github.com/ndt0610/financial-statement-evidence-api) · *Ảnh dùng bộ dữ liệu tổng hợp để minh họa truy nguyên nguồn, không phải báo cáo của doanh nghiệp thật.*

### Equara — FinBERT, tin–giá và danh mục đầu tư

**Từ tiêu đề tin đến nhãn theo quy tắc có thể xem lại:** prototype dùng FinBERT pretrained, nhóm tin gần trùng và đối chiếu biến động giá 5 phiên; README giải thích từng nhánh gán nhãn. Cùng repository có nghiên cứu phản ứng tin–giá trên EGX và danh mục Mỹ Phase 1.

<a href="https://github.com/ndt0610/equara-finbert-egx"><img src="https://raw.githubusercontent.com/ndt0610/equara-finbert-egx/main/docs/images/decision-label-etel.png" alt="Kết quả nhãn thử nghiệm Mua cho ETEL cùng điểm tin, giá 5 phiên và ngưỡng lịch sử" width="590"></a>

[Mở repository: Equara](https://github.com/ndt0610/equara-finbert-egx) · *Dự án cá nhân; có sử dụng AI coding assistants và ghi rõ phạm vi hỗ trợ. Nhãn không phải khuyến nghị giao dịch.*

## Dữ liệu tài chính và hệ thống

| Dự án | Nội dung có thể kiểm tra |
| --- | --- |
| [Vietnam Yield-Curve Research](https://github.com/ndt0610/ryc-vietnam-yield-curve) | So sánh kịch bản giữ/bán trái phiếu; dữ liệu giả lập và các giả định được ghi trong README. |
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

## Kỹ năng thể hiện qua dự án

**Tài chính và dữ liệu:** phân tích BCTC · Excel · SQL · Power BI<br>
**Phát triển prototype:** Python · FastAPI · Transformers/FinBERT · JavaScript/React · Streamlit<br>
**Demo học máy/thuật toán:** Q-learning · k-NN · gradient boosting · backtracking

Các kỹ năng trên được thể hiện qua bài tập và prototype cá nhân, không phải kinh nghiệm vận hành production. FinBERT là mô hình pretrained; quá trình phát triển có dùng AI coding assistants và được ghi nhận trong repository Equara.
