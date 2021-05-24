# Live_covid_tracker



                                          ****************************INDRODUCTION******************
This project aims to build a website which provides the accurate and live information about the covid -19 cases all over the world ; we can select any country and see the latest updates of the total cases , recovered cases and the total deaths due to coronavirus from the time it starts till now. It provides us accurate and exact figures , we can see cases and the condition worldwide.

                                      ***************************TECHNOLOGY USED*************************
                                      
                                      
                                      
1. HTML : Hyper Text Markup Language(HTML) is the standard markup language for creating web pages.
HTML stands for Hyper Text Markup Language.
* HTML is the standard markup language for creating Web pages.
* HTML describes the structure of a Web page.
* HTML consists of a series of elements.
* HTML elements tell the browser how to display the content.
* HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.



2. CSS : CSS is a language we use to style a web page.
* CSS stands for Cascading Style Sheets.
* CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
* CSS saves a lot of work. It can control the layout of multiple web pages all at once.
* External stylesheets are stored in CSS files.



3. JAVASCRIPT: JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which are HTML and CSS .

4. VS CODE : Visual Studio Code is a streamlined code editor with support for development operations like debugging, task running, and version control. It aims to provide just the tools a developer needs for a quick code-build-debug cycle and leaves more complex workflows to fuller featured IDEs, such as Visual Studio IDE. It is a freeware source-code editor made by Microsoft for Windows, Linux and macOS.

5. AWS CLOUD : Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis. These cloud computing web services provide a variety of basic abstract technical infrastructure and distributed computing building blocks and tools. One of these services is Amazon Elastic Compute Cloud (EC2), which allows users to have at their disposal a virtual cluster of computers, available all the time, through the Internet.

                                     ************************API’S USED********************************* 
                                     
                                     
                                     
1. ./Gilroy-Regular.woff’-> we used this API to use Gilroy family fonts in our website. Gilroy Free Font Family is a modern sans serif with a geometric touch. An older brother of the original Qanelas font family. It comes in 20 weights, 10 uprights and its matching italics. The Light & Extra Bold weights are free of charge, so you can use them to your heart’s content.


2. www.geoplugin.com/geolocation-> we used this link in geoplugin function () file to get the location for the API’s used in the making of the code.geoPlugin provides a free geolocation API in multiple different programming languages in a single API call. ... IP Geolocation can be performed on both IPv4 and IPv6 addresses using the same API request format. geoPlugin detects whether the IP is IPv4 or IPv6 automatically so you don't have to.



3.https://api.covid19api.com/total/country/ -> we use this link to get the API for the countries latest covid -19 data of recovered cases, active cases and total deaths .



                                      *******************OVERVIEW      OF    PROJECT*********************
                                      
                                      
As we can see the current situation of the world , the whole world is suffering from the deadly virus disease which becomes the pandemic known as CORONAVIRUS (COVID-19), since late 2019 .At this point of time there are conditions that some countries have completely recovered from the virus while some are recovering and in some countries like our INDIA we are suffering from the second wave of the virus and at the same time preparing ourself for the third wave too.��So, in order to get the global news and the latest trends and updates on the pandemic like which country is In which condition and what are the situations of the disease in which country what is the recovery rate, how many people are active there ,how many new cases comes in a day and how many people died;

In short ,to get all the information of the pandemic worldwide I have made a website which tells us the same ,it gives the data of all over the world . I also hoisted it with the help of AWS S3 cloud services and you can also search for it on google and can access the information from there also with this link https://covid-live-tracker.s3.ap-south-1.amazonaws.com/coronavirus_live_tracker/index.html In making of this project I use three languages i.e.., HTML ,CSS and JavaScript. The whole project is divided into four files or parts;

First ,(index.html ) In which I use HTML language ,HTML is used to write the basic format and the body of the page used different links to link the images on the page etc etc….

Second one is the CSS file (style.css) ,In which CSS language is used which is used to style the page to give colours and paddings and fonts and all the styling to the page is given by this part.

Third one is the JavaScript file (countries.js) ,In which I use JavaScript and is used to get the country codes of all the 195 countries of the world. Then ,I made search country element which is used to search the specific countries then , make country list function which is used to fetch the data of the particular country . then I made a function change_country_btn which is used to update the button of the country list.

Fourth one is also the JavaScript file(app.js),In which also JavaScript is used but this file is used to fetch and update the COVID-19 API’s with the help of several different API links.

And finally the last one is the JavaScript file (function geoplugin.js) which is used to get the location details of the user which we get from www.geoplugin.com/geolocation link.

At last I hoist my website on the online platforms with the help of AWS S3 cloud services.
