# Chapter-7-Extra-5
 
letter_table = str.maketrans('ABCDEFGHIJKLMNOPQRSTUVWXYZ', '22233344455566677778889999')

number = input("Enter the number in the format of XXX-XXX-XXXX: ")

print(number.translate(letter_table))
