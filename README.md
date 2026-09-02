# Top 5 — Rotation

A minimalist, interactive music ranking interface that displays a personal **Top 5 artist rotation**. Each artist appears as an expandable row containing their genre and five selected tracks.

## ✨ Features

* Interactive expandable artist rows
* Displays a Top 5 artist ranking
* Shows each artist's genre
* Displays five tracks per artist
* Shows track durations
* Responsive layout for desktop and mobile
* Smooth expand/collapse animations
* Keyboard-accessible artist selection
* Reduced-motion support for accessibility
* Custom visual styling with a dark, editorial-inspired design
* Artist images displayed as circular avatars

## 🎵 Featured Artists

| Rank | Artist         | Genre           |
| ---- | -------------- | --------------- |
| 01   | Yeat           | Hip-Hop         |
| 02   | Kendrick Lamar | Hip-Hop         |
| 03   | Steve Lacy     | R&B             |
| 04   | PinkPantheress | Alternative Pop |
| 05   | Mac Miller     | R&B / Soul      |

Each artist contains a selection of five tracks.

## 🛠️ Technologies Used

* **HTML5** — Structure and content
* **CSS3** — Layout, animations, responsive design and visual styling
* **JavaScript** — Interactive expandable rows
* **Google Fonts**

  * Fraunces
  * Public Sans
  * IBM Plex Mono

## 📁 Project Structure

```text
project/
│
├── index.html
│
└── images/
    ├── yeat.jpeg
    ├── kendrick.jpeg
    ├── steve.jpeg
    ├── pinkpanther.jpeg
    └── mac.jpeg
```

The HTML references the artist images from an `images/` directory, so the folder structure should be maintained for the avatars to display correctly.

## 🖱️ How It Works

The interface initially displays five collapsed artist rows.

Clicking an artist:

1. Expands that artist's row.
2. Displays their five tracks.
3. Hides the details of the other artists.
4. Updates the accessibility state using `aria-expanded`.
5. Hides the "tap a row to expand" hint.

Clicking the currently expanded artist collapses it again.

## 📱 Responsive Design

The interface adapts to smaller screens using CSS media queries.

On mobile devices:

* The header height is reduced.
* Artist genres are initially hidden.
* The expanded artist displays its genre.
* Ranking numbers remain visible.
* Artist avatars and typography scale according to the viewport.

The project also respects `prefers-reduced-motion`, disabling animations for users who have reduced motion enabled.

## 🎨 Design

The project uses a dark, editorial aesthetic with:

* Dark brown/black backgrounds
* Cream-colored typography
* Gold ranking numbers
* Rust and teal accent colors
* Large translucent ranking numbers
* Serif display typography
* Monospace metadata
* Subtle grain/noise texture

The layout is designed to occupy the full viewport rather than behaving like a conventional scrolling webpage.

## 🚀 Running the Project

No build tools or dependencies are required.

Simply open:

```text
index.html
```

in a modern web browser.

For the best experience, use a current version of Chrome, Edge, Firefox or Safari.

## 🔧 Customisation

To create your own rotation, edit the artist information directly inside `index.html`.

You can change:

* Artist names
* Genres
* Track names
* Track durations
* Artist images
* Rankings
* Colors
* Fonts
* Animation behaviour

Artist images can be replaced by changing the image paths in the `.avatar` elements.

## 📄 License

This project is provided for personal and educational use. You may modify and adapt the source code for your own projects.
