## 波斯顿房价预测

### 绘图版本

#### 结果：



![image](https://github.com/royal12646/mechine_learning/blob/main/1.png)
![image](https://github.com/royal12646/mechine_learning/blob/main/2.png)

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

![image](https://github.com/royal12646/mechine_learning/blob/main/3.png)

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

![image](https://github.com/royal12646/mechine_learning/blob/main/4.png)

![image](https://github.com/royal12646/mechine_learning/blob/main/5.png)

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



