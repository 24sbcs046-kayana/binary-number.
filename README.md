# binary-number.
def decimalToBinary(num):
&quot;&quot;&quot;This function converts decimal number
to binary and prints it&quot;&quot;&quot;
if num &gt; 1:
decimalToBinary(num // 2)
print(num % 2, end=&#39;&#39;)

# decimal number
number = int(input(&quot;Enter any decimal number: &quot;))
decimalToBinary(number)
