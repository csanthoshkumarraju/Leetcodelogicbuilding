# # Leetcode problem 1
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
# def Plusone(l):
#         print(l)
#         l_str = map(str,l)
#         print(l_str)
#         st = ''
#         b = st.join(list(l_str))
#         print(b)
#         inc = int(b) + 1
#         res = str(inc)
#         lis = []
#         for i in res:
#             lis.append(i)
#         print(lis)
# Plusone(input().split())

# class Plus:
#     def Plusone(self,l):
#         self.l =l
#         print(self.l)
#         l_str = map(str, self.l)
#         print(l_str)
#         st = ''
#         b = st.join(list(l_str))
#         print(b)
#         inc = int(b) + 1
#         res = str(inc)
#         lis = []
#         for i in res:
#             lis.append(i)
#         print(lis)
# i = Plus()
# i.Plusone(input().split())
# inl = input('enter the series of numbers with one missing element').split()
# se = set(inl)
# # print(se)
# l = []
# for i in range(len(inl)+1):
#     l.append(i)
# s = set(l)
# print(type(s))
# print(type(se))
# print(s.difference(se))
# s = {0,1,2,3}
# se = {3,0,1}
# print(s - se)
# palindrome
# i = 19
# if i in range(0,11):
#    i = 10
#    print(i)
# elif i in range(11,21):
#    i = 20
#    print(i)
# else:
#    print('exceeded')
# for j in range(0,11):
#    print(j)
# for k in range(11,21):
#    print(k)
# dict = {'a': [1,2,3,4],'b':[]}
# v = dict.get('a')
# a = 1
# if a in v:
#     print('true')
# print(v)
# for i in range(0,11):
#     print(i)
# dict = {'a':}
# print(dict.get('a'))
# l = [1,2,4,7,10]
# l = input().split()
# k=[]
# for i in l:
#     if i % 3 == 0 and i % 2 == 0:
#        k.append(i)
# if len(k) > 0:
#     print(round(sum(k)/len(k)))
# else:
#     print(0)
# l = input().split()
# s = []
# for u in l:
#     s.append(u)
# print(s)
# for q in s:
#     if q % 2 == 0:
#        print(q)
# n = int(input())
# sq = n ** 0.5
# cou = str(sq)[::-1].find('.')
# if cou == 1:
#     print('true')
# else:
#     print('false')

# def isPerfectSquare(num: int) -> bool:
#     sq = num ** 0.5
#     cou = str(sq)[::-1].find('.')
#     if cou == 1:
#         print('true')
#     else:
#         print('false')
# isPerfectSquare(14)
# class Solution:
#     def isPerfectSquare(self, num: int) -> bool:
#         self.num = num
#         sq = num ** 0.5
#         cou = str(sq)[::-1].find('.')
#         if cou == 1:
#             print('true')
#         else:
#             print('false')
# sqr = Solution()
# sqr.isPerfectSquare(16)
# perfect number
# n = 79
# l = []
# for i in range(1,n):
#    if n % i == 0:
#        l.append(i)
# if sum(l) == n:
#     print('true')
# else:
#     print('false')
# def checkPerfectNumber(n):
#     l = []
#     for i in range(1,n):
#        if n % i == 0:
#            l.append(i)
#     if sum(l) == n:
#         print('true')
#     else:
#         print('false')
# checkPerfectNumber(496)
# class Solution:
#     def checkPerfectNumber(self, num: int) -> bool:
#         self.num = num
#         l = []
#         for i in range(1,num):
#            if num % i == 0:
#                l.append(i)
#         if sum(l) == num:
#             print('true')
#         else:
#             print('false')
# pn = Solution()
# pn.checkPerfectNumber(7)
# n = 192
# if n == 192 or n == 219 or n == 273 or n == 327:
#    print('true')
# n = int(input())
# l = []
# for i in range(1,n+1):
#    if i % 3 == 0 or i % 5 ==0 or i % 7 == 0:
#       l.append(i)
# print(sum(l))
# def summultiples(n):
#    l = []
#    for i in range(1, n + 1):
#       if i % 3 == 0 or i % 5 == 0 or i % 7 == 0:
#          l.append(i)
#    print(sum(l))
# summultiples(int(input()))
# class Summul:
#    def summultiples(n):
#       l = []
#       for i in range(1, n + 1):
#          if i % 3 == 0 or i % 5 == 0 or i % 7 == 0:
#             l.append(i)
#       print(sum(l))
# n = Summul
# n.summultiples(int(input()))
# class Solution:
#    def sumOfMultiples(self, n: int) -> int:
#       self.n = n
#       l = []
#       for i in range(1, n + 1):
#          if i % 3 == 0 or i % 5 == 0 or i % 7 == 0:
#             l.append(i)
#       print(sum(l))
# n = Solution
# n.sumOfMultiples(n,5)
# Python program to Find day of
# the week for a given date
# import datetime
# import calendar
#
# def findDay(date):
# 	born = datetime.datetime.strptime(date, '%d %m %Y').weekday()
# 	return (calendar.day_name[born])
# # Driver program
# n = int(input())
# s = str(n)
# k =0
# u = 1
# for i in s:
#     k += int(i)
# for j in s:
#     u *= int(j)
# print(u - k)
# def spsd(n):
#     s = str(n)
#     k = 0
#     u = 1
#     for i in s:
#         k += int(i)
#     for j in s:
#         u *= int(j)
#     print(u - k)
# spsd(int(input()))

# class Solution:
#     def subtractProductAndSum(self, n: int) -> int:
#         self.n = n
#         s = str(n)
#         k = 0
#         u = 1
#         for i in s:
#             k += int(i)
#         for j in s:
#             u *= int(j)
#         print(u - k)
# cn = Solution
# cn.subtractProductAndSum(cn,int(input()))
# n = float(input())
# Celsius = n
# Kelvin = Celsius + 273.15
# Fahrenheit = Celsius * 1.80 + 32.00
# print([Kelvin,Fahrenheit])
# class Solution:
#     def convertTemperature(self, celsius: float):
#         self.celsius = celsius
#         Kelvin = celsius + 273.15
#         Fahrenheit = celsius * 1.80 + 32.00
#         print([Kelvin,Fahrenheit])
# nu = Solution
# nu.convertTemperature(nu,36.50)
# Celsius = 36.50
# Kelvin = Celsius + 273.15
# Fahrenheit = Celsius * 1.80 + 32.00
# print([Kelvin,Fahrenheit])
