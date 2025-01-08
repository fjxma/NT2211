# NT2211 Học máy trong ATTT
## Giảng Viên: TS Lê Kim Hùng
### Học viên: 
- Cao Bá Kiệt  230202008
- Huỳnh Thị Xuân Thịnh 230202015

### Đồ án cuối kì bao gồm:
1. File Model **`XGB_HypOpt.pkl`**
2. File **`train.ipynb`** - File code dùng để huấn luyện với model, nhóm đã thử nghiệm với 5 thuật toán khác nhau.
3. File **`test.csv`** - File này thầy cung cấp dùng để kiểm tra mô hình, tuy nhiên file test thầy cung cấp không có nhãn.
4. File **`main.py`** - File này dùng để load model đã export và thực hiện dự đoán. Output sẽ là file **`*_predict.csv`** chứa cột **Predict**
   - ex: 
     ```bash
     python main.py path/to/model.pkl --csv-path path/to/data.csv
     ```
   - ex:
     ```bash
     python ./main.py ./weights/XGB_HypOpt.pkl --csv-path ./test.csv
     ```
### Notes: Đề bài gồm 2 file : **`train.csv`** và **`test.csv`**. Tuy nhiên file **`test.csv`** thầy gửi không có nhẵn.

### File có dung lượng lớn hơn 25MB nên nhóm sẽ upload ở [v1.0](https://github.com/fjxma/NT2211/releases/tag/v1.0)
