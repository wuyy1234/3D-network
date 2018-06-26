# 3D-network
## 将巡逻兵小游戏改编成网络游戏
### 修改方法：
> 布置好networkmanager等之后，运行build&run会得到下面的界面，一个士兵是host的，一个士兵是client的。  
> 由于还没有网络同步所以两个士兵还是同步运动的，下面修改同步状态。  
> 在userGUI类上修改，如下：  
>   
* 更新脚本以仅移动本地播放器  
* 添加 “Using UnityEngine.Networking”  
* 将 “MonoBehaviour” 更改为 “NetworkBehaviour”  
* 在Update函数中添加一个 “isLocalPlayer” 检测，以便只有本地程序处理输入  

