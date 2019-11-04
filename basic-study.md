# 1. Các đặt điểm cơ bản của lập trình hướng đối tượng trong PHP
## Tính đóng gói: Phạm vi cho phép truy cập /thay đổi thuộc tính/phương thức đối với:
+ Publish: Mọi phạm vi.
+ Protected: bản thân
nó và lớp kế thừa.
+ Private: bản thân nó

## Tính kế thừa:
+ Sử dụng từ khoá extends để kế thừa
+ Khi kế thừa có thể sử dụng lại các thuộc tính/phương thức Publish và Protected của lớp cha.
+ Có thể overide lại phương thức kế thừa từ lớp cha

## Tính trừu tượng:
+ Tính trừu tượng giúp chúng ta tập trung vào những đặc điểm chính hơn là đi sâu vào chi tiết. Có thể hiểu là xây dựng ra cái khung sườn.
+ Php có abtract và interface

## Đa hình:
+ Định nghĩa một đặc tính/phương thức cho một loạt các đối tượng gần giống nhau. Nhưng khi thực hiện thì các đối tượng khác nhau có thể overide lại để có cách thực hiện khác nhau và cho ra kết quả khác nhau.
