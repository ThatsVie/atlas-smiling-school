# Pug Smile School

This project included three web pages implemented with Bootstrap. HTML/CSS/Accessibility/Responsive design/Bootstrap knowledge was applied. There was minimal instruction, and the implementation was left to individual creativity - the objective was simple: to have fully functional web pages that looked the same as the designer file. The pages were designed to showcase various pug-related content in an engaging and accessible manner. These pages were based on the following Figma design files, with creative freedom taken to incorporate pug-themed elements:

- [Homepage Figma File](https://www.figma.com/design/hcxMqRWjdj06jHycRkbzOf/Homepage?node-id=0-1&t=Mq8XBvlJZG2WxGZi-0)
- [Pricing Page Figma File](https://www.figma.com/design/QQmdkH49hKJuJ6244fBXzH/Pricing?node-id=0-1&t=ATtwuwpEqWUtGF9B-0)
- [Courses Page Figma File](https://www.figma.com/design/zKRy0vMRBjwHaKBn1WnavS/Courses?node-id=0-1&t=n0UjYPupBYiuFTX3-0)


This additional page, `love.html` provided a creative outlet to apply what was learned, resulting in additional practice and an enjoyable project.

**You can view the deployed project here: [Pug Smile School](https://thatsvie.github.io/atlas-smiling-school/)**
## Homepage `index.html`

### Header Section

The header section includes the following elements:
- **Logo Section**: Displays the Smileschool logo along with a smiley face icon. The logo section is wrapped in an anchor tag, allowing users to navigate back to the homepage by clicking on the logo.
- **Navigation Bar**: Contains links to different sections of the site, including "Courses," "Pricing," and "Love."


### Hero Section

The hero section includes:
- **Hero Content**: Features a prominent heading "Get Puggy" and emphasizes words like "STUMPY," "BARK," and "LOYAL" to describe the playful nature of pugs. A call-to-action button "REGISTER FOR FREE" is also included.
- **Pro Pugs Section**: Showcases notable pugs with their achievements and titles.

### Carousel of Quotes

The carousel of quotes section highlights testimonials from various pugs. This section uses the Bootstrap Carousel component to display rotating quotes, accompanied by images of the pugs who provided the testimonials. Each slide includes:

- **Pug Image**: A rounded-circle image of the pug providing the testimonial.
- **Quote**: A blockquote with the pug's testimonial.
- **Author Information**: The name and playful occupation of the pug.

### Popular Videos

The "Most Popular Tutorials" section showcases popular video tutorials using the Bootstrap Carousel component. This section adjusts the number of video cards displayed based on the screen size: 4 cards for desktop, 2 cards for tablets, and 1 card for mobile devices. Each video card includes:

- **Video Thumbnail**: An image representing the video.
- **Video Title**: A bold title for the video.
- **Video Description**: A short description of the video's content.
- **Instructor Information**: An image and name of the pug instructor.
- **Star Rating**: A visual representation of the video's rating.
- **Duration**: The length of the video in minutes.

#### Implementation Details

- **Carousel**: The videos are displayed in a carousel format, allowing users to scroll through the most popular tutorials.
  - **Carousel ID**: The `id` for this carousel is `popularVideoCarousel` to ensure it operates independently of other carousels on the page.
  - **Cards**: Each video is represented by a card containing an image, title, description, and additional details like the instructor's name and video duration.
- **Controls**: Carousel controls are included to enable users to navigate between the videos.

### Free Membership Section

The free membership section invites users to join the community and learn more about pugs. It includes:
- **Section Heading**: A prominent heading that highlights the "Free Membership" offer.
- **Membership Benefits**: Four columns, each featuring an icon and a benefit of the membership, such as "Happy Pugs," "Pug Tricks," "Pug Health," and "Pug Stories."
- **Call-to-Action Button**: A "REGISTER FOR FREE" button to encourage users to sign up.

### Latest Videos

The "Latest Videos" section showcases the newest video tutorials featuring pugs. This section is designed to provide users with the most recent content available on the platform. It is exactly the same as the "Most Popular Tutorials" section.


### Footer Section

The footer of the Pug Smile School website includes:

- **Background**: The footer has a `bg-cyprus` background color with white text.
- **Logo and Smiley Icon**: Displayed on the left side, or centered on smaller screens.
- **Social Media Links**: Icons for Facebook, Twitter, and Instagram on the right side, or centered on smaller screens.
- **Copyright Text**: Centered at the bottom with reduced opacity for subtlety.

## Pricing Page `pricing.html`

### Header

The header of the pricing page includes:
- **Logo Section**: Displays the Smileschool logo along with a smiley face icon, aligned to match the header on the homepage. The logo section is wrapped in an anchor tag, allowing users to navigate back to the homepage by clicking on the logo.
- **Navigation Bar**: Contains links to "Courses," "Pricing," and "Love."

### Hero Section

The hero section of the pricing page includes:
- **Heading**: A heading "What is Smileschool?" with the logo and smiley icon.
- **Subheading**: A bold subheading "Go pug!"

### Pricing Grid

The pricing grid showcases different membership options and benefits. It includes:
- **Buttons**: Two buttons for "BUY 3 MONTHS" and "BUY 1 YEAR," both sized at 162px by 44px.
- **Price Information**: Displays the price and monthly rate for each option.
- **Benefits**: Lists benefits such as "Unlimited access to all tutorials," "Access SmileSchool private forum," "Access Smiles contests & Smiles Analysis," and "Get a free toothbrush." Each benefit is accompanied by a green check icon.

### Carousel of Quotes

The carousel of quotes section highlights testimonials from various pugs, similar to the homepage. It includes:
- **Pug Image**: A rounded-circle image of the pug providing the testimonial.
- **Quote**: A blockquote with the pug's testimonial.
- **Author Information**: The name and playful occupation of the pug.

### FAQ Section

The FAQ section answers common questions about pugs and their care. Each FAQ includes:
- **Question**: A heading with the question.
- **Answer**: A paragraph with the answer, using pug-related placeholder text.

### Footer Section

The footer is consistent with the homepage, including:
- **Background**: The footer has a `bg-cyprus` background color with white text.
- **Logo and Smiley Icon**: Displayed on the left side, or centered on smaller screens.
- **Social Media Links**: Icons for Facebook, Twitter, and Instagram on the right side, or centered on smaller screens.
- **Copyright Text**: Centered at the bottom with reduced opacity for subtlety.

## Courses Page `courses.html`

### Header/Hero Section

The header/hero section of the Courses page includes:
- **Logo and Navigation:** Displays the Smileschool logo along with navigation links to the 'Courses,' 'Pricing,' and 'Love' pages. On smaller screens, a burger menu is used for navigation. The logo section is wrapped in an anchor tag, allowing users to navigate back to the homepage by clicking on the logo.
- **Inspirational Quote:** Features an inspirational quote "« Don't cry because it's over. Smile because it happened. »" displayed prominently in the center, using the 'Coiny' font for emphasis.

### Search Filters

The search filters section allows users to refine their video search based on keywords, topics, and sort options:
- **Keywords:** Users can enter keywords into a search bar to filter videos. An icon next to the search bar enhances the visual cue for searching.
- **Topic Dropdown:** A dropdown menu lets users select the level of expertise for the videos, with options for Novice, Intermediate, and Expert.
- **Sort By Dropdown:** Users can sort videos by Most Popular, Most Recent, or Most Viewed, using another dropdown menu.

### List of Results Section

The list of results section displays video cards, each containing a thumbnail, title, description, and rating:
- **Video Cards:** Each video card shows a thumbnail image with a centered play button overlay. Below the thumbnail, the video title and description are displayed. 
- **Ratings and Duration:** A row at the bottom of each card displays the video rating (using star icons) and the video duration.

### Footer Section

The footer is consistent with the homepage, including:
- **Background**: The footer has a `bg-cyprus` background color with white text.
- **Logo and Smiley Icon**: Displayed on the left side, or centered on smaller screens.
- **Social Media Links**: Icons for Facebook, Twitter, and Instagram on the right side, or centered on smaller screens.
- **Copyright Text**: Centered at the bottom with reduced opacity for subtlety.

## Love Page `love.html`

### Header Section

The header section of the Love page includes:
- **Logo Section**: Displays the Smileschool logo along with a smiley face icon. The logo section is wrapped in an anchor tag, allowing users to navigate back to the homepage by clicking on the logo.
- **Navigation Bar**: Contains links to "Courses," "Pricing," and "Love."

### Hero Section

The hero section includes:
- **Hero Content**: Features a prominent heading "A pug's love is like no other." and emphasizes the unique bond between pugs and their owners.

### Main Content

The main content section includes:
- **Adopt/Foster Buttons**: Provides options for users to adopt or foster a pug with links .
- **Titles**: Highlights themes of "Love" and "Care" with corresponding descriptions.
- **Features**: Lists features such as "24/7 Pug Helpline," "Access to Pug Lovers Forum," "Invitations to Pug Playdates," and "Receive Pug Care Packages," each with heart icons.
- **Pug Merchandise**: Details exclusive discounts on pug merchandise with a paw print logo.

### Carousel Section

The carousel section showcases images of pugs in various settings, using the Bootstrap Carousel component.

### Testimonials Section

The testimonials section includes quotes and images from pug owners, highlighting the joy and love their pugs have brought into their lives.

### Pug Facts

The Pug Facts section includes interesting facts about pugs, displayed in visually appealing fact boxes.

### Photo Gallery

The photo gallery showcases images of pugs in various activities and settings, presented in a grid format.

### Love Stories

The Love Stories section features stories of pug owners and their pugs, presented in a card format with images and descriptions.

### Pug Love Stories Form

This section invites users to share their own pug love stories through a submission form.

### Footer Section

The footer is consistent with other pages, including:
- **Background**: The footer has a `bg-black` background color with white text.
- **Logo and Smiley Icon**: Displayed on the left side, or centered on smaller screens.
- **Social Media Links**: Icons for Facebook, Twitter, and Instagram on the right side, or centered on smaller screens.
- **Copyright Text**: Centered at the bottom with reduced opacity for subtlety.

**This additional page allowed for further exploration of Bootstrap components and provided an enjoyable creative outlet to apply what was learned in a fun and engaging way. The Love page celebrates the unique bond between pugs and their owners, offering a variety of pug-related content and interactive elements.**


### Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling the webpage, including custom styles and Bootstrap integration.
- **Bootstrap 4.4.1**: For responsive design and components like the navbar and carousel.
- **Google Fonts**: To enhance the typography with fonts like Source Sans Pro and Coiny.



### Additionally

- The images used in the project are stored in the `images` and `puggies` directories.
- Custom styles are defined in the `styles.css` file and are imported into the `homepage.html` file.