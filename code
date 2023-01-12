class Subscription:
    TOI = [3,3,3,3,3,5,6]
    hindu = [2.5,2.5,2.5,2.5,2.5,4,4]
    ET = [4,4,4,4,4,4,10]
    BM = [1.5,1.5,1.5,1.5,1.5,1.5,1.5]
    HT = [2,2,2,2,2,4,4]
s = Subscription()
newspaper = ['TOI','hindu','ET',"BM",'HT']
multi_array= []
multi_array.append(sum(s.TOI))
multi_array.append(sum(s.hindu))
multi_array.append(sum(s.ET))
multi_array.append(sum(s.BM))
multi_array.append(sum(s.HT))
input_budget = int(input("Enter the budget:"))
output_list = []
for i in range(len(multi_array)-1):
    for j in range(i+1,len(multi_array)):
        if multi_array[i]+multi_array[j]<=input_budget:
            output_list.append({newspaper[i],newspaper[j]}) 
print(output_list)
       
