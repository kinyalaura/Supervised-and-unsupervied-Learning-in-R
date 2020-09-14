# KiraPlastinina Customer Segmentation

![Kira Plastinina Logo](https://www.malls.com/upload/iblock/c71/c718e9cb0d0d795ab79ec46407f36075.jpg)

>**Description**

Kira Plastinina is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, 
Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s 
behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups.

*Approach 1: K Means Clustering *

This is a clustering algorithms and usually the first thing practitioners apply when solving clustering tasks to get an idea of the structure of the dataset. 
The goal of kmeans is to group data points into distinct non-overlapping subgroups.

*Approach 2: Heirarchical Clustering*

This is an algorithm that groups similar objects into groups called clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, 
and the objects within each cluster are broadly similar to each other.

**Dataset Columns**

*The dataset consists of 10 numerical and 8 categorical attributes. The 'Revenue' attribute can be used as the class label.

*"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another. 

*The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 

*The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 

*The value of the "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.

*The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 

*The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 

*The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.

**Requirements**

Google colab notebook

**Setup instructions**

Save a copy of the notebook in your drive and open it to access.

**Technologies used**

R packages
* Data.table
* Ggplot2
* Corrplot
* Pastecs
* Psych
* Factoextra
* Hrbrthemes

R libraries
* Tidyr
* Tidyverse
* GridExtra
* Grid
* Ggplot2
* Lattice
* Factoextra
* Hrbrthemes

**Bugs**

There were no known bugs are the time of completion

**Support**

In case of any clarifications or suggestions with regards to this project email me at ngolua.kinya@gmail.com

>**Licences**

MIT license
