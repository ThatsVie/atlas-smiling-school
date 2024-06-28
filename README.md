# Pug Smile School
Implement a Design With Bootstrap

## Header/Hero Section

The header/hero section includes the following elements:
- **Logo Section**: Displays the Smileschool logo along with a smiley face icon.
- **Navigation Bar**: Contains links to different sections of the site, including "Courses," "Pricing," and "Love."
- **Hero Content**: Features a prominent heading "Get Puggy" and emphasizes words like "STUMPY," "BARK," and "LOYAL" to describe the playful nature of pugs. A call-to-action button "REGISTER FOR FREE" is also included.
- **Pro Pugs Section**: Showcases notable pugs with their achievements and titles.

## Carousel of Quotes

The carousel of quotes section highlights testimonials from various pugs. This section uses the Bootstrap Carousel component to display rotating quotes, accompanied by images of the pugs who provided the testimonials. Each slide includes:

- **Pug Image**: A rounded-circle image of the pug providing the testimonial.
- **Quote**: A blockquote with the pug's testimonial.
- **Author Information**: The name and playful occupation of the pug.

## Popular Videos

The "Most Popular Tutorials" section showcases popular video tutorials using the Bootstrap Carousel component. This section adjusts the number of video cards displayed based on the screen size: 4 cards for desktop, 2 cards for tablets, and 1 card for mobile devices. Each video card includes:

- **Video Thumbnail**: An image representing the video.
- **Video Title**: A bold title for the video.
- **Video Description**: A short description of the video's content.
- **Instructor Information**: An image and name of the pug instructor.
- **Star Rating**: A visual representation of the video's rating.
- **Duration**: The length of the video in minutes.

### Implementation Details

- **Carousel**: The videos are displayed in a carousel format, allowing users to scroll through the most popular tutorials.
  - **Carousel ID**: The `id` for this carousel is `popularVideoCarousel` to ensure it operates independently of other carousels on the page.
  - **Cards**: Each video is represented by a card containing an image, title, description, and additional details like the instructor's name and video duration.
- **Controls**: Carousel controls are included to enable users to navigate between the videos.

## Free Membership Section

The free membership section invites users to join the community and learn more about pugs. It includes:
- **Section Heading**: A prominent heading that highlights the "Free Membership" offer.
- **Membership Benefits**: Four columns, each featuring an icon and a benefit of the membership, such as "Happy Pugs," "Pug Tricks," "Pug Health," and "Pug Stories."
- **Call-to-Action Button**: A "REGISTER FOR FREE" button to encourage users to sign up.

## Latest Videos

The "Latest Videos" section showcases the newest video tutorials featuring pugs. This section is designed to provide users with the most recent content available on the platform.

### Implementation Details

- **Structure**: The section is structured similarly to the "Most Popular Tutorials" section, ensuring consistency across the website.
- **Heading**: The heading for this section is "Latest videos", with "Latest" highlighted to draw attention.
- **Carousel**: The videos are displayed in a carousel format, allowing users to scroll through the latest tutorials.
  - **Carousel ID**: The `id` for this carousel is `latestVideosCarousel` to ensure it operates independently of other carousels on the page.
  - **Cards**: Each video is represented by a card containing an image, title, description, and additional details like the instructor's name and video duration.
- **Controls**: Carousel controls are included to enable users to navigate between the videos.

