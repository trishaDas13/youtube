# youtube
Hosting link: https://trishadas13.github.io/youtube/
![image](https://github.com/trishaDas13/youtube/assets/126088849/4b089188-74c0-4eda-a97d-d1403a7909a3)
![image](https://github.com/trishaDas13/youtube/assets/126088849/44c2fe28-c98c-47f1-8c6c-a754d2590ff8)
![image](https://github.com/trishaDas13/youtube/assets/126088849/3517d966-fa32-47f2-8158-d14dea9c795a)


html code:-

![image](https://github.com/trishaDas13/youtube/assets/126088849/44f6a337-7ce8-422e-ba86-a7d3df3fe98b)
![image](https://github.com/trishaDas13/youtube/assets/126088849/c2c07a52-64cf-43df-8da6-6796b4edbaf9)
![image](https://github.com/trishaDas13/youtube/assets/126088849/683c2d0b-4d38-43af-bd1b-b5582526adac)
![image](https://github.com/trishaDas13/youtube/assets/126088849/35e93c08-da1f-4c5e-bfe3-e840e97c1529)
![image](https://github.com/trishaDas13/youtube/assets/126088849/99c3b050-e531-4e38-97f3-0bf0bdd2c2fe)
![image](https://github.com/trishaDas13/youtube/assets/126088849/a001833a-ed4f-41bf-9fb8-a5c9d492ce9e)
![image](https://github.com/trishaDas13/youtube/assets/126088849/621ce664-8eae-4460-8955-e990b62e382b)

The HTML document begins with a Document Type Declaration specifying that the document follows the HTML5 standard. The <html> element serves as the root of the document, indicating that the content is in English. The <head> section contains metadata and resource links. It sets the character encoding to UTF-8 using a <meta> tag and configures the viewport for responsive design using another <meta> tag. The title of the webpage, "Youtube," is defined using the <title> tag. External styles are linked through a <link> element, connecting to the "styles.css" file. Additionally, the Google Fonts Material Icons stylesheet is linked using another <link> tag.

The <body> section contains the visible content of the webpage. The header, represented by a <div> with the class "header," features navigation and search functionalities. The left side of the header contains a menu icon and the YouTube logo, while the search section includes a form with an input field for search queries and a search button with a Material Icons search icon. The header also contains icons for various functions such as search, video camera, apps, notifications, and user account.

Within the main content area, there is a sidebar on the left, indicated by a <div> with the class "sidebar." This sidebar contains categorized sections, each with a distinct icon and label. Categories include "Home," "Trending," and "Subscriptions," along with separators in the form of horizontal lines. Another set of categories includes "Library," "History," "Your Videos," "Watch Later," and "Liked Videos."

The videos section, enclosed within a <div> with the class "videos," displays recommended videos. Each video is presented in a container with a thumbnail image on the left and details on the right. These details consist of the author's image, the video's title, the author's name, and the view count. Each title also includes a hyperlink to the video or author's page. The view count is displayed with an indication of when the video was uploaded.

Overall, the provided HTML structure defines a webpage that replicates a YouTube interface. It features a header with navigation and search options, a categorized sidebar for easy content exploration, and a section to display recommended videos with their respective details. This layout mirrors the familiar design and functionality of the YouTube platform.

CSS code:- 

![image](https://github.com/trishaDas13/youtube/assets/126088849/97909030-9763-4f8d-826e-54b9f6484741)
![image](https://github.com/trishaDas13/youtube/assets/126088849/2c43a310-8010-4063-bfdd-7fbcd7feb3ad)

* selector is used to reset margins, paddings, and set the box-sizing property to border-box for all elements in the document.

body selector sets the font family to 'Roboto' and 'sans-serif' as a fallback.

.header class styles the header section. It uses flexbox to display its contents horizontally with space between and aligns items to the center. The height and padding create a 70px tall header.

.leftside styles the left side of the header. It uses flexbox to align its items vertically at the center. The img element has a width of 50px and a margin of 10px on the left.

.leftside i styles the icons in the header with some padding and a cursor pointer.

.search class styles the search form. It sets a border, height, and display as flex for the form element.

.search input styles the search input field with a width of 500px, padding, and border. The border radius is set to 0 to remove any rounded corners.

.search button styles the search button with padding, margin, height, and border. The width is commented out.

.main class styles the main content section. It uses flexbox to display its contents horizontally. The overflow: hidden ensures that content exceeding the container's dimensions is hidden.

.sidebar class styles the sidebar section. It has a fixed width of 230px, a white background color, and vertical scrolling for overflowing content.

.sidebar_categories and .sidebar_category style the sidebar's category list. The categories are displayed in a column with padding and margin applied for spacing.

.sidebar_category:hover styles the appearance of a category when hovered, changing the background color and cursor to indicate interactivity.

.videos class styles the videos section with a light background color, padding, and a top border.

.videos_container styles the container for videos, using flexbox to arrange them in a row with space around and enabling wrapping.

.video class styles an individual video element with a fixed width and a margin at the bottom.

.video_thumbnail and .video_thumbnail img style the thumbnail images of the videos. They use object-fit to cover the container while maintaining the aspect ratio.

.author img styles the author's profile image, applying a border radius and setting dimensions.

.video_details styles the video details section, arranging its content horizontally and providing a margin-top.

.title styles the video title and details, arranging them vertically.

title h3 styles the video title with color, line height, font size, and margin.

.title a, span styles links and spans within the title section, setting text decoration, color, and font size.

h1 selector styles h1 headings, setting font size, margin, and color.
