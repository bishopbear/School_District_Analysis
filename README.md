# School_District_Analysis
For this project we are tasked with analyzing grade data for a school district with approx. 40,000 students grades 9 through 12. Our analysis will a basis for determining how to improve grades across the district. To do this we will clean and parse the data to provide insights to help us with recommending next steps.

After initially reviewing the data, we noticed that somehow some of the students names included a prefix such as Dr., Mr., Mrs., and some suffixes such as DDS. etc. We are not sure how these got here (could be a student prank!), however, we did have to clean this up. We were able to identify all prefixes and suffixes using a mixture of different pandas functions and methods and then run a loop to finally clean the data. Once we did this we moved into parsing the data so that we could isolate our desired metrics.

Tables presenting each of the following metrics:
* Top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score received by students in each grade level at each school
* The average reading score received by students in each grade level at each school
* School performance based on the budget per student
* School performance based on the school size 
* School performance based on the type of school

The school district summary will be a high-level snapshot of the district's key metrics:

Below we have included some screen shots of the aggregated data.

DISTRICT SUMMARY
![district_summary](https://user-images.githubusercontent.com/58608736/178094316-b89c6a76-09fe-4bcb-b6e0-6b702a0ec974.png)

SCHOOL SUMMARY RESULTS
![school_summary](https://user-images.githubusercontent.com/58608736/178093932-5a98e538-feaf-4629-9e3d-0df1d6fea651.png)

SCORES BY SCHOOL SPENDING
![spending_summary](https://user-images.githubusercontent.com/58608736/178093908-dda62f67-55a9-4c6e-a9b7-dc8db5e79212.png)

SCORES BY SCHOOL SIZE
![school_size](https://user-images.githubusercontent.com/58608736/178094030-c5498e34-bd69-40da-b795-a249f2940661.png)

SCORES BY SCHOOL TYPE
![school_type](https://user-images.githubusercontent.com/58608736/178093992-f51ea24f-e6b5-4618-b533-5eedde09dfd4.png)

With these data we can come to some initial conclusions. 
* We can see that charter schools have vastly higher passing rates
* Generally, the smaller the school the better the grades
* And interestingly enough, money spent does not simply equate to higher scores

With these findings we can begin to formulate questions for further analysis and then finally recommendations for improvement.

