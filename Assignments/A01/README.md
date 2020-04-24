# DH150 Assignment 1: Heuristic Evaluation by Lillian Nguyen

## San José Resources  
>Being back in San Jose during the COVID-19 quarantine, I’ve decided to focus on my hometown for this project, specifically the unexplored resources that the city provides. I’ve lived in San Jose my entire life until I moved away to attend UCLA, where I realized the vast resources that the school provides. I wanted to explore whether my city offers anything cool and interesting for the public, so I browsed the internet and found two resources: an online archives catalog that conserves the city’s historic collections and an app to report any issues in the San Jose area. By improving the UX design, the site and app would become more user-friendly and accessible, creating a more well-informed and safe community. 

## Severity Scale for Usability Problems
The following 1 to 3 rating scale can be used to rate the severity of usability problems:
Rating  | Importance  |
:---: | :---  |
1  | Cosmetic problem only: need not be fixed unless extra time is available on project  |
2  | Minor usability problem: fixing this should be given low priority  |
3  | Major usability problem: important to fix, so should be given high priority  |

Credit: NNgroup - https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/
 
## Heuristic Evaluation of Website - History San José Online Catalog
https://historysanjose.pastperfectonline.com/

History San José, a non-profit organization under the City of San José, aims to preserve and enrich the cultural heritage of San Jose and surrounding area through research and collections, to name a few. This growing online catalog holds over 30,000 records of photographic collections, images of material culture, archives, and libraries. The homepage has 3 main components: the navigation bar, the body with information on the catalog, search methods, and image orders, and the footer with contact information. The navigation bar has 8 items: “Home,” “Keyword Search,” “Advanced Search,” “Random Images,” “Archives,” “Photos,” “Libraries,” and “Objects.”

![History San Jose homepage](HSJ-screenshot.png) 


### Initial Evaluation 
The search tools and information architecture are particularly concerning and hinder a user’s efficiency. The keyword and advanced search tools have their own pages and specific functions, making the search task more complicated. I was also very confused on what the menu items entail due to the terminology (e.g. random images versus photos, archives versus libraries) and what types of records fit within each category. There is also no organization or hierarchy of content within each of the other links when a user first lands on the page since it is just a layout of random records; they are not subcategorized either. 


### #1: Visibility of System Status
Rating  | Evaluation  |
:---: | :---  |
1  | When a user is on a specific tab or page, the menu item block in the navigation block does not change color at all. Therefore, a user would not know which page they are on and/or what type of record is being shown (e.g. “Photos” or “Objects”).  |
1  | When the cursor hovers over a record photo or label, the outline of the photo frame or the font color of the label changes to the color red. However, it could be hard to distinguish for people with poor color vision because of the slight color change.  |
1  | The outline of the text search box with a magnifying glass on the right end changes from gray to blue, indicating the function is ready to be used.  |
1  | A user must click on the bright red search button next to the search button. The search button slightly changes from bright red to a darker shade of red when a cursor is hovered over it, which is barely noticeable and could be changed to make the change more obvious.  | 
1  | There is no progress indicator when searching for items so a user has no indication on whether their search is being executed or not. It would be nice to have some kind of notification of a search completion, although it is not significant.  |


### #2: Match between system and the real world
Rating  | Evaluation  |
:---: | :---  |
2  | The terminology used to filter out searches in the “Advanced Search” page may not be easily known; some users may question the function of some of the filters, such as “lexicon category” and “lexicon sub-category.”  |
3  | The terminology used for the categories “Archives” and “Libraries” can be undistinguishable to some people who are unfamiliar with how the system works. An option may be to categorize both into “Collections” and clearly organize the archives records from the libraries records.  |
3  | Each record is labeled with their catalog and accession numbers, instead of its corresponding title and description. A user would not understand the context behind the item based on that information and would have to click on the photo to see the full description.  |

![HSJ-Advanced Search](HSJ-advanced.png) 


### #3: User control and freedom
Rating  | Evaluation  |
:---: | :---  |
1  | There is an option to “Return to Search Results” with no change to the search boxes/filters. However, the words are very small and can easily be overlooked. The red font does not help to make it stand out.  


### #4: Consistency and standards

![HSJ-Keyword Search](HSJ-keyword.png) 

Rating  | Evaluation  |
:---: | :---  |
1  | The magnifying glass icon in the search bar is not clickable, which this icon usually is in other cases. A user can be confused and assume the icon is a button for initiating a search.  |
2  | The advanced search page does not have an option to show only records with images. The keyword search page does have one.
3  | The menu item “Random Images” may be confusing. At first, I wondered whether it meant a curated or computer-generated random selection of record items or a space for record items that do not go under the other pages. It has no search bar either. The purpose of the page is to showcase a “rotating selection of images using the Random Images feature.”  |
3  | The search options are not consistent with usual types of search engines. The keyword search and advanced search are mutually exclusive and are their own search engines by themselves. There is no option to filter out a keyword based on the filters from the advanced search. The types of filters in the advanced search are almost unusable to the general public, only the creators, since most people would probably not know the title, catalog number, lexicon category, etc.  |
3  | Much of the information architecture seems to be organized through the lens of the creators and how they themselves would structure information. For example, the advanced search works better for the familiarized research worker rather than a typical user who wants to find an item based on a keyword and filtered by date. The menu items in the navigation bar also have no hierarchy or sub-hierarchies.  |
3  | The large “History San Jose” heading does not link to the homepage of the online catalog; it is linked to the main website of History San Jose. The “Home” is the first menu item in the navigation bar but is easily overlooked by all the other tabs.  |


### #5: Error prevention
Rating  | Evaluation  |
:---: | :---  |
1  | A typo indicator would be useful, even though I understand searches can be anything at all or a name spelling could be unique.  |
2  | The search engines could offer a suggestions dropdown. I understand that searches can be anything at all, but if a system can detect words/phrases being typed, then it could be very useful in preventing misspellings.  |
2  | The advanced search filters do not offer a note for some of the formats. For example, the catalog number requires the hyphens, and the date is formatted as year/month/day or ####/##/####.  |


### #6: Recognition rather than recall
Rating  | Evaluation  |
:---: | :---  |
2  | The search engines could offer suggestions in a search engine dropdown to transition a user from recalling to recognizing a word or phrase.  |
2  | The results page can offer a list of related words/phrases or similar suggestions to the typed searches, thereby helping a user recognize/inspire a new search. For example, if a user searches for “bike,” the results page can suggest “bicycle.”  |
3  | Overall design and terminology of the website makes it hard for a user to recall the workings of the system. For example, a user having to remember how to use the advanced search or which filters were used because there is no color change.  |
3  | The website can include a bar or list of records that a user clicked on or change the record color to indicate that it has already been viewed. The results page only shows a photo (if any), numerical label and/or collection, and record type. Most, if not all, are not unique enough or easy to remember when browsing.  |

![HSJ-Record Listing Example](HSJ-record.png) 


### #7: Flexibility and Efficiency of Use
Rating  | Evaluation  |
:---: | :---  |
3  | The keyword search page includes a long paragraph on how to use Boolean search in a complicated and overwhelming way. The search engine can be designed in a way that allows a user to do Boolean search without typing out the specific Boolean operators.  |
3  | The advanced search filters can be redesigned and reorganized into a better search system that both experts and novices can use. The current engine is more navigable to experts and slows down a typical user.  |
3  | A user has to click on the record photo, not the corresponding label, in the results page to view the entire record information. There is no quick view to see a closer look at the image either.   |


### #8: Aesthetic and minimalist design
Rating  | Evaluation  |
:---: | :---  |
2  | There are too many menu items (total of 8) in the navigation bar. The search engines can be combined to one tab. “Random Images” can be deleted if it serves no purpose.  |
3  | There is no sense of hierarchy. A user should be able to search for an item immediately once arriving at the homepage, rather than decide whether to do a keyword or advanced search. The search engine can be added to the visible portion of the homepage without scrolling.
3  | The extra information on the homepage can go into an “About” or “Help” page. All the information is overwhelming and can be better organized for quick reading.  |
3  | Overall aesthetic looks historic and not engaging. The use of colors is misleading - the abundance of red font and colors when there is no need to draw attention in an alarming way.  |
3  | The layout of the photos on the “Random Images” page is messy due to the various sized photos, causing misalignment of the labels.  |

![HSJ-Random Images](HSJ-randomimages.png) 


### #9: Helps users recognize, diagnose, and recover from errors
Rating  | Evaluation  |
:---: | :---  |
3  | In the “Image Orders” portion of the homepage, the link to the Library and Research Fees page cannot be found.  |
3  |  There are no notifications for the advanced search filters. A user would not know whether their search or the formatting is incorrect.  |


### #10: Help and documentation
Rating  | Evaluation  |
:---: | :---  |
3  | The “How to Search” portion of the homepage is the only source of help in the website. It gives some information on some advanced searches and Boolean functions. There is no description or example for all of the filters.  |
3  | The keyword search page includes a note on how to do Boolean searches. It may be good to refresh people on how to use the search but a novice may be confused because of the way it is explained.  |



## Heuristic Evaluation of App - San José 311
https://www.sanjoseca.gov/your-government/departments-offices/customer-service/san-jose-311


San Jose 311 is a mobile app that allows users to report issues and track your or other people’s City service requests. Requests include abandoned vehicles, graffiti, illegal dumping, pothole, and streetlight outage. There is an option to include photos and map the specific location. The app links to several City of San Jose resource websites for finding more information on neighborhood service providers, FAQs, or paying bills.

![SJ311-homepage](SJ311-homepage.png) 


### Initial Evaluation 
The structure of the app is very poor. The login system does not remember account information so a user must login every time they stay off of the app for a long period of time. Navigating from one feature to another is not easy and smooth. Lack of hierarchy makes the app feel cluttered and unorganized with no main purpose/priority for the app.


### #1: Visibility of System Status
Rating  | Evaluation  |
:---: | :---  |
1  | A throbber and ‘darkened’ screen indicate that the app is working to perform the action. Although it performs the action, it can be too distracting and does not transition as smoothly as it can be since there are 2 changes: a throbber appearing in the middle of the screen and the screen being shaded by a gray screen.  |
2  | In the “Other Reports” page, there is no status update or a page for completed  to see whether reports have been completed, open, or still in progress. It is hard to know what other statuses there are besides those three. A user can track a report using the “Follow” button, yet it is still difficult to know the status of each case because there is no indication on the item record. There is only an obvious status indication on reports a user has submitted. For example, a green “OPEN” oval indicated the status is open.  |

![SJ311-loading](SJ311-loading.png) 


### #2: Match between system and the real world
Rating  | Evaluation  |
:---: | :---  |
1  | The icons can be changed to match other common icons that are more well-known and understood. The hamburger icon on the top left, at first, indicates that it could be a graph or some kind of visual, but it is just a hamburger icon that leads to the main menu.  |
1  | The add icon is good for adding a report, however it can be made more obvious and aesthetic with color or a circle frame.  |
1  | The filter icon does not look like common filter icons today. I could not tell what it was until I tapped on it.  |
1  | When using the toggle function during the making of a report, those functions do not have a clear confirmation (e.g. yes or no when toggling from one side to the other). The color change from navy blue (meaning yes) to gray (meaning no) is the only determinant for whether the toggle is placed at either side. Similarly, the check mark function also only changes from navy blue to gray. Both these colors are not consistent with the assumption of yes. 

![SJ311-toggle](SJ311-toggle.jpg) 


### #3: User control and freedom
Rating  | Evaluation  |
:---: | :---  |
2  | When creating a new report, a user can tap the “<” icon to go back to the previous page. The icon is not clearly assumed as an exit function but is more of a function to go back to the previous page.  |
2  | There is no frozen navigation bar to quickly go to other pages on the app. A user must press the “<” icon to go back to the homepage or access the hamburger option.  |
2  | There is no option to delete, edit, or cancel a report a user has submitted.  |


### #4: Consistency and standards

![SJ311-unconsistency](SJ311-unconsistency.jpg) 


Rating  | Evaluation  |
:---: | :---  |
1  | Some of the text can be rewritten to be structurally or grammatically correct. For example, a modal page says “to logout,” which should be “to log out.”  |
1  | The pages to make a report are not consistent with each other. For example, the first line for each question in the report should be the question itself, followed by examples on the second line. Some of these have both the question and example on the first line.  |
1  | The 2 options on the homepage, “New Report” and “Other Reports,” are confusing because “New Report” could mean recent reports and “Other Reports” can fall into any category. These can be changed to action phrases, like “Make a New Report” and “Activity” or “Reports Feed,” respectively.  |
1  | In the filter option, “Services” is used to organize by issue type (e.g. illegal dumping, pothole) and is not the best term to use to describe the type of issue.  |
1  | These toggle and check mark functions should also be consistent with each other rather than have 2 different visual on the same page that serve the same purpose.
1  | When making a report, the heading of that report page says “Your [insert issue] Report” or “My Report” for reporting on other issues that are not the main 5 issues (abandoned vehicle, graffiti, illegal dumping, pothole, and streetlight outage). Those headings imply that the page is for viewing reports that have already been processed. They can be changed to “Report an Issue.”  |
2  | The app interface has no footer/navigation bar and only displays 6 boxes for a user to choose from (3 of those boxes will take a user to their phone internet browser and not to another page in the app).  |
2  | The app interface has no footer/navigation bar and only displays 6 boxes for a user to choose from (3 of those boxes will take a user to their phone internet browser and not to another page in the app).  |

![SJ311-terminology](SJ311-terminology.jpg) 


### #5: Error prevention
Rating  | Evaluation  |
:---: | :---  |
1  | When a user taps on the “<” icon to go back to the previous page, exit, or cancel their report, their inputs will be completely gone and there is no notification confirming whether the user would like to discard the draft. The “<” is not clearly marked as an exit button.  |
1  | There is an option to log out. A modal box will ask a user to confirm if they want to log out. The app automatically logs the user out when they haven’t been on it for a period of time, which can get annoying when a user wants to quickly make a new report, view their submitted reports, or stay logged in.  |
1  | The option to filter other reports by date is available, but it takes an extra step or a modal box to alert a user if the end date is set before the start date, resulting in decreased efficiency. 


### #6: Recognition rather than recall
Rating  | Evaluation  |
:---: | :---  |
1  | A map feature for plotting the location of the issue is a nice feature that allows a user to easily recognize and pinpoint their estimated or exact street location instead of recalling the street address of where they were at. It can possibly include a street or satellite view option to make the location even more precise because of the real images.  |


### #7: Flexibility and efficiency of use
Rating  | Evaluation  |
:---: | :---  |
1  | A user can log in as a guest to make a report for all issues, except reporting abandoned vehicles requires an account and they cannot view their submitted reports made as a guest. After submitting a report as a guest, the app takes the user to view “My Reports” with a feed of records from the “Other Reports” page. This is misleading and confusing; the guest user would not be able to go to that “My Reports” page after exiting.  |
2  | The filter option for searching through reports is sorted by “Services,” “Date Range,” and “Near Me.” It cannot be filtered by “other issues” or specific locations that are not near the user.  |


### #8: Aesthetic and minimalist design
Rating  | Evaluation  |
:---: | :---  |
2  | The other 3 items are “FAQs,” “Neighborhood Services,” and “Pay Bills,” which all take the user to a linked page in the internet browser. These are extra mass information and could be tucked away somewhere accessible.  |
3  | There is no hierarchy on the homepage. The more important items are “News Report” to make a new report, “My Reports” to check the status of their own reports or other users’ reports that they follow, and “Other Reports” to browse through public reports. These commonly used items do not have a frozen navigation bar nor are they in the hamburger menu items.  |


### #9: Helps users recognize, diagnose, and recover from errors
Rating  | Evaluation  |
:---: | :---  |
1  | When logging in with incorrect credentials, the notification does not specify whether the username/email address or password is incorrect.  |
1  | When submitting a report without filling out the fields with asterisks, the modal box only chooses one of those asterisks to notify a user and not specify/list each of them.  |


### #10: Help and documentation
Rating  | Evaluation  |
:---: | :---  |
2  | There is no help and documentation page on the app itself, but the “FAQs” item links to a page that will go to the internet browser. It would be helpful, especially to novice users, to have a Help page on the app itself for technical issues, explanations, navigation, etc.  |
