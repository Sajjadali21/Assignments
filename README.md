# Assignments
Assignment 1
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Twinkle, twinkle, little star,\n",
      "\tHow I wonder what you are!\n",
      "\t\tUp above the world so high,\n",
      "\t\tLike a diamond in the sky.\n",
      "Twinkle, twinkle, little star,\n",
      "\tHow I wonder what you are\n"
     ]
    }
   ],
   "source": [
    "print(\"Twinkle, twinkle, little star,\\n\\tHow I wonder what you are!\\n\\t\\tUp above the world so high,\\n\\t\\tLike a diamond in the sky.\\nTwinkle, twinkle, little star,\\n\\tHow I wonder what you are\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3.7.1 (default, Dec 10 2018, 22:54:23) [MSC v.1915 64 bit (AMD64)]\n",
      "sys.version_info(major=3, minor=7, micro=1, releaselevel='final', serial=0)\n"
     ]
    }
   ],
   "source": [
    "import sys\n",
    "print (sys.version)\n",
    "print (sys.version_info)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "date and time = 31/10/2019 02:26:59\n"
     ]
    }
   ],
   "source": [
    "from datetime import datetime\n",
    "dt_string = now.strftime(\"%d/%m/%Y %H:%M:%S\")\n",
    "print(\"date and time =\", dt_string)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Input radius of the circle: 2.5\n",
      "Area 19.634954084936208\n"
     ]
    }
   ],
   "source": [
    "from math import pi \n",
    "r = float(input (\"Input radius of the circle: \"))\n",
    "print (\"Area\",str(pi * r**2))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Input your First Name : sajjad\n",
      "Input your Last Name : ali\n",
      "ali sajjad\n"
     ]
    }
   ],
   "source": [
    "firstname = input(\"Input your First Name : \")\n",
    "lastname = input(\"Input your Last Name : \")\n",
    "print (lastname + \" \" + firstname)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter First Number12\n",
      "Enter Second Number35\n",
      "Sum:  47\n"
     ]
    }
   ],
   "source": [
    "a = int(input(\"Enter First Number\"))\n",
    "b = int(input(\"Enter Second Number\"))\n",
    "c = a + b\n",
    "print(\"Sum: \",c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

Assignment 2
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 1 marks sheet using grades"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\t\t\t\t\tmark-sheet\t\t\t\t\t\t\t\t\t\n",
      "Enter english marks: 80\n",
      "Ennter maths marks: 82\n",
      "Enter physics marks: 83\n",
      "Enter islamiat marks: 88\n",
      "Enter chemistry marks: 79\n",
      "\n",
      "your percentage is \n",
      " 82.39999999999999\n",
      "congrats A+ grade\n"
     ]
    }
   ],
   "source": [
    "print(\"\\t\\t\\t\\t\\tmark-sheet\\t\\t\\t\\t\\t\\t\\t\\t\\t\")\n",
    "e=int (input(\"Enter english marks: \"))\n",
    "m=int(input(\"Ennter maths marks: \"))\n",
    "p=int(input(\"Enter physics marks: \"))\n",
    "i=int(input(\"Enter islamiat marks: \"))\n",
    "c=int(input(\"Enter chemistry marks: \"))\n",
    "obt=e+m+p+i+c;\n",
    "total=500;\n",
    "per=obt/total*100;\n",
    "print(\"\\nyour percentage is \\n\",per)\n",
    "if(per>=80):\n",
    "    print(\"congrats A+ grade\")\n",
    "elif(per>=70):\n",
    "    print(\"A grade\")\n",
    "elif(per>=60):\n",
    "    print(\"B grade\")\n",
    "elif(per>=50):\n",
    "    print(\"C grade\")\n",
    "else:\n",
    "    print(\"Fail\")\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 2 to identify the number is even or odd:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter any number: 9\n",
      "number is odd\n"
     ]
    }
   ],
   "source": [
    "num=int(input(\"Enter any number: \"))\n",
    "if(num%2==0):\n",
    "    print(\"number is even\")\n",
    "else:\n",
    "    print(\"number is odd\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 3 lenght of list"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "lenght of list is: \n",
      "5\n"
     ]
    }
   ],
   "source": [
    "list=[23,56,67,78,89]\n",
    "print(\"lenght of list is: \")\n",
    "print(len(list))\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 4 to find hightest number in the list:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Maximum number in the list is: \n",
      "105\n"
     ]
    }
   ],
   "source": [
    "list=[89,67,65,45,105]\n",
    "print(\"Maximum number in the list is: \")\n",
    "print(max(list))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 5 write a program to sum all numeric item in the list:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "sum of list is: \n",
      "371\n"
     ]
    }
   ],
   "source": [
    "list=[89,67,65,45,105]\n",
    "print(\"sum of list is: \")\n",
    "print(sum(list))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# 6 print out element in the list that is less than 5:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]\n",
      "\n",
      "element that is less than 5 in the list: \n",
      "\n",
      "[1, 1, 2, 3]\n"
     ]
    }
   ],
   "source": [
    "list=[1,1,2,3,5,8,13,21,34,55,89]\n",
    "print(list)\n",
    "print(\"\\nelement that is less than 5 in the list: \\n\")\n",
    "print(list[0:4])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

Assignment 3
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Make a calculator using Python with addition , subtraction , multiplication , division and power.\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Select operation.\n",
      "1.Add\n",
      "2.Subtract\n",
      "3.Multiply\n",
      "4.Divide\n",
      "5.Power\n",
      "Enter choice(1/2/3/4/5): 5\n",
      "Enter first number: 2\n",
      "Enter second number: 4\n",
      "2.0 ^ 4.0 = 16.0\n"
     ]
    }
   ],
   "source": [
    "# This function adds two numbers \n",
    "def add(x, y):\n",
    "   return x + y\n",
    "# This function subtracts two numbers \n",
    "def subtract(x, y):\n",
    "   return x - y\n",
    "# This function multiplies two numbers\n",
    "def multiply(x, y):\n",
    "   return x * y\n",
    "# This function divides two numbers\n",
    "def divide(x, y):\n",
    "   return x / y\n",
    "# This function power two numbers\n",
    "def power(x, y):\n",
    "   return x**y \n",
    "print(\"Select operation.\")\n",
    "print(\"1.Add\")\n",
    "print(\"2.Subtract\")\n",
    "print(\"3.Multiply\")\n",
    "print(\"4.Divide\")\n",
    "print(\"5.Power\")\n",
    "# Take input from the user \n",
    "choice = input(\"Enter choice(1/2/3/4/5): \")\n",
    "num1 = float(input(\"Enter first number: \"))\n",
    "num2 = float(input(\"Enter second number: \"))\n",
    "if choice == '1':\n",
    "   print(num1,\"+\",num2,\"=\", add(num1,num2))\n",
    "elif choice == '2':\n",
    "   print(num1,\"-\",num2,\"=\", subtract(num1,num2))\n",
    "elif choice == '3':\n",
    "   print(num1,\"*\",num2,\"=\", multiply(num1,num2))\n",
    "elif choice == '4':\n",
    "   print(num1,\"/\",num2,\"=\", divide(num1,num2))\n",
    "elif choice == '5':\n",
    "   print(num1,\"^\",num2,\"=\", power(num1,num2))\n",
    "else:\n",
    "   print(\"Invalid input\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Write a Python script to add a key to a dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{0: 'sajjad', 1: 'ali'}\n",
      "{0: 'sajjad', 1: 'ali', 2: 'hydari'}\n",
      "hydari\n"
     ]
    }
   ],
   "source": [
    "n = {0:\"sajjad\", 1:\"ali\"}\n",
    "print(n)\n",
    "n.update({2:\"hydari\"})\n",
    "print(n)\n",
    "print(n[2])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Write a Python program to sum all the numeric items in a dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum : 600\n"
     ]
    }
   ],
   "source": [
    "def Sum(myDict):       \n",
    "    sum = 0\n",
    "    for i in myDict: \n",
    "        sum = sum + myDict[i]       \n",
    "    return sum  \n",
    "dict = {'a': 100, 'b':200, 'c':300} \n",
    "print(\"Sum :\",Sum(dict)) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Write a program to check if there is any numeric value in list using for loop"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]\n",
      "Element Exists\n"
     ]
    }
   ],
   "source": [
    "#check if there is any numeric value in list\n",
    "test_list = [ 1,2,3,4,5,6,7,8,9,10 ]\n",
    "print(test_list) \n",
    "for i in test_list: \n",
    "    if(i == 4) : \n",
    "        print (\"Element Exists\")\n",
    "        "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Write a program to identify duplicate values from list"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[20, 30, -20, 60]\n"
     ]
    }
   ],
   "source": [
    "def Repeat(x): \n",
    "    size = len(x) \n",
    "    repeated = [] \n",
    "    for i in range(size): \n",
    "        k = i + 1\n",
    "        for j in range(k,size): \n",
    "            if x[i] == x[j] and x[i] not in repeated: \n",
    "                repeated.append(x[i]) \n",
    "    return repeated \n",
    "list1 = [10, 20, 30, 20, 20, 30, 40, 50, -20, 60, 60, -20, -20] \n",
    "print(Repeat(list1)) "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Write a Python script to check if a given key already exists in a dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Key is present in the dictionary\n",
      "Key is not present in the dictionary\n"
     ]
    }
   ],
   "source": [
    "d = {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}\n",
    "def kp(x):\n",
    "  if x in d:\n",
    "      print('Key is present in the dictionary')\n",
    "  else:\n",
    "      print('Key is not present in the dictionary')\n",
    "kp(5)\n",
    "kp(9)"
   ]
   "pygments_lexer": "ipython3",
   "version": "3.6.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
}
