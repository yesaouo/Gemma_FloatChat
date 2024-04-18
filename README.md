# Gemma_FloatChat
一個半透明浮動視窗的ＡＩ助手

![根據用戶電腦配置自動選擇 (MacOS使用MPS運行)](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/964a6c12-8dfb-4ae6-9d6e-bc6abeb0f6b5)

## 效能測試
測試平台: Ryzen 7 5800H, RTX 3060 Laptop

根據底下的測試結果，我發現以下幾點：

1. 增加對話長度上限可以在一定程度上避免回答過長而被切斷的情況。然而，對於短問題的回答結果，增加對話長度上限並沒有太大的影響。

2. 對話長度上限與執行時間呈正比關係。也就是說，對話長度上限越大，執行時間也會相對增加。

3. 對話語言對執行時間的影響不大。但是，我們注意到，非英文的回答內容通常會略少於英文的回答。

<br>

翻譯前 | 翻譯後 | 執行時間
--- | --- | ---
![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/9dc42f09-5650-4b91-81b1-175f6ea11ed5) | ![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/863528d8-65d9-464e-adab-4a7c7f96430f) | 0.6688 s
![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/b5e0899a-b8c9-46c4-84e3-b6a07b768adb) | ![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/24ba2107-2ab5-4f94-ae21-47a907852470) | 16.325 s

英文提問 | 中文提問
--- | ---
![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/56a064c3-ff6c-4d3c-8d8d-c323f8fb972e) | ![image](https://github.com/yesaouo/Gemma_FloatChat/assets/88719692/4909884d-61f7-4b8b-8c18-6914a2406508)
執行時間: 30.319024085998535 s | 執行時間: 30.191612482070923 s

## 執行方法
參考 [main.ipynb](https://github.com/yesaouo/Gemma_FloatChat/blob/main/main.ipynb) 內有教學
