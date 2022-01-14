# HW1 - Course Setup and RCR

Yash Prakash
CS 800  
Due: Jan 18, 2022

## Git, GitHub

***Q1.** What is your GitHub username?*
<br/> veeprayas

## ODU-CS Linux

***Q2:** How can you contact the Computer Science help desk?*
<br/> For technical support I contact the systems group via mail at root@cs.odu.edu they are located at Dragas Hall. They have an amazing group of students and are really friendly and privide almost immediate suport. For general assistance I approach ITS help desk via email itshelp@odu.edu.

***Q3:** What hostname should you use to connect to the ODU-CS systems?*
<br/> My hostname is cs_yprak001.

***Q4:** In what directory will your webpages reside?*
<br/>I included the directory of my webpages in ~/secure_html.

***Q5:** What is the URL of your new webpage?*
<br/>The URL of my webpage is https://www.cs.odu.edu/~cs_yprak001/. I have built a website for this assignment. But I will be working to improve it in the comming weeks. 

## Markdown

***Q6.** Replace the code in the fenced code block with another block of code. You can use some Python code, or you can insert code from a different language -- just change the language indicated so that syntax highlighting still works properly.*

```python

# Function for nth Fibonacci number
def Fibonacci(n):
   
    # Check if input is 0 then it will
    # print incorrect input
    if n < 0:
        print("Incorrect input")
 
    # Check if n is 0
    # then it will return 0
    elif n == 0:
        return 0
 
    # Check if n is 1,2
    # it will return 1
    elif n == 1 or n == 2:
        return 1
 
    else:
        return Fibonacci(n-1) + Fibonacci(n-2)
 
# Driver Program
print(Fibonacci(9))
 

```

***Q7.** Edit the table so that it matches the first 3 weeks of our class schedule, as given in our [syllabus](https://github.com/odu-cs800-research/public/blob/main/spr22/syllabus.md).*

This is a simple table.  

|Date|Topic|
|:---:|:---:|
|Sep 1, 3|Introduction, What's Vis and Why Do It?|
|Sep 8, 10|Data and Data Cleaning|

|Week|Class Date|Topic|
|:---:|:---:|:---:|
|1|Jan 11, 13|Course Intro, What's Grad School All About?|
|2|Jan 18, 20|Academic Presence, Research Careers|
|3|Jan 25, 27|Reading Academic Papers|

## LaTeX and Overleaf

***Q8.** What is the link to view your newly created project? (Under "Anyone with this link can view this project")*
<br/> The link to my newly created project is https://www.overleaf.com/read/wcpdcxktcqdh

## Responsible Conduct of Research

***Q9.** Include the image in your report in place of the "Growth of the Early Web" image. Make sure to change the description of the image in the report.*

The example figure below shows the growth in the number of websites between 1993 and 1996.  I've used HTML to insert this to show how images can be scaled.  Change the width value as needed so that your image is an appropriate size.

<img src="growth-early-web.png" width=400 />

<br/>
<img src="https://i0.wp.com/statisticsbyjim.com/wp-content/uploads/2021/06/bar_chart_clustered.png?resize=300%2C200&ssl=1" width=400 />
<br/> In above bar chart in the x-axis you can see three categorical variables which have two values each namely male and female. And on y-axis you have frequency count.
The graph highlights preferences of three falvours i.e chocolate,strawberry and vanilla on basis of gender. 

## References

* The Missing Semester of Your CS Education, https://missing.csail.mit.edu/
* ODU Career Pathways Program, https://sites.wp.odu.edu/careerpathways/

***Q10.** Replace the references with three webpages that you've visited so far this semester related to this class. These should include both the title of the webpage/article and the URL.*
 
## References

* SYSTEMS GROUP, https://systems.cs.odu.edu/Main_Page
* ITS HELP DESK, https://www.odu.edu/ts/helpdesk
* Python Program for Fibonacci numbers, https://www.geeksforgeeks.org/python-program-for-program-for-fibonacci-numbers-2/
* Bar Charts: Using, Examples, and Interpreting, https://statisticsbyjim.com/graphs/bar-charts/
