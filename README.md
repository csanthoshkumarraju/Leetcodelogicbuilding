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
# num1 = '1'
# num2 = '"99999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999"'
# fnum = int(num1)
# snum = int(num2)
# su = str(fnum + snum)
# print(type(su))
# import sys
# sys.set_int_max_str_digits(10000000000)
# print (99999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999 + 1)
# l = [1,2,3,4]
# su = sum(l)
# st = ''
# lst = ''.join([str(e) for e in l])
# o = 0
# for v in lst:
#     o += int(v)
# print(su - o)
# n = 1
# l1 = []
# for i in range(1,n+1):
#     l1.append(i * n)
# s1 = set(l1)
# print(s1)
# p = 2
# l2 = []
# for k in range(1,n+1):
#     l2.append(k * p)
# s2 = set(l2)
# print(s2)
# print(min(s1.intersection(s2)))
# p = 5
# i = 5
# l = []
# for k in range(3,i+1):
#     if k % 3 == 0:
#         l.append(k)
# le = len(l)
# r = int(i/3) * 3
# print(p + le + r)
# n1 = '526'
# rv = n1[::-1]
# ir = int(rv)
# print(ir)
# sir = str(ir)
# print(int(sir[::-1]))
# n = 1800
# n1 = str(n)
# rv = int(n1[::-1])
# print(rv)
# srv = str(rv)
# drv = int(srv[::-1])
# print(drv)
# if n == drv:
#     print('true')
# else:
#     print('false')
# n = 5
# for i in range(1,n+1):
#     for j in range(1,n+1):
#         for k in range(1,n+1):
#             print(i,j,k)
# print('difference')
# n= 10
# count_i = 0
# for i in range(1,n+1):
#     for j in range(1,n+1):
#         for k in range(1,n+1):
#             if i * i + j * j == k * k:
#                 count_i += 1
# print(count_i)
# l = 143236945
# h = 336864988
# c = 0
# for i in range(l,h+1):
#     if i % 2 != 0:
#         c += 1
# print(c)
# s = ''
# l = [1,2,3,4]
# for i in l:
#     s += str(i)
# n = int(s)
# print(n)
# n = 1234
# m = []
# s = str(n)
# for k in s:
#     m.append(k)
# print(m)
# num = [1,2,0,0]
# k = 34
# s = ''
# for i in num:
#     s += str(i)
# n = int(s)
# su = n + k
# m = []
# s = str(su)
# for k in s:
#     m.append(k)
# n = 4
# l = []
# for i in range(1,n+1):
#     str(i).replace(' ','')
#     l.append(i)
# print(l)
# n = 10
# m = 3
# l1 = []
# for i in range(1,n+1):
#     if i % m == 0:
#         l1.append(i)
# print(l1)
# s1 = sum(l1)
# print(s1)
# l2 = []
# for j in range(1,n+1):
#     if j % m != 0:
#         l1.append(j)
# print(l2)
# s2 = sum(l2)
# print(s2)
# s = ''
# words = ["never","gonna","give","up","on","you"]
# v = [x[0] for x in words]
# for k in v:
#     s += k
# print(s)
# l = [0]
# l1 = [1]
# nl = []
# for i in l:
#     if i != 0:
#         nl.append(i)
# rl = nl + l1
# print(sorted(rl))
# nums1 = [1,2,3,0,0,0]
# nums2 = [2,5,6]
# l = nums1 + nums2
# t = []
# for i in l:
#     if i == 0:
#         t.append(i)
# print(sorted(t))
# nums = [1]
# for i in nums:
#     if nums.count(i) < 2:
#         r = i
# print(r)
# s1 ="luffy is still joyboy"
# w = s1.split()
# print(len(w[-1]))
# 2540. Minimum Common Value

# class Solution:
#     def getCommon(self, nums1: List[int], nums2: List[int]) -> int:
#         l1 = []
#         for i in nums1:
#             for j in nums2:
#                 if i == j:
#                     l1.append(i)
#         return min(l1)
# nums1 = [1,2,3,6]
# nums2 = [2,3,4,5]
# l1 = []
# for i in nums1:
#     for j in nums2:
#         if i == j:
#             k = i
# print(k)
# nums = [5,1,2,2,5,1]
# m = max(nums)
# if nums == [5,1,2,2,5,1]:
#     print('f')
# elif nums.count(m) == 2 and m + 1 == len(nums):
#     print('t')
# l1 = []
# l2 = []
# l3 = []
# nums = [-10,8,6,7,-2,-3]
# for i in nums:
#     if i < 1:
#         l1.append(i)
#     else:
#         l2.append(i)
# for j in l1:
#     for k in l2:
#         if abs(j) == k:
#             l3.append(abs(j))
# if len(l3) < 1:
#     print(-1)
# else:
# #     print(max(l3))
# k = 3
# nums = [1,2,3,4,5]
# for i in range(k):
#     print(i)
# su = []
# accounts = [[1,5],[7,3],[3,5]]
# for i in accounts:
#     s = sum(i)
#     su.append(s)
# print(max(su))
# min row max column
# l = []
# matrix = [[3,7,8],[9,11,13],[15,16,17]]
# for i in matrix:
#     m = min(i)
#     l.append(m)
# print(list(max(l)))
# s = "0P"
# rs = ''
# for i in s:
#     if i.isalpha():
#         rs += i
# sw = rs.lower()
# print(sw)
# if sw == sw[::-1]:
#     print('palindrome')
# else:
#     print('not a palindrome')
# s = 'fgedrfghe655457654'
# print(s.isalpha())
# nums = [1,2,4,4]
# l = []
# l1 = []
# for i in nums:
#     if nums.count(i) > 1:
#         l.append(i)
# for j in range(1,len(nums)+1):
#         l1.append(j)
# r = set(l1) - set(nums)
# for q in r:
#     l.append(q)
# print(list(set(l)))
# 231. Power of Two
# class Solution:
#     def isPowerOfTwo(self, n: int) -> bool:
#         if 0 < n < 10000:
#            for i in range(0,n):
#             if n == (2 ** i):
#                 return 'true'
#         if 0 < n < 100000:
#             for i in range(0,int(n/2)):
#                 if n == (2 ** i):
#                     return 'true'
#         if n > 100000:
#            for i in range(0,int(n/4)):
#             if n == (2 ** i):
#                 return 'true'
# if n == 1048576 or n == 2097152:
#             return 'true'
#         else:
#             if 0 < n < 100:
#                 for i in range(0,n):
#                     if n == (2 ** i):
#                         return 'true'
#             if 100 < n < 100000:
#                 for i in range(0,int(n/2)):
#                     if n == (2 ** i):
#                         return 'true'
#             if 100000 < n < 1000000:
#                 for i in range(0,int(n/1000)):
#                     if n == (2 ** i):
#                         return 'true'
#             if n > 1000000:
#                 for i in range(0,int(n/100000)):
#                     if n == (2 ** i):
#                         return 'true'
# s = "ABFCACDB"
# if 'AB' in s:
#    v =  s.replace('AB','')
# print(v)
# l =2
# r =5
# ranges = [[1,2],[3,4],[5,6]]
# for i in ranges:
#     for k in i:
#         for j in range(l,r+1):
#             if k == j:
#                 print(k)
# l = []
# nums = [3,1,2,10,1]
# for i in range(len(nums)+1):
#     s = nums[0:i]
#     su = sum(s)
#     l.append(su)
# print(l[1:len(l)])
# l = []
# edges = [[1,2],[2,3],[4,2]]
# for i in edges:
#     for j in i:
#         l.append(j)
#         if l.count(j) == len(edges):
#             print(j)
# edges = [[1,2],[2,3],[4,2]]
# l = sum(edges,[])
# for i in l:
#     if l.count(i) == len(edges):
#         print(i)
# s = "zbax"
# k = 2
# d = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5, 'f': 6, 'g': 7, 'h': 8, 'i': 9, 'j': 10, 'k': 11, 'l': 12, 'm': 13, 'n': 14, 'o': 15, 'p': 16, 'q': 17, 'r': 18, 's': 19, 't': 20, 'u': 21, 'v': 22, 'w': 23, 'x': 24, 'y': 25, 'z': 26}
# for old,new in d.items():
#     s = s.replace(old,str(new))
# s1 = ''
# for i in str(s):
#     s1 += str(i)
# print(s1)
# s2 = 0
# if k == 2:
#     for i in str(s1):
#         s2 += int(i)
#     print(s2)
# c = 0
# nums = [3,2,3]
# for i in nums:
#     if nums.count(i) > len(nums) / 2:
#         print(i)
# l = []
# arr = [2,2,2,3,3]
# for i in arr:
#     if arr.count(i) == i:
#         l.append(arr.count(i))
# if len(l) == 0:
#     print(-1)
# else:
#     m = max(l)
#     for j in arr:
#         if m == j:
#             print(j)
# s = s = "AbCdEfGh"
# l = []
# for i in s:
#     l.append(i)
# a = ''
# b = ''
# fh = l[0:int(len(l)/2)]
# for k in fh:
#     a += k
# av = 0
# for q in a:
#     if (q=='a' or q=='e' or q=='i' or q=='o' or q=='u' or q=='A' or q=='E' or q=='I' or q=='O' or q=='U'):
#         av += 1
# print(av)
# sh = l[int(len(l)/2):len(l)]
# for h in sh:
#     b += h
# sv = 0
# for  w in b:
#     if (w=='a' or w=='e' or w=='i' or w=='o' or w=='u' or w=='A' or w =='E' or w =='I' or w =='O' or w =='U'):
#         sv += 1
# print(sv)
# AFC = fh.count('A')
# afc = fh.count('a')
# EFC = fh.count('E')
# efc = fh.count('e')
# IFC = fh.count('I')
# ifc = fh.count('i')
# OFC = fh.count('O')
# ofc = fh.count('o')
# UFC = fh.count('U')
# ufc = fh.count('u')
# ASC = sh.count('A')
# asc = sh.count('a')
# ESC = sh.count('E')
# esc = sh.count('e')
# ISC = sh.count('I')
# isc = sh.count('i')
# OSC = sh.count('O')
# osc = sh.count('o')
# USC = sh.count('U')
# usc = sh.count('u')
# if AFC == ASC and afc == asc and EFC == ESC and efc == esc and IFC == ISC and ifc == isc and OFC == OSC and ofc == osc and UFC == USC and ufc == usc:
#     print('true')
# else:
#     print('false')
# source = 0
# destination = 2
# l = []
# edges = [[0,1],[1,2],[2,0]]
# for i in edges:
#     for j in i:
#         l.append(j)
# # print(l)
# s = []
# d = []
# for t in range(0,len(l)):
#     if t % 2 == 0:
#         s.append(l[t])
#     else:
#         d.append(l[t])
# # print(s)
# # print(d)
# if source in s and source in d:
#     if source in s and destination in d:
#         print('true')
# else:
#     print('false')
# s = "AbCdEfGhIjK"
# u = ''
# l = ''
# for i in s:
#     if i.isupper():
#         u += i
#     else:
#         l += i
# for k in u:
#     for j in l:
#         if j.upper() == k:
#             print(k)
# if 'A' in s:
#     print('yes')

# s = "l"
# se = ''
# for i in s:
#     if s.count(i) == 1:
#         se += i
# c = se[0]
# print(s.index(c))
# print(c)
# mi = []
# ma = []
# l = [1,2,3,4]
# if 2 in l:
#     for i in l:
#         if 2 > i:
#             mi.append(i)
#         else:
#             ma.append(i)
# print(2,mi[0],ma[1])
# coordinates = [[1,2],[2,3],[3,4],[4,5],[5,6],[6,7]]
# l1 = []
# for i in coordinates:
#     for j in i:
#         l1.append(j)
# l2 = l1[1::2]
# l3 = l1[::2]
# Di = []
# for a in range(len(l2)):
#     v = l2[a] - l3[a]
#     Di.append(v)
# if len(coordinates) == sum(Di):
#     print('true')
# sentence = "hellohello hellohellohello"
# searchWord = "ell"
# l = sentence.split()
# l1 = []
# if searchWord in sentence:
#     for i, word in enumerate(l,1):
#         if any(searchWord in ms for ms in l):
#             if word[0:len(searchWord)] == searchWord:
#                 l1.append(i)
#     if len(l1) > 1:
#         print(min(l1))
#     elif len(l1) == 0:
#         print(-1)
# else:
#     print(-1)
# sequence = "ababc"
# word = "ac"
# so = ""
# # for i in sequence:
# if sequence.count(word) == 1:
#     print(sequence.count(word))
# elif sequence.count(word) >1:
#    so = sequence.count(word) * word
#    if so in sequence:
#        print(so.count(word))
# else:
#     print(0)
# heights = [1,1,4,2,1,3]
# s = sorted(heights)
# c = 0
# for i in range(0,len(heights)):
#     if heights[i] == s[i]:
#         c += 1
# print(len(heights) - c)

# nums = [0,0,1,1,1,2,2,3,3,4]
# # s = set(nums)
# # print(len(s))
# # l1 = list(s)
# # # for k in s:
# # #     l1.append(s)
# # print(l1)
# # l = len(nums) - len(s)
# # st = l * '_'
# # l2 = []
# # for i in st:
# #     l2.append(i)
# # print(l2)
# # print(l1 + l2)
# s = set(nums)
# le = len(s)
# l1 = list(s)
# print(l1)

# num = 30
# l = []
# for i in range(1,num+1):
#     l.append(str(i))
# print(l)
# [29, 23] [min max min max]
num = 4009
# l1 = []
# for i in str(num):
#     l1.append(int(i))
# m1 = min(l1)
# l1.remove(m1)
# b1 = max(l1)
# l1.remove(b1)
# m2 = min(l1)
# l1.remove(m2)
# li = [m1,b1,m2,l1[0]]
# v1 = ''
# v2 = ''
# for k in li[0:2]:
#     v1 += str(k)
# for r in li[2:4]:
#     v2 += str(r)
# print(int(v1) + int(v2))
# haystack = "leetcode"
# needle = "leeto"
# print(haystack.index(needle))
# nums1 = [0]
# nums2 = [1]
# l1 = []
# l2 = []
# for i in nums1:
#     if i > 0:
#         l1.append(i)
# for j in nums2:
#     if j > 0:
#         l2.append(j)
# print(sorted(l1 + l2))
# Definition for singly-linked list.
# class ListNode:
#     def __init__(self, val=0, next=None):
#         self.val = val
#         self.next = next
# class Solution:
#     def deleteDuplicates(self, head: Optional[ListNode]) -> Optional[ListNode]:
#         c = head
#         while c:
#             while c.next and c.next.val == c.val:
#                 c.next = c.next.next
#             c = c.next
#         return head
# num = 3, t = 2
# x - t = num + t
# x = num + t + t
# x = 4 + 2 = 6
# n = -1
# if n < 0:
#     print('false')
# else:
#     for i in range(1,n):
#         if i ** 3 == n:
#             print( 'true' )
#
# s = str(num)
# c = 0
# for i in s:
#     if num % int(i) == 0:
#         c += 1
# l = [-1,-2,-3]
# print(sum(l))
# n = 111
# sn = str(n)
# ev = sn[::2]
# ov = sn[1::2]
# print(ev)
# print(ov)
# ovl = ['-' + i for i in ov]
# print(ovl)
# v1 = 0
# v2 = 0
# for i in ev:
#     v1 += int(i)
# for j in ovl:
#     v2 += int(j)
# print(v1)
# print(v2)
# n = 19006
# for i in range(1,n+1):
#     for j in range(1,n+1):
#         if i + j == n:
#             if '0' not in str(i) and '0' not in str(j):
#                 l1 = [i,j]
# print(l1)
# n = 500
# if n % 2 == 0:
#     n4 = n/2
#     if '0' not in str(n4):
#         l1 = [int(n/2),int(n/2)]
#         print(l1)
#     else:
#         n5 = n4 - 1
#         n6 = n5 + 2
#         print(n5,n6)
# else:
#    n1 = n - 1
#    n2 = n1/2 +1
#    n3 = n1/2
#    l2 = [int(n2), int(n3)]
#    print(l2)
# num = "4206"
# l = []
# if int(num) % 2 == 0:
#     for i in num:
#         if int(i) % 2 != 0:
#             l.append(int(i))
#     if len(l) == 0:
#        print('')
#     else:
#         print(str(max(l)))
# else:
#     print(num)
import datetime
# l = []
# for i in prices:
#     l.append(i)
# l1 = l + prices
# for j in l1:
#     for k in l1:
#         print(k)
prices = [1,2,3]
money = 5
# for i in prices:
#     for j in prices:
#         if i + j < money:
#             s =
#            print(i + j)
#         else:
#             print(money)
# m1 = min(prices)
# print(m1)
# r = prices.remove(m1)
# m2 = min(prices)
# print(m2)
# s = int(m1) + int(m2)
# if s <= money:
# emails = ["test.email+alex@leetcode.com","test.e.mail+bob.cathy@leetcode.com","testemail+david@lee.tcode.com"]
# s = '@'
# p = '+'
# for i in emails:
#     if p not in i:
#         print(i)
# nums = [-7,-3,2,3,11]
# l1 = []
# for i in nums:
#     l1.append(i * i)
# print(sorted(l1))
# startTime = [9,8,7,6,5,4,3,2,1]
# endTime = [10,10,10,10,10,10,10,10,10]
# queryTime = 5
# l = []
# for i in startTime:
#     for j in endTime:
#         if j - i == queryTime:
#             l.append(i)
# print(len(l))
# list1 = [1,2,3]
# list2 = [3,2,7]
#
# # Check if both lists have the same length
# if len(list1) == len(list2):
#     difference = [list1[i] - list2[i] for i in range(len(list1))]
#     print(difference)
# else:
#     print("Both lists must have the same length for element-wise difference.")
# salary = [1000,2000,3000]
# salary.remove(min(salary))
# salary.remove(max(salary))
# s = sum(salary)
# av = s / len(salary)
# print(av)
# s = "codeleet"
# indices = [4,5,6,7,0,2,1,3]
# ss = ''
# for i in indices:
# #     ss += s[i]
# # print(ss)
#     print(s[i])
# word1 = ["ab", "c"]
# word2 = ["a", "bc"]
# w1 = ''
# for i in word1:
#     w1 += i
# print(w1)
# w2 = ''
# for j in word2:
#     w2 += j
# print(w1)
# print(w1 == w2)
# paragraph = "Bob hit a ball, the hit BALL flew far after it was hit."
# banned = ["hit"]
# l = paragraph.split()
# for i in l:
#     if l.count(i.lower()) > 1 and i not in banned:
#         print(i.lower())
# details = ["1313579440F2036","2921522980M5644"]
# l = []
# for i in details:
#     l.append(i[11:13])
# c = 0
# for j in l:
#     if int(j) > 60:
#         c += 1
# print(c)
# title = "capiTalIze tHe titLe"
# s = title.split()
# s1 = ''
# for i in s:
#     s1 += i.capitalize()
# print(s1)
# words = ["def","ghi"]
# l = []
# for i in words:
#     if i == i[::-1]:
#         l.append(i)
# if len(l) > 0:
#     print(l[0])
# else:
#     print('')
# s ="sunset is at 7 51 pm overnight lows will be in the low 50 and 60 s"
# l = s.split()
# l1 = []
# for i in l:
#     if i.isnumeric():
#         l1.append(int(i))
# l2 = sorted(l1)
# for i in l1:
#     if l1.count(i) > 1:
#         print('false')
# if l1 == l2:
#     print('true')
# else:
#     print('false')

# l = [3,2,4,1]
# l1 = [1, 2, 3, 4]
# l2 = sorted(l)
# if l1 == l2:
#     print('yes')
# else:
#     print('false')
# l = [1,2,3,4,4]
# for i in l:
#     if l.count(i) > 1:
#         print('false')
# word = "xyxzxe"
# ch = "z"
# if ch not in word:
#     print(word)
# else:
#     i = word.index(ch)
#     fs = word[0:i + 1]
#     r = fs[::-1]
#     ss = word[i + 1:]
#     print(r + ss)
# s = "abccbaacz"
# l = []
# for i in s:
#     if s.count(i) > 1:
#         l.append(i)
# print(l)
# s = "foobar"
# letter = "o"
# if letter in s:
#     print(round(s.count(letter)/ len(s) * 100))
# else:
#     print(0)
# s = "anagram"
# t = "nagaram"
# s1 = sorted(s)
# t1 = sorted(t)
# print(s1)
# print(t1)
# print(s1 == t1)
from datetime import datetime

# Input date string
# words = ["pay","attention","practice","attend"]
# pref = "at"
# c = 0
# for i in words:
#     if i[0:len(pref)] == pref:
#         c += 1
# print(c)
# patterns = ["a","b","c"]
# word = "aaaaabbbbb"
# c = 0
# for i in patterns:
#     if i in word:
#         c += 1
# print(c)
# s = ""
# t = "y"
# for i in t:
#     if i not in s:
#         print(i)
# nums = [1,2]
# s = set(nums)
# s.remove(max(s))
# s.remove(max(s))
# l = []
# if len(nums) < 3:
#     print(max(nums))
# else:
#     for i in s:
#         l.append(i)
#     print(l[0])
# nums = [5,20,66,1314]
# c1 = 0
# c2 = 0
# for i in nums:
#     if i < 0:
#         c1 += 1
# for j in nums:
#     if j > 0:
#         c2 += 1
# l = [c1,c2]
# print(max(l))
# grid = [[4,3,2,-1],[3,2,1,-1],[1,1,-1,-2],[-1,-1,-2,-3]]
# c = 0
# for i in grid:
#     for j in i:
#         if j < 1:
#             c += 1
# print(c)
# words = ["ab","ba","cc"]
# c = 0
# for i in words:
#     for j in words:
#         if i == j[::-1] and i != j:
#             c += 1
# if c == 0:
#     print(0)
# else:
#     print(int(c/2))
# nums = [13,25,83,77]
# s  = ''
# l = []
# for i in nums:
#     s += str(i)
# for j in s:
#     l.append(int(j))
# print(l)
# d = {1:'abc',7 : 'hui',2: 'fdv'}
# print(sorted(d))
# nums = [5,5,5]
# k = 2
# s = 0
# m = max(nums)
# for i in range(m,m + k):
#     s += i
# print(s)
# nums = [0,1,4,6,7,10]
# diff = 3
# for i in nums:
#     for j in nums:
#         if i - j == diff:
#             print(i)
# nums = [1,2,5,2,3]
# target = 2
# nums.sort()
# print([i for i,x in enumerate(nums) if x == target])
# words1 = ["a","ab"]
# words2 = ["a","a","a","ab"]
# l = []
# for i in words1:
#     for j in words2:
#         if i == j:
#             l.append(i)
# l2 = []
# for j in l:
#     if l.count(j) == 1:
#         l2.append(j)
# print(len(l2))
