# New Team Card

This project is a responsive and stylish card component that can be used to display team members' information, such as profile pictures, titles, and roles.

## Preview

![Team Card Preview](https://img.ultronprivat.media/u/3tjPpz.png)

## Features

- **Responsive Design**: The card is responsive and works well on different screen sizes.
- **Customizable**: Easily change the images, titles, and roles via the HTML.
- **Discord Integration**: Automatically fetch your Discord profile picture and banner using your Discord ID.
- **Hover Effects**: Buttons change styles when hovered for better user interaction.

## Getting Started

### Prerequisites

- Basic understanding of HTML and CSS.
- A text editor, like VSCode or Sublime Text.
- A web browser to view the card.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/UltronReal/team_card_discord.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd team_card_discord
    ```

3. **Open the `index.html` file in your browser:**

    ```bash
    open index.html
    ```

### Customization

To customize the card:

- **Profile Image**: Automatically pull your Discord profile picture by replacing `ID` in the following URL with your actual Discord ID:

    ```html
    <img src="https://id.rappytv.com/ID/icon" alt="Profile Picture">
    ```

- **Banner Image**: Similarly, fetch your Discord banner by replacing `ID` in this URL:

    ```html
    <img src="https://id.rappytv.com/ID/banner" alt="Discord Banner">
    ```

- **Title and Subtitle**: Update the text in the `card__title` and `card__subtitle` divs respectively.

### CSS Variables

You can adjust the look of the card by modifying the CSS variables at the top of the CSS file:

- `--main-color`: Controls the main accent color.
- `--submain-color`: Controls the subtitle text color.
- `--bg-color`: Controls the background color of the card.


## Acknowledgments

- Design inspired by [Uiverse.io](https://uiverse.io/).
- Discord integration powered by [RappyTV Discord API](https://id.rappytv.com/).

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any changes you would like to make.
