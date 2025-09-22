# Giả sử 'predicted_prices' là kết quả dự đoán và 'test_prices' là dữ liệu thực tế
plt.figure(figsize=(14, 7))
plt.plot(test_prices.index, test_prices, label='Giá thực tế')
plt.plot(predicted_prices.index, predicted_prices, label='Giá dự đoán')
plt.title('Dự đoán giá cổ phiếu VNM bằng LSTM')
plt.xlabel('Ngày')
plt.ylabel('Giá (VNĐ)')
plt.legend()
plt.grid(True)

# Lưu biểu đồ vào file ảnh
plt.savefig('vnm_prediction_chart.png')
