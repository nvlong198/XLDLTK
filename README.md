# XLDLTK
## Kết quả được Cải tiến từ mô hình [Kaggle](https://www.kaggle.com/masumrumi/a-detailed-regression-guide-with-house-pricing)

### Tiền xử lý thêm so với kernel ban đầu :
 - Xử lý outlier `GarageYrBlt` trong file test ( outlier `GarageYrBlt` = 2209 )
 - Thêm feature `hasVeneer` thể hiện có trang trí tường
 - Thêm feature `isRemodel` thể hiện nhà đã được tu sửa
 - BlThêm 4 mô hình `LGBMRegressor`, `XGBRegressor` , `GradientBoostingRegressor` và `Support Vector Regression`
### Kết quả hiện tại
![N|Solid](https://scontent.fhan2-4.fna.fbcdn.net/v/t1.15752-9/78491117_1210931639296645_4294536699758772224_n.png?_nc_cat=103&_nc_ohc=qwg7_kLBZt8AQmoKef3vN92p-7f5Kb7Wuu3kYnxLVBaSopnjVXBxR9EnQ&_nc_ht=scontent.fhan2-4.fna&oh=051fcb0be81a7aaf12d380a19bbce423&oe=5E43BEAB)
