```python
# #python异常捕获机制
# try:
#     age=int(input('please enter your age'))
#     print(age)
#     income=2000
#     print(income/age)
# except ZeroDivisionError:
#     print('age cant be zero')
# except ValueError:
#     print('error:please enter number!')



#  classes in python

# class Point:
#     def __init__(self,xp,yp):  #self指向创建的实例本身
#                                #注意有两个下划线
#         self.xp=xp
#         self.yp=yp
#
#
#
#     def move(self):
#         print('move')
#
#     def draw(self):
#         print('draw')
#
# Point1=Point(15,20) #格式！
# Point1.draw()
# Point1.move()
# Point1.X=10   #可以在外面直接新定义一个变量
# print(Point1.xp)
```