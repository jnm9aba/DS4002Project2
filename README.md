## SRC

### Code Installation/Building

The code is in the Jupyter Notebook (.ipynb file format). It can be run locally using software such as Jupyter Labs or VSCode, or in the cloud using a service such as Google Colab.

### Code Usage

It is recommended to not run the entire file, as that will result in downloading the images to your computer and populating the dataframes from scratch. If desired, both the images and the dataframes can be downloaded from the github. If you want to explore the image analysis techniques used, all of the helper functions are in the file and custom images can be uploaded.

## DATA

### Data Dictionaries

#### final_df.csv
| Variable | Description |
| -------- | ----------- |
| Username | Username of the Instagram account that the post is from |
| Caption | Caption that the account had with the post |
| Date Posted | The date and time that the account posted the picture |
| Number of Likes | Number of likes that the post received |

#### MostPopularAccounts.csv
| Variable | Description |
| -------- | ----------- |
| Rank | Rank of the Instagram Account Based on Number of Followers |
| Username | Username of the Instagram account |
| Owner | Name of the Person Who Owns the Account |
| Brand Account | Unused Column with No Data |
| Followers (millions) | Amount of Followers in Millions |
| Profession/Activity | What the Owner of the Account is Known For |
| Country/Continent | Where the Account is Based |

#### result_df.csv
| Variable | Description |
| -------- | ----------- |
|  | Row Number |
| Username | Username of the Instagram account |
| Average Number of Likes | Average Number of Likes on 10 Most Recent Posts |
| Average Number of Likes on Red-Dominant Posts | Average Number of Likes the Red-Dominant Pictures of the 10 Most Recent Posts Received |
| Average Number of Likes on Green-Dominant Posts | Average Number of Likes the Green-Dominant Pictures of the 10 Most Recent Posts Received |
| Average Number of Likes on Blue-Dominant Posts | Average Number of Likes the Blue-Dominant Pictures of the 10 Most Recent Posts Received |
| Red-Dominant Percentage | Ratio of Likes of Red-Dominant Pictures to Average Number of Likes of Account |
| Green-Dominant Percentage | Ratio of Likes of Green-Dominant Pictures to Average Number of Likes of Account |
| Blue-Dominant Percentage | Ratio of Likes of Blue-Dominant Pictures to Average Number of Likes of Account |

### Link to Data
[Our Data](https://github.com/jnm9aba/DS4002Project2/tree/main/DATA)

### Notes
All of the images that were analyzed are in a folder within DATA called IMAGES. Within this folder, there is a folder for each account that contains all of the images.

## FIGURES
| Figure | Takeaways |
| -------- | ----------- |
| Bargraph of Percentage Change in Likes for Green-Dominant Posts  | There aren't too many accounts with at least one green dominant post. For those that do, one has a very negative percentage change in likes for green posts and the rest have about the same percentage change--between 15 and 30%. |
| Bargraph of Percentage Change in Likes for Red-Dominant Posts | All of the accounts have at least one red-dominant post. A majority of these accounts have a positive percentage change, but there are still quite a few that are negative. The percentage changes aren't too strong for positive or negative. |
| Bargraph of Percentage Change in Likes for Blue-Dominant Posts | 90% of accounts had blue-dominant photos. A majority of the accounts had a negative percentage change for these posts, however, the magnitude of those that are positive cause there to be more positivity than negativity in percentage change for these accounts. |
| Bargraph of Average Likes for Most Followed Instagram Accounts | Even though these are the most popular accounts, there is still a wide variety in their popularity. There are extremely popular accounts like @zendaya that receive so many likes they could potentially skew our results. It would be wise to normalize our data somehow.  |

## REFERENCES

[1] B. C. Author, R. Katai, and N. Schaffer, “5 things the most liked Instagram photos include,” Social Media & Influencer Marketing Speaker, Consultant & Author, 02-Oct-2022. [Online]. Available: https://nealschaffer.com/most-liked-instagram-photos/. [Accessed: 05-Oct-2022]. 

[2] S. Ajani, “6 ways to get more Instagram likes - it's easier than you think,” Keyhole, 23-Jan-2020. [Online]. Available: https://keyhole.co/blog/get-more-instagram-likes/#:~:text=DOMINANT%20COLORS%20ARE%20IMPORTANT&amp;text=Research%20has%20shown%20that%20predominantly,or%20in%20blue%2Dhued%20lighting. [Accessed: 05-Oct-2022].

[3] “List of most-followed Instagram accounts,” Wikipedia, 11-Oct-2022. [Online]. Available: https://en.wikipedia.org/wiki/List_of_most-followed_Instagram_accounts. [Accessed: 12-Oct-2022]. 

[4] R. Madsen, “Color models and color spaces,” Color models and color spaces - Programming Design Systems. [Online]. Available: https://programmingdesignsystems.com/color/color-models-and-color-spaces/index.html#:~:text=HSV%20is%20a%20cylindrical%20color,on%20the%20RGB%20color%20circle. [Accessed: 19-Oct-2022]. 

### Acknowledgements
We would like to acknowledge Professor Alonsi and Harsh for helping us throughout our project.

### MI1 Assignment
[Milestone 1](https://docs.google.com/document/d/15haxigBHvCb8rI7tktmQFV64L9-oW4imXrP1yVX8IdY/edit?usp=sharing)

### MI2 Assignment
[Milestone 2](https://docs.google.com/document/d/1yAlrMrNyQZG4u_CxR5IqKfujadzdsb7uWFDpjmyYKuo/edit?usp=sharing)


