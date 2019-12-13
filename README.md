# XLDLTK
## Kết quả được Cải tiến từ kernel [Kaggle](https://www.kaggle.com/alfredmaboa/advanced-regression-techniques-regularization)

### Tiền xử lý thêm so với kernel ban đầu :
 - Xử lý outlier `GarageYrBlt` trong file test ( outlier `GarageYrBlt` = 2207 thay bằng 2007 )
 - Thêm feature `hasVeneer` thể hiện có trang trí tường
 - Thêm feature `isRemodel` thể hiện nhà đã được tu sửa
 - Thêm 5 mô hình `LGBMRegressor`, `XGBRegressor` , `GradientBoostingRegressor`,`Support Vector Regression` và `StackingCVRegressor`
### Kết quả hiện tại
![N|Solid](https://scontent.fhan2-3.fna.fbcdn.net/v/t1.15752-9/78827370_2383301748448162_719334578866618368_n.png?_nc_cat=107&_nc_ohc=2g_kKZ-UHK4AQngn7MEdmkWQLpAwioWcRY70wdQa2eBYN6rVpFNZHwvXw&_nc_ht=scontent.fhan2-3.fna&oh=a8f53bc7a7233af52a3de1fde1f3ba70&oe=5E6C0D59)
