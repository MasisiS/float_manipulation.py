import math
import statistics

random_num = input("Enter 10 numbers:") # 10 numbers requested from user

new_list = [float(value) for value in random_num.split(', ')] # adding the floating  to the list

print(sum(new_list)) #calculating and printing total

print(new_list.index(max(new_list))) # printing index of maximum number in a list

print(new_list.index(min(new_list))) # printing index of minimum number in a list

print(statistics.mean(new_list)) # Calculating and printing average

print(statistics.median(new_list)) # Calculating and printing median
