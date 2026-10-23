# 1151VR-HW4

## 1. 專案截圖
<img width="445" height="433" alt="image" src="https://github.com/user-attachments/assets/04fbb9f1-6dbd-454e-8771-4bf47330c653" />
<img width="672" height="386" alt="image" src="https://github.com/user-attachments/assets/9524ccb9-04ce-4b77-ba72-bc8e5cc804f4" />

## 2. GitHub 連結
https://github.com/chengyou1126/1151VR-HW4-414262040-HSIEH-CHENG-YU/blob/main/README.md

## 3. YouTube 影片連結
https://youtu.be/kFmWTIJ_564

## 4. 製作流程與相關操作說明

### 【製作流程】
1. **場景建置與模型導入**：於 Unity 6 中建立 3D 場景，匯入飛機模型 (zero)，並利用 Cube 設置 15 個障礙物構成飛行跑道。
2. **物理引擎與碰撞偵測**：為飛機與障礙物配置 Collider，透過標籤 (Tag) 進行碰撞邏輯判定。當撞擊發生時觸發停止狀態 (isStopped = true)，立即中斷飛機的位移運算與輸入控制。
3. **音效邏輯整合**：匯入並配置三種音效。設定背景持續播放引擎聲；透過 Z 軸座標判定飛越障礙物時觸發過關得分音效(win sound)；碰撞發生時觸發撞擊音效(crash sound)。
4. **跨平台輸出與實機測試**
   - **iOS 實機連線**：使用 Unity Remote 5 將畫面投放至手機螢幕上面遊玩。
### 【操作與注意事項】
- 遊戲開始後飛機會自動向前，玩家需使用「電腦滑鼠」上下左右移動來控制飛機閃避障礙物。
- 手機端支援觸控滑動。因 Unity Remote 5 在Windows環境下的硬體與傳輸限制，不支援音訊串流且存在畫面延遲，故手機端僅作為跨平台畫面與觸控訊號之展示。完整聲光遊玩過程請參考YouTube連結。
