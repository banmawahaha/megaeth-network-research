# 03 Performance Test and Transaction Analysis  
*Performance Testing and Transaction Analysis on MegaETH*  
*MegaETH 性能測試與交易分析*

## Overview | 簡介
This document focuses on the methodology and results of performance testing on the MegaETH testnet.  
It aims to provide transparent, reproducible, and data-driven insights into transaction latency, throughput, and efficiency.  
本文件重點介紹 MegaETH 測試網的性能測試方法與結果，旨在提供透明、可重現且以數據為基礎的分析，涵蓋交易延遲、吞吐量與效率。

## Testing Methodology | 測試方法論
1. **Test Wallet Deployment**  
   A dedicated test wallet is deployed on MegaETH testnet for sending and receiving transactions.  
   **測試錢包部署**  
   在 MegaETH 測試網部署專用測試錢包，用於發送與接收交易。
2. **Transaction Types**  
   - Simple ETH transfer  
   - Smart contract execution (EVM compatible)  
   **交易類型**  
   - 簡單 ETH 轉帳  
   - 智能合約執行（EVM 兼容）
3. **Data Collection**  
   Record transaction latency, confirmation time, and gas cost for each transaction.  
   **數據收集**  
   記錄每筆交易的延遲、確認時間及 Gas 成本。
4. **Throughput Measurement**  
   Measure transactions per second (TPS) using batch transactions.  
   **吞吐量測量**  
   通過批量交易測量每秒交易量（TPS）。
