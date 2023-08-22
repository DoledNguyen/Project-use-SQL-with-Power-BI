# I. Background 
Global Superstore is a well-known retail company that operates worldwide, selling a wide range of products, including furniture, electronics, office supplies, and more. The company generated a vast amount of data related to its sales, customers, and products. This data is valuable in understanding the performance of the company, identifying trends and patterns, and making informed business decisions.

(Global Superstore là một công ty bán lẻ nổi tiếng hoạt động trên toàn thế giới, bán nhiều loại sản phẩm, bao gồm đồ nội thất, đồ điện tử, đồ dùng văn phòng, v.v. Công ty đã tạo ra một lượng lớn dữ liệu liên quan đến doanh số bán hàng, khách hàng và sản phẩm của mình. Dữ liệu này có giá trị trong việc hiểu hiệu suất của công ty, xác định các xu hướng và mô hình cũng như đưa ra các quyết định kinh doanh sáng suốt

# II. Analysis

### 1. Business situation of the company
<img width="1290" alt="Screenshot 2023-08-19 at 21 55 04" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/9fc1cd2f-5220-476a-9311-133e86a2c4f4">

- Revenue and profit tend to increase strongly in the third and fourth quarters and decrease slightly in the first two quarters of the year.

(Doanh thu và lợi nhuận có xu hướng tăng mạnh vào quý 3 và 4 và giảm nhẹ ở 2 quý đầu năm.)

<img width="1291" alt="Screenshot 2023-08-19 at 21 55 22" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/29ff547e-2e45-4a31-88d6-6c2f1e530b96">

- Technology and furniture products are considered durable goods, thus commanding higher prices, leading to greater profitability. It is also evident that 4 out of the top 5 highest-selling products belong to the technology and furniture product lines.

(Các sản phẩm công nghệ và nội thất được coi là hàng hóa lâu bền, do đó có giá cao hơn, dẫn đến lợi nhuận cao hơn. Ngoài ra có thể thấy 4 trong số 5 sản phẩm bán chạy nhất thuộc về dòng sản phẩm công nghệ và nội thất.)

<img width="1291" alt="Screenshot 2023-08-19 at 21 55 40" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/fee35a04-5fab-45ab-aa99-3dd7fa2933ff">

***

The revenue has steadily increased over the years, with a noticeable uptrend in quarters 3 and 4. This suggests that customers tend to engage in more robust shopping activities towards the end of the year, with reduced spending at the beginning of the year. Overall, the company's business outlook has shown consistent improvement and development over the years.

=> Promote the business of technology products and furniture. Re-research the market at the beginning of the year, adjust to find the right products to optimize sales

(Doanh thu tăng đều qua các năm, có xu hướng tăng mạnh vào các quý 3 và 4 có thể thấy được khách hàng thường mua sắm mạnh vào cuối năm và ít chi tiêu vào đầu năm hơn. Nhìn chung  tình hình kinh doanh công ty có cải thiện tốt và phát triển qua các năm.

=> Đẩy mạnh kinh doanh các sản phẩm công nghệ và nội thất. Nghiên cứu lại thị trường đầu năm, điều chỉnh để tìm ra sản phẩm phù hợp nhằm tối ưu hóa doanh số.)

***

### 2. Product Analysis

<img width="1250" alt="Screenshot 2023-08-20 at 10 10 51" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/a12840d7-b85b-49f2-9f44-f75ecdce4a29">
<img width="1248" alt="Screenshot 2023-08-20 at 10 11 06" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/1ca9a920-e333-4b86-843a-bfbaea2dc5db">
<img width="1251" alt="Screenshot 2023-08-20 at 10 11 23" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/04addabd-4f2e-4384-b857-c14c235ee0bf">
<img width="1255" alt="Screenshot 2023-08-20 at 10 12 15" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/bba01918-ef57-45a4-906d-7de50ade619d">

***

Stop selling Table products. Do more market research. Focus on selling products with high turnover. More discounts at 2 levels 10% and 20% to attract customers

(Ngừng bán sản phẩm Table. Nghiên cứu thị trường nhiều hơn. Tập trung bán những sản phẩm có doanh thu cao. Giảm thêm ở 2 mức 10% và 20% để thu hút khách hàng)

***

### 3. Product Delivery
<img width="1252" alt="Screenshot 2023-08-21 at 15 11 26" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/0ddd772e-ac06-45b8-bd4f-4372d56e1da7">
<img width="1249" alt="Screenshot 2023-08-21 at 15 11 43" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/9a1bd1e3-b5eb-4fa8-8795-1918a86b5255">
<img width="1253" alt="Screenshot 2023-08-21 at 15 12 00" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/0e202db2-6c7b-455d-a6ef-42ba2623f24a">

***

Shipping costs No significant impact on revenue and profit fluctuations. Standart Class has the highest revenue and Shipping cost

=> Use Second Class mode more to minimize Shipping Cost, Find a solution to reduce delivery days to optimize shipping costs. Need to re-examine current logistics strategy

(Chi phí vận chuyển Không ảnh hưởng đáng kể đến biến động doanh thu và lợi nhuận. Standart Class có doanh thu và chi phí vận chuyển cao nhất

=> Sử dụng chế độ Second Class nhiều hơn để giảm thiểu Chi phí Vận chuyển, Tìm giải pháp giảm ngày giao hàng để tối ưu hóa chi phí vận chuyển. Cần xem xét lại chiến lược logistics hiện tại.)
***

### 4.Customer Analysis

<img width="1254" alt="Screenshot 2023-08-22 at 11 43 11" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/c98c8d9a-936c-442e-87e7-cddfd3060289">
<img width="1253" alt="Screenshot 2023-08-22 at 11 43 33" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/d8bbc964-ef42-4676-a458-6bfb94f1c2e5">

***

The number of customers increased over time, along with the profit. The largest portion of the market share is held by consumers, comprising half of the total. Asia Pacific has the largest number of visitors.

(Số lượng khách hàng tăng dần theo thời gian, cùng với đó là lợi nhuận. Phần lớn thị phần do người tiêu dùng nắm giữ, chiếm một nửa tổng thị phần. Châu Á Thái Bình Dương có số lượng khách nhiều nhất.)

***

### 5. Customer Segmentation 
<img width="1258" alt="Screenshot 2023-08-22 at 13 07 10" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/06c9c155-339c-464f-bc5d-50ddc59e1d6a">
<img width="1253" alt="Screenshot 2023-08-22 at 13 07 32" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/118ac9fe-ba5c-4a14-ae61-db17c257350f"><img width="1252" alt="Screenshot 2023-08-22 at 13 08 40" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/8e8610ae-187a-4c2e-84ab-4169dad0d434">
<img width="1251" alt="Screenshot 2023-08-22 at 13 09 13" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/6d081129-d5ca-46de-a830-7b29cd51a25b">
<img width="1251" alt="Screenshot 2023-08-22 at 13 09 24" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/a9512688-387c-4102-a00d-4ce3d5fa8176">

***

The Lost Customers rate is quite high, it is necessary to review the customer retention strategy, especially with the Lost Customers segment. Find ways to enhance the value of your product or service. Up sale for loyal customers.

(Tỷ lệ Lost Customers khá cao, cần xem lại chiến lược giữ chân khách hàng, đặc biệt với phân khúc Lost Customers . Tìm cách để nâng cao giá trị của sản phẩm hoặc dịch vụ của bạn. Up sell đối với nhóm khách hàng trung thành.)

***



<img width="1251" alt="Screenshot 2023-08-22 at 15 12 53" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/58bca871-b7d3-4c8c-a56c-c7f6fff03272">

# III. Conclusion 
<img width="1253" alt="Screenshot 2023-08-22 at 15 13 07" src="https://github.com/DoledNguyen/Project-use-SQL-with-Power-BI/assets/129746147/074ad144-830a-4b88-ac4d-b628c83e6126">

***

The company's business situation is progressing quite well, with consistent annual revenue growth and a notable increase in the number of orders sold. However, there are fluctuations in quarterly revenue. The initial quarters usually witness fewer orders and lower revenue compared to the later quarters. It's important for us to consider adjusting the appropriate product offerings and reevaluating the market to enhance sales.
The customer churn rate is also relatively high, which could have negative implications for the company's future. Therefore, it's crucial to revamp customer service, enhance user experience, and improve quality. Additionally, for the product categories contributing significantly to the company's revenue, there should be a concentrated effort to further strengthen their development.

(Tình hình kinh doanh của công ty đang tiến triển khá tốt với doanh thu tăng trưởng đều hàng năm và số lượng đơn hàng bán ra tăng đáng kể. Tuy nhiên, doanh thu hàng quý có sự biến động. Các quý đầu tiên thường có ít đơn hàng hơn và doanh thu thấp hơn so với các quý sau. Điều quan trọng là chúng ta phải xem xét điều chỉnh việc cung cấp sản phẩm phù hợp và đánh giá lại thị trường để nâng cao doanh số bán hàng.
Tỷ lệ khách hàng rời bỏ cũng tương đối cao, điều này có thể có tác động tiêu cực đến tương lai của công ty. Do đó, cần phải cải tiến dịch vụ khách hàng, nâng cao trải nghiệm người dùng và cải thiện chất lượng. Bên cạnh đó, đối với những ngành hàng đóng góp đáng kể vào doanh thu của công ty thì cần tập trung đẩy mạnh phát triển hơn nữa.)


***





