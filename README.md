# program-to-find-the-area-of-a-triangle-whose-sides-are-given
import math
a = float(input(&quot;Enter the length of side a: &quot;))
b = float(input(&quot;Enter the length of side b: &quot;))
c = float(input(&quot;Enter the length of side c: &quot;))

s = (a+b+c)/2
area = math.sqrt(s*(s-a)*(s-b)*(s-c))
print(&quot; Area of the triangle is: &quot;, area)
