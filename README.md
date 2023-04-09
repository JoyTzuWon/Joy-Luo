# Joy-Luo
计算机视觉作业：构建两层神经网络
类型：两层Fully-Connected layer构建的双层神经网络
一些参数的选取：batch-size：当batch-size特别小的时候，由于训练集数据较大，拟合情况不是特别好，batch-size过大训练后accuracy也会下降。我挑选出的的最佳batch-size为512.
Epoch：由于我的超参数设置，epoch=100，1000，10000都对训练后的accuracy没有多少影响，但整体不是特别高，可能是hyper parameters范围的设置，与weight的initialization有关。epoch次数：100

正确率曲线

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758896-7da0331d-b2cf-4d83-afb4-2683b726a9a4.png">

loss曲线

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758914-17a5597c-deba-4f5a-a450-59888ac2ecd1.png">

参数可视化

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758924-f476bba2-ed15-4f7f-bed4-9712d9b525dd.png">

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758926-b26bc487-03df-4ecf-86ad-9c9b2f9a0f12.png">

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758932-458d52d9-20b8-4e03-89a0-1700afd1fe98.png">

<img width="416" alt="image" src="https://user-images.githubusercontent.com/129930916/230758935-c2e81dae-675f-4048-bc6c-5813ca2fd9d4.png">
