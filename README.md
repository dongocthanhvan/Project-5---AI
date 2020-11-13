Câu 1:

Với mỗi iteration thì ta sẽ duyệt qua các tập dữ liệu rồi thực hiện predict. Nếu y_pred khác với y thì weight[y] sẽ được cộng thêm X, weights[y_pred] sẽ bị trừ đi X

Câu 2: 
Chúng ta sẽ chạy 100 lần, mỗi lần tìm ra argMax, thêm argMax vào output và update lại weights bằng giá trị âm vô cùng để có thể tìm được giá trị max tiếp theo
Sau khi cho chạy thấy giống hình a 

Câu 3:
Đầu tiên, duyêt qua tất cả c đã cho trong Cgrid, sau đó thực hiện vòng lặp giống perceptron nhưng có thêm tau 

Câu 4:

Đếm được số thành phần liên thông của các pixel trắng trong tập dữ liệu đó. Sử dụng thuật toán dfs để tính số thành phần liên thông trong hàm cc. Sau khi tính được số thành phần liên thông ta sẽ thêm ra 3 feature đó là số thành phần lớn hơn 1, lớn hơn 3 và lớn hơn 5, các feature này dạng nhị phân

Câu 5:
Duyệt qua vòng lặp max_iterations và duyệt qua trainingData. Sau đó có Counter để chứa key là label và giá trị từng label đó. Ở vòng for label, tính độ chính xác bằng feature của label tại training thứ i nhân với weights. Tính argMax của y_hat thì thuật toán giống preceptron

Câu 6:
Dựa vào đề bài, ta có các feature mới là con ma gần nhất ( nearest_ghost), num_ghost là đếm số ma( dùng cho né ma và lao vào ma), scared_ghost là đếm số ma scared( dùng cho né ma và lao vào ma), stop là xét xem action hiện tại có phải stop hay không, nearest_food là xác định khoảng cách đến food gần nhất( dùng cho thằng chỉ đi ăn thức ăn và né ma+ ăn thức ăn)
