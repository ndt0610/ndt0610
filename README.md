# Nguyễn Đình Tú

**Công nghệ Tài chính (PTIT) · Phân tích tài chính · Dữ liệu số**

Mình là sinh viên Công nghệ Tài chính tại PTIT, đang chuẩn bị thực tập ở ngân hàng. Mình quan tâm điểm giao giữa nghiệp vụ tài chính và dữ liệu: phân tích báo cáo, lần lại nguồn số liệu, rồi dựng prototype để kiểm tra cách một quy tắc hoạt động. Các dự án cá nhân và bài tập học phần được ghi riêng; dữ liệu mô phỏng được chú thích rõ.

## Hai dự án nên xem trước

### Financial Statement Evidence API

**Báo cáo gốc nói gì, và nhận định đó dựa trên số nào?** Bàn phân tích đọc XLSX/PDF, so sánh chỉ tiêu nhiều kỳ, phân rã DuPont và nêu điểm cần rà soát như lợi nhuận dương nhưng dòng tiền kinh doanh âm. Bấm vào chỉ tiêu để xem công thức, trạng thái xác minh và ô/trang nguồn; thiếu chứng cứ thì kết quả được giữ lại để hậu kiểm.

<a href="https://github.com/ndt0610/financial-statement-evidence-api"><img src="https://raw.githubusercontent.com/ndt0610/financial-statement-evidence-api/main/docs/images/financial-bank-analysis.jpg" alt="Góc nhìn ngân hàng trên dashboard phân tích báo cáo tài chính nhiều kỳ" width="590"></a>

[Mở repository: Financial Statement Evidence API](https://github.com/ndt0610/financial-statement-evidence-api) · *Dashboard dùng dữ liệu minh họa; README repo có ảnh thứ hai cho thấy cách mở công thức và ô nguồn.*

### Equara — FinBERT, tin–giá và danh mục đầu tư

**Từ tiêu đề tin đến nhãn theo quy tắc có thể xem lại:** prototype dùng FinBERT pretrained, nhóm tin gần trùng và đối chiếu biến động giá 5 phiên; README giải thích từng nhánh gán nhãn. Cùng repository có nghiên cứu phản ứng tin–giá trên EGX và danh mục Mỹ Phase 1.

<a href="https://github.com/ndt0610/equara-finbert-egx"><img src="https://raw.githubusercontent.com/ndt0610/equara-finbert-egx/main/docs/images/decision-label-etel.png" alt="Kết quả nhãn thử nghiệm Mua cho ETEL cùng điểm tin, giá 5 phiên và ngưỡng lịch sử" width="590"></a>

[Mở repository: Equara](https://github.com/ndt0610/equara-finbert-egx) · *Dự án cá nhân; có sử dụng AI coding assistants và ghi rõ phạm vi hỗ trợ. Nhãn không phải khuyến nghị giao dịch.*

## Dữ liệu tài chính và hệ thống

| Dự án | Nội dung có thể kiểm tra |
| --- | --- |
| [Bitcoin Regtest Transaction Demo](https://github.com/ndt0610/bitcoin-regtest-transaction-demo) | Theo dõi vòng đời giao dịch Bitcoin trên Regtest cục bộ: UTXO, ký, phát giao dịch và xác nhận. |
| [Blockchain Balance API](https://github.com/ndt0610/blockchain-balance-api) | API đọc số dư đa chuỗi với adapter provider và định danh tài sản có cấu trúc. |
| [RAG Document Assistant](https://github.com/ndt0610/rag-document-assistant) | Hỏi đáp trên PDF với truy xuất theo trang, xử lý ingestion bất đồng bộ và trích dẫn nguồn. |

## Mô phỏng quyết định

[Surge Strike Simulator](https://github.com/ndt0610/surge-strike-simulator) là demo Web cho một tình huống vận hành nền tảng gọi xe: chiết khấu cao có thể làm thay đổi nguồn cung tài xế, số cuốc phục vụ và giá theo khu. Bản đồ 21 khu cho phép đổi kịch bản, tạo cú sốc đình công và thử thưởng hoặc giảm chiết khấu; báo cáo 20 seed so sánh các chính sách. Đây là mô hình tác nhân với dữ liệu và hành vi giả lập, không phải dữ liệu hay dự báo của Be.

<a href="https://github.com/ndt0610/surge-strike-simulator"><img src="https://raw.githubusercontent.com/ndt0610/surge-strike-simulator/main/docs/images/surge-strike-map.jpg" alt="Bản đồ mô phỏng 21 khu với surge, trạng thái tài xế và bảng điều khiển chính sách" width="590"></a>

*Mở ảnh để xem bản đồ lớn hơn; repository có thêm ảnh phần thử can thiệp và biểu đồ diễn biến mô phỏng.*

### Vietnam Yield-Curve Research

Nghiên cứu mô phỏng dòng tiền trái phiếu và so sánh giữ/bán theo các kịch bản lãi suất. Demo **Perfect Foresight** riêng cho phép thay tháng bán và tỷ lệ bán, xem phân bổ dòng tiền và so với giữ đến kỳ hạn trên đường giá giả định đã biết trước. Vì đường giá được đưa vào mô hình từ đầu, kết quả là một phép so sánh kịch bản chứ không phải dự báo thị trường hay khuyến nghị giao dịch.

<a href="https://github.com/ndt0610/ryc-vietnam-yield-curve/tree/main/demos/perfect-foresight"><img src="https://raw.githubusercontent.com/ndt0610/ryc-vietnam-yield-curve/main/demos/perfect-foresight/perfect-foresight-default-case.png" alt="Kịch bản cơ sở của demo Perfect Foresight: giữ đến H cao hơn phương án bán tốt nhất trên lưới" width="590"></a>

[Mở RYC và demo Perfect Foresight](https://github.com/ndt0610/ryc-vietnam-yield-curve/tree/main/demos/perfect-foresight) · *Ảnh ghi rõ giả định đường giá biết trước; kết quả chỉ áp dụng cho lưới kịch bản đã chọn.*

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
