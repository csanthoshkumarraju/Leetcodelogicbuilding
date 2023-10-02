# Leetcodelogicbuilding
# # Lettcode problem 1
# # 1. Two Sum
# l = [1,2,3,4]
# # # print(l.index(3)+l.index(4))
# # # print(l[0]+l[1])
# # sum = 0
# # for i in l:
# #     sum += i
# # print(sum)
# le = len(l)
# # print(l[0:])
# for i in range(len(l)):
#     sum_index = [i,l[i:]]
#     print(sum(sum_index))
# # possibilities of sums= [(1,2),(1,3),(1,4),(2,3),(2,4),(3,4)]
# # possibilities of indices =[(0,1/0,2,0,3,1,2/1,3/2,3)]
#  palindrome
# class Palindrome:
#   def __init__(self,x):
#      self.x = x
#   def isPalindrome(self):
#       reverse_integer = str(self.x)
#       if str(self.x) == reverse_integer[::-1]:
#           print('true')
#       else:
#           print('false')
# nu = Palindrome(input())
# nu.isPalindrome()
# import re
#
# #Check if the string starts with "The" and ends with "Spain":
#
# txt = "The rain in Spain"
# x = re.search("^The$", txt)
#
# if x:
#   print("YES! We have a match!")
# else:
#   print("No match")
# creating an empty list

# lst = []
# n = int(input("Enter number of elements : "))
# for i in range(0, n):
# 	ele = int(input())
# 	lst.append(ele)
# print(lst)
# lst1 = []
# n1 = int(input("Enter number of elements : "))
# for i in range(0, n1):
# 	ele1 = int(input())
# 	lst1.append(ele1)
# print(lst1)
# l3 = lst + lst1
# print(sorted(l3))

# def sortedl():
# 	lst = []
# 	n = int(input("Enter number of elements : "))
# 	for i in range(0, n):
# 		ele = int(input())
# 		lst.append(ele)
# 	print(lst)
# 	lst1 = []
# 	n1 = int(input("Enter number of elements : "))
# 	for i in range(0, n1):
# 		ele1 = int(input())
# 		lst1.append(ele1)
# 	print(lst1)
# 	re = lst + lst1
# 	print(re)
# 	print(sorted(re))
# sortedl()

# class sortedli:
# 	def __init__(self,ele,ele1):
# 		self.ele = ele
# 		self.ele1 = ele1
# 	def sortedl(self):
# 		lst = []
# 		# n = int(input("Enter number of elements : "))
# 		for i in range(0, n):
# 			self.ele = int(input())
# 			lst.append(self.ele)
# 		print(self.ele)
# 		self.ele1 = []
# 		lst1 = []
# 		# n1 = int(input("Enter number of elements : "))
# 		for i in range(0, n1):
# 			self.ele1 = int(input())
# 			lst1.append(self.ele1)
# 		print(self.ele1)
# 		# re = self.ele + self.ele1
# 		# print(re)
# 		# print(sorted(re))
# n = int(input("Enter number of elements : "))
# n1 = int(input("Enter number of elements : "))
# sl = sortedli(int(input()),int(input()))
# sl.sortedl()

