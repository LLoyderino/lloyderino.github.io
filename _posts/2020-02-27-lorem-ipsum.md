---
layout: post
title:  "Lorem Ipsum"
categories: testing
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras a dolor nec ante viverra dictum sed eget ligula. Aliquam molestie cursus ligula. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris id enim volutpat, porttitor orci sit amet, fringilla enim. Phasellus rutrum sem eu volutpat accumsan. Aliquam elementum in quam vitae imperdiet.

Pellentesque venenatis mollis ligula ut ullamcorper. Duis vel laoreet sem. Pellentesque porta turpis non ligula dapibus, eget elementum tortor pretium. Duis finibus ultricies dui et vulputate. Nullam semper non dui eu ultrices. Sed lacinia turpis neque, ut elementum risus facilisis vitae. Proin eleifend vel elit vel congue.

`Nullam rhoncus odio non lorem bibendum vestibulum`

Curabitur vel rhoncus massa, pharetra vestibulum odio. Vestibulum pulvinar ultrices ligula. Donec nec dignissim sapien, at pharetra erat. Duis quis tellus non nulla finibus faucibus. Cras quis velit sem. `Cras` ligula mauris, tempus `non volutpat` nec, vehicula sed nibh. Suspendisse feugiat, arcu eget tincidunt lobortis, mauris lectus hendrerit neque, eu feugiat mauris diam in metus. Vivamus finibus rhoncus tempor.

Testing some code:

{% highlight python %}
# Python program to display the Fibonacci sequence

def recur_fibo(n):
   if n <= 1:
       return n
   else:
       return(recur_fibo(n-1) + recur_fibo(n-2))

nterms = 10

# check if the number of terms is valid
if nterms <= 0:
   print("Plese enter a positive integer")
else:
   print("Fibonacci sequence:")
   for i in range(nterms):
       print(recur_fibo(i))
{% endhighlight %}

Testing some link [google](https://www.google.com)
