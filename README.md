# XLDLTK
## Kết quả được Cải tiến từ mô hình [Kaggle](https://www.kaggle.com/masumrumi/a-detailed-regression-guide-with-house-pricing)

### Tiền xử lý thêm so với kernel ban đầu :
 - Xử lý outlier `GarageYrBlt` trong file test ( outlier `GarageYrBlt` = 2209 )
 - Thêm feature `hasVeneer` thể hiện có trang trí tường
 - Thêm feature `isRemodel` thể hiện nhà đã được tu sửa
 - BlThêm 4 mô hình `LGBMRegressor`, `XGBRegressor` , `GradientBoostingRegressor` và `Support Vector Regression`
### Kết quả hiện tại
![N|Solid](https://scontent.fhan2-3.fna.fbcdn.net/v/t1.15752-9/78925621_553882142074397_8597360925462233088_n.png?_nc_cat=101&_nc_ohc=cmwOwFS5rlsAQkB16KEhLRI5p_PEGkgu06Tsmk8IHYGFI1QMOtF6aDsQA&_nc_ht=scontent.fhan2-3.fna&oh=a31c382aed35336a7f9bcb553f80dccd&oe=5E4543D0)
