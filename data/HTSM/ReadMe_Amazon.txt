1. JSON File:
Camera, Phone, Tablet and TV reviews crawled from Amazon (http://www.amazon.com/). 

2. File Format:
Each JSON file is named using the productID from Amazon.com. So each JSON file contains all the reviews of that particular product 
from Amazon.com until the time of crawling. Structure of the file is designed using the standard JSON array of reviews. Each review contains
Title, Author, ReviewID, Overall (Rating in the range of 1 to 5), Content and Date. 

Meta data of the product includes: Price, Name, Features, ImgURL and ProductID.

3. Folder Structures:
Amazon data directory is divided into 4 directories i.e. Camera, Phone, Tablet and TV. Each of these folder is subdivided into 
6 sub directories namely 0,1000,2000,3000,4000 and 5000. This name indicates that each of these sub directories contains that number of reviews (i.e. 1000 indicates approximately 1000 reviews from Amazon.com, 0 indicates only reviews from newegg.com no review from amazon.com)

4. References
[1] Md Mustafizur Rahman and Hongning Wang. Hidden Topic Sentiment Model. WWW'2016.

