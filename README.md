# CS-360

Project 3 video link: https://youtu.be/XCVNre2vvr8

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
  The app is a basic inventory management system that allows its users to track items, adjust quantities on the fly, and get alerts for low stock and out of stock items. It is made for warehouse managers at small    businesses to be able to see inventory levels and help to prevent running out of stock.
  
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
  The app needed a login screen, an inventory grid screen, and an sms settings screen. I made sure to keep users in mind by using labels on all the buttons, and I placed the "add item" section above the grid so it   would be easy and self explanatory to add an item.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
  At first, I did not code as incrementally as I should have and testing took longer than it should have. I did start with the login screen first, the inventory screen second, then sms functionality last. The strategy will be applied to future projects, I just need to isolate functions within the functions more.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
  I used Logcat in android studio to make sure each feature worked and it also helped to track errors. I had an issue with items swapping when I changed their quantities and found that I had to change how I was storing the data on the grid screen to get the bug fixed.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
  My sms zero inventory alert did not work at all even though it was coded the same as the low inventory. I found that I had used a special character and I had to remove it from the text. Also, I changed the data storage from a hash set to a list so the order swapping would stop happening.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
  I think the inventory grid screen was very successful. I implemented the recyclerview that supported add, delete, and quantity adjustment all on one screen. Also, the way to add an item was on the same screen and the inventory updated immediatley.
