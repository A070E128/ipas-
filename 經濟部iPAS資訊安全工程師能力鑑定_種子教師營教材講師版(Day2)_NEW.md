# 資料連結層 – ARP Spoofing(1/2)
又稱為ARP flooding、ARP poisoning或ARP Poison Routing
在Broadcast Domain下無法被動監聽其他電腦間連線封包
ARP Spoofing攻擊強迫偽冒其他IP，讓攻擊者有機會監測到其他電腦間的通訊
# 資料連結層 – ARP Spoofing(2/2)
## 攻擊手法
攻擊者使用ARP Broadcast封包告訴其他電腦，192.168.1.1的MAC是Attacker的MAC
其他電腦要傳送給192.168.1.1的封包會被送到Attacker
Attacker將封包錄下後轉送到真正的192.168.1.1
## 防護建議
強制使用靜態ARP Table(小型網路)
採用VLAN縮小Broadcast Domain的範圍
啟用Switch中的Port、MAC及IP的對應控管
