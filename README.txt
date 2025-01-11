MLP:
- input layer: nhận dữ liệu đầu vào, mỗi neuron tương ứng một đặc trưng của dữ liệu
- hidden layer: một hoặc nhiều lớp neuron giữa input và output layer. hidden layer giúp mạng học các đặc trưng phức tạp từ dữ liệu
- output layer: cung cấp kết quả cuối của mô hình (1 neuron cho bài toán hồi quy, nhiều neuron cho bài toán phân loại

neural network
- forward propagation: dữ liệu đầu vào được truyền qua các lớp của mạng. mỗi neuron tính toán đầu ra dựa vào trọng số của nó, sau đó áp dụng activation function để tạo ra đầu ra
- activation function: trong bài toán phân lớp, hàm kích hoạt phổ biến là hàm softmax, giúp chuyển đổi đầu ra thành xác suất cho mỗi lớp
- loss function: hàm mất mát phổ biến cho bài toán phân lớp là cross-entropy loss, giúp đo lường sự khác biệt giữa dự đoán và giá trị thực tế
- backward propagation: sai số giữa đầu ra dự đoán và thực tế được lan truyền ngược qua mạng để điều chỉnh các trọng số. quá trình này sử dụng thuật toán gradient descent để tối ưu hóa trọng số => giảm sai sót