# PrintSplit_XLD-Tuned離線版

把太大、印表機印不下的 STL 模型，自動切割成符合列印範圍的小塊。
這是 [PrintSplit](https://github.com/printsplit/PrintSplitWeb/) 的 **Windows 離線版**，不需要網路，也不需要安裝 Docker 或任何伺服器。

## 下載

到 [Releases](https://github.com/XLD-Tuned/3D_STL_AUTOCUT/releases/latest) 下載 `PrintSplit_XLD-Tuned離線版-安裝版-x.x.x.exe`，執行後依照畫面安裝即可。

> 程式沒有數位簽章，第一次執行時 Windows 可能會跳出藍色的 SmartScreen 警告，
> 點「**其他資訊**」→「**仍要執行**」即可。

**系統需求：** Windows 10 / 11（64 位元）

## 功能

- 設定印表機的列印範圍（X / Y / Z），自動把模型切成符合尺寸的區塊
- 平均切割：避免切出太小的碎塊
- 對位孔：在切面上打孔，插入線材當定位銷，方便黏合時對齊
- 3D 預覽：切割前預覽切割位置，可直接拖曳切割平面調整
- 自動修復有破洞的模型
- 介面支援 **繁體中文** 與 English（左上角 🌐 切換）
- 完全離線運作，檔案不會上傳到任何地方

## 使用方式

1. 點「點擊選擇 STL 檔案」，選擇要切割的模型
2. 輸入印表機的列印範圍（單位：mm）
3. 視需要勾選「平均切割」或「對位孔」
4. 按「切割 STL 檔案」
5. 完成後按「將所有零件存到資料夾…」，選擇要儲存的位置

## 致謝與授權

本程式修改自 [PrintSplit](https://github.com/printsplit/PrintSplitWeb/)（作者 Shea Silverman），
原項目以 MIT 授權釋出。本離線版加入了 Windows 桌面程式、繁體中文介面等修改，同樣以 MIT 授權釋出。

```
MIT License

Copyright (c) Shea Silverman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
