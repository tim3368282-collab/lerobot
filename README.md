# lerobot
Robotic Arm: ACT Imitation Learning and Real-world Pick-and-Place

1. Project Overview
本專案以 SO-100 實體機械臂為平台，使用開源 LeRobot 相關工具與 ACT（Action Chunking with Transformers）模仿學習策略，實作模型訓練與實體機械臂控制。

專案目標是了解如何利用示範資料訓練機器人策略，並將訓練後的模型應用於實際物品夾取與放置任務。

2. Technologies
Python
PyTorch
LeRobot
ACT Imitation Learning
Kaggle GPU Environment
SO-100 Robotic Arm
3. Implementation
Training Environment
使用 Kaggle Notebook 建立 Python 訓練環境，安裝必要套件，設定資料集與訓練參數。

Model Training
使用 ACT 策略執行模型訓練，保留訓練日誌、Loss 變化及 checkpoint 紀錄。
file: lerobot_in_kaggle_training.ipynb 
目前提供的訓練紀錄包含約 70,000 training steps。

Real-world Robot Experiment
完成 SO-100 實體機械臂組裝，並使用訓練後的 ACT 模型控制機械臂，實際執行物品夾取及放入盒子的任務。

4. Personal Contributions
實體機械臂組裝與操作。
Kaggle 訓練環境建置。
資料集與模型訓練參數設定。
模型訓練執行與訓練紀錄整理。
訓練模型與實體機械臂整合及任務測試。
本專案使用既有開源工具與模型訓練程式，並以實際訓練、系統整合及實體操作驗證作為主要實作內容。

5. Results
實體 SO-100 機械臂已成功執行物品夾取與放置任務。
video: video_overhead.mp4, video_on_wrist.mp4

6. References
Kaggle training notebook: https://www.kaggle.com/code/timjas/lerobot
GenkiArm source repository: https://gitee.com/huahuaze/genkiarm
LeRobot: https://github.com/huggingface/lerobot

