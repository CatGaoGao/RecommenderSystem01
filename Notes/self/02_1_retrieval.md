# 基于物品的协同过滤（ItemCF）  
<img width="991" height="592" alt="image" src="https://github.com/user-attachments/assets/e9feec48-92eb-4bf7-9cab-2cb758440597" />

<img width="970" height="479" alt="image" src="https://github.com/user-attachments/assets/99e04077-0162-4ea0-8e80-7187fc12b027" />

<img width="1049" height="588" alt="image" src="https://github.com/user-attachments/assets/0f8b8e82-5d3a-4fc2-aa03-f6a25538a41e" />

# swing模型  
如果重合的用户来自同一个小圈子，要降低他们的权重  

# 基于用户的协同过滤（UserCF）  
<img width="1037" height="574" alt="image" src="https://github.com/user-attachments/assets/fd9f600c-1d53-4a85-9f58-e777b5ca06df" />
<img width="918" height="514" alt="image" src="https://github.com/user-attachments/assets/766f3d46-a8ba-48c5-8d2d-8665d6d779da" />
<img width="934" height="576" alt="image" src="https://github.com/user-attachments/assets/335bdc93-0c17-4422-84b9-e1d8d375984f" />

# 离散特征处理    
1.建立字典    
2.向量化（one-hot编码、Embedding）   

# one-hot编码  
性别[0,0][0,1][1,0]、国籍（规定有限的200个国家），这种有限的数据可以，能用向量穷尽表示  
但类别数量太大时，通常不用one-hot编码   

# Embedding  
