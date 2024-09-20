## 波斯顿房价预测

### 绘图版本

#### 结果：



<img src="C:/Users/idis/AppData/Roaming/Typora/typora-user-images/image-20240920133746286.png" alt="image-20240920133746286" style="zoom:50%;" />

<img src="C:/Users/idis/AppData/Roaming/Typora/typora-user-images/image-20240920134038458.png" alt="image-20240920134038458" style="zoom:50%;" />
![image](https://github.com/user-attachments/assets/c3d0a8e8-f996-4970-93f0-4e405087456b)

#### 方程参数：

~~~python
w=5.5290
b=-12.3993
~~~



#### 训练参数：

~~~python
lr = 0.03
num_epochs = 4
batch_size=16
~~~



### 所有特征版本

#### 结果：

![image-20240920134827915](C:/Users/idis/AppData/Roaming/Typora/typora-user-images/image-20240920134827915.png)

#### 方程参数：

~~~python
w=tensor([[ 0.1435],
        [-0.1854],
        [-0.0041],
        [-0.0775],
        [ 0.3675],
        [ 0.1621],
        [-0.0626],
        [-0.0116],
        [-0.0326],
        [ 0.1007],
        [-0.1640]], requires_grad=True) 

b= tensor([22.3872], requires_grad=True)
~~~

#### 训练参数：

~~~python
lr = 0.003
num_epochs = 10
batch_size=16
~~~





## 拟合sin(x)

### 结果：

<img src="C:/Users/idis/AppData/Roaming/Typora/typora-user-images/image-20240920135121473.png" alt="image-20240920135121473" style="zoom:50%;" />

<img src="C:/Users/idis/AppData/Roaming/Typora/typora-user-images/image-20240920135146409.png" alt="image-20240920135146409" style="zoom:50%;" />

#### 方程参数：

~~~python
w=tensor([[ 3.4052],
        [-8.9720],
        [ 1.6977],
        [ 6.0178],
        [-2.4762]], dtype=torch.float64, requires_grad=True) 

b= tensor([-0.0005], dtype=torch.float64, requires_grad=True)
~~~

#### 训练参数：

~~~python
lr = 0.008
num_epochs = 25000
batch_size=16
~~~



