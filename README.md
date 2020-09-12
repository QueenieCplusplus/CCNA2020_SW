# CCNA2020_SW
switcher

# Flooding

交換機收到影格會根據 MAC table 將影格傳送到對應到適合處理的阜，倘若沒有學習過，則採用泛洪 flooding to all ports。
這是因為預設上，所有 ports 都屬於同一 VLAN。

如有額外切出虛擬區域網路，則 flood 僅會作用於同一 VID。

# Trunk

串接不同的交換機時，需要使用 802.1q 和 trunk port，此時交換機的 port 可以同時配置多個 VLAN。
