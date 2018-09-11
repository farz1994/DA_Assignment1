# DA_Assignment1
Prescriptive analytics is used to predict the future outcome : T
Base R packages are installed automatically : T

Recycling of elements in a Vector ?
Recycling of elements is when we perform operations on two different vectors having different lengths. In this case the elements of the shorter length vector are used to complete the operation.(Elements of the shorter length are reapeated until the lenth of the shorter vector becomes same as the longer one)
 
Give an example of recycling of elements?
x1<-c(2,6,8,0,1,4,6)
x2<-c(2,1,4)
print(x1*x2)
Result : [1]  4  6 32  0  1 16 12
