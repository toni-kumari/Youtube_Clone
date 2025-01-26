# YouTube Clone

This project is a simple clone of the YouTube website, built using HTML and CSS. It includes a header, sidebar, and a grid of video previews.

## Project Structure

- `Youtube.html`: The main HTML file that contains the structure of the website.
- `styles/`: Directory containing all CSS files for styling the website.
  - `general.css`: General styles applied to the entire website.
  - `header.css`: Styles specific to the header section.
  - `video.css`: Styles specific to the video grid and video previews.
  - `sidebar.css`: Styles specific to the sidebar.

## How to Run

1. Clone the repository to your local machine.
2. Open `Youtube.html` in your web browser.

## File Descriptions

### Youtube.html

This file contains the HTML structure of the website, including the header, sidebar, and video grid.

### styles/general.css

Contains general styles applied to the entire website, such as body and paragraph styles.

### styles/header.css

Contains styles specific to the header section, including the search bar, buttons, and icons.

### styles/video.css

Contains styles specific to the video grid and video previews, including thumbnails, video titles, and video stats.

### styles/sidebar.css

Contains styles specific to the sidebar, including sidebar links and icons.

## Fonts

The project uses the Roboto font, which is loaded from Google Fonts.

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;500;700&display=swap" rel="stylesheet">
```

## Media Queries

The project includes media queries to ensure the website is responsive and looks good on different screen sizes.

```css
@media (max-width: 750px) {
    .video-grid {
        grid-template-columns: 1fr 1fr 1fr 1fr;
    }
}

@media (min-width: 1000px) and (max-width: 750px) {
    .video-grid {
        grid-template-columns: 1fr, 1fr, 1fr;
    }
}

@media (min-width: 1000px) {
    .video-grid {
        grid-template-columns: 1fr 1fr;
    }
}
```

## License

This project is licensed under the MIT License.
