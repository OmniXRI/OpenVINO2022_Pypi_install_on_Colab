# OpenVINO2022_Pypi_install_on_Colab
如何在Colab上透過Pypi安裝OpenVINO開發者版本

由於Intel OpenVINO和Google Colab雙雙推進版本，導致OpenVINO很多舊版和最新版提供範例不一定能順利在Google Colab上運行，所以這裡提供一個較簡易的方法重新安裝後就能順利解決，並示範一個影像分類的範示提供大家參考。

Intel OpenVINO在2022.1版後就有重大改革[1]，同時提供了很多 Jupyter Notebooks範例[2][3]，很方便大家進行AI應用測試。
不過這些範例雖然和Google Colab都是 *.ipynb 格式，但因為有很多相對位置參考及套件包版本衝突問題，所以這裡改成下列步驟即可順利執行。
1. 以pip install 來安裝 openvino-dev 
2. 下載OpenVINO Notebooks範例中相關檔案（如模型、測試影像等）
3. 複製OpenVINO Notebooks範例程式碼並修改相對路徑引用
4. 運行全部

點擊下列網址可直接開啟範例進行測試。  
https://colab.research.google.com/github/OmniXRI/OpenVINO2022_Pypi_install_on_Colab/blob/main/Pypi_install_OpenVINO_on_Colab.ipynb

[1][OpenVINO 2022大改版讓Edge AI玩出新花樣](https://omnixri.blogspot.com/2022/08/openvino-2022edge-ai.html)  
[2][Github - openvinotoolkit / openvino_notebooks](https://github.com/openvinotoolkit/openvino_notebooks)  
[3][Learn OpenVINO -Interactive Tutorials (Python)](https://docs.openvino.ai/latest/tutorials.html)  
