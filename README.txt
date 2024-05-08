A deep learning model for detecting the grasping angle of toys
深度學習期末報告第6組_2023_0110

程式 :
	final_project_group_six.ipynb : 訓練與驗證神經網路模型的程式
	build_dataset.ipynb : 建立資料集的程式
	check_preprocess1.ipynb : 檢查自動擷取圖片特徵是否正確的程式
檔案 :
	angle_type.txt : 抓取角度的答案種類(4種)
	img_grabbing_angle.csv : 資料集中所有圖片檔名與對應的夾取角度
資料夾 :
	toys_in_the_room : 資料集(模擬玩具散落在房間的地板)
	background : 資料集中的背景(房間地板)
	toys_original : 資料集中原始玩具圖
	preprocessed_images : 儲存執行 check_preprocess1.ipynb 得到的結果圖
	result : 儲存訓練與驗證損失圖以及模型參數
