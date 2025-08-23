# gameshub
A Website Consists of classic retro games , Stress Relief
🕹️ Retro Arcade Hub - NOVA BLADE

Step back in time with the Retro Arcade Hub! This project is a visually stunning, one-stop portal dedicated to the golden age of gaming. We're bringing classic, nostalgic games like Snake, Pac-Man, and Tic-Tac-Toe back to life with a modern, futuristic aesthetic, all playable directly in your browser.

Built with a passion for retro gaming and modern web technologies, this hub features a dynamic particle background, immersive background audio, and sleek, neon-lit UI to create an unforgettable gaming experience.


✨ Live Demo

[(https://novablade.netlify.app/)]


🎮 Games Included

This arcade currently features a collection of timeless classics:

    🐍 Snake Xenia: The definitive serpent adventure. Grow your snake by eating pellets, but don't run into the walls or your own tail!

    👻 Pac-Man: Navigate the maze, munch on dots, and avoid the ghosts in this iconic arcade classic.

    ⭕ Tic-Tac-Toe: A simple yet strategic two-player game. Can you get three in a row?

...with more games planned for the future!

🚀 Features

    Interactive Particle Universe: A dynamic JavaScript canvas background where particles react to your mouse movements.

    Immersive Audio: Ambient background music to set the mood for a retro gaming session.

    Futuristic UI/UX: A sleek, dark-themed interface with neon glows, glassmorphism cards, and animated SVG icons.

    3D Hover Effects: Game cards lift and tilt on hover, providing a satisfying, tactile feel.

    Fully Responsive: Enjoy a seamless experience on any device, from your desktop monitor to your mobile phone.

    Pure HTML/CSS/JS: No complex frameworks needed. The project is lightweight and easy to understand.

    Easily Extensible: A modular structure makes it simple to add new games to the hub.

🛠️ Built With

    Frontend: HTML5, Vanilla JavaScript (ES6+)

    Styling: Tailwind CSS, Custom CSS3 Animations & Properties

    Fonts: Google Fonts (Orbitron & Rajdhani)

📂 Project Structure

The project is organized with a clean and intuitive file structure:

SNAKE/
├── audio/
│   └── Dancing in Green Grass - The Kyoto Connection.mp3
├── index.html              # The main landing page/hub
├── pac-man.html            # The Pac-Man game page
├── snakeXenia.html         # The Snake game page
├── tictactoe.html          # The Tic-Tac-Toe game page
└── README.md

🏁 Getting Started

To get a local copy up and running, follow these simple steps.

    Clone the repository
    Bash

git clone https://github.com/your-username/your-repo-name.git

Navigate to the project directory
Bash

    cd SNAKE

    Open index.html in your browser. You're ready to play!

🧩 How to Add a New Game

Want to expand the arcade? Here’s how to add a new game:

    Create the Game File: Create a new HTML file for your game (e.g., pong.html) in the root directory. Build your game's logic and visuals inside this file.

    Update the Hub Page: Open index.html.

    Add the Game Card: Find the <main> section and copy an existing game card block (the <a> tag and its contents).

    Customize the New Card:

        Change the href to point to your new game file: href="pong.html".

        Update the game title (<h2>) and description (<p>).

        Customize the glow colors by changing the CSS variables: --glow-color-1 and --glow-color-2.

        (Optional) Create a new animated SVG icon for your game.

🗺️ Roadmap

This project is actively being developed. Here are some ideas for the future:

    [ ] Add More Games:

        [ ] Tetris (Block Stacker)

        [ ] Pong

        [ ] Asteroids

    [ ] High Score System: Implement localStorage to save high scores for each game.

    [ ] Sound Controls: Add UI elements to mute or control the volume of the background music and game sounds.

    [ ] Improved Mobile Controls: Add on-screen controls or swipe gestures for better mobile gameplay.

See the open issues for a full list of proposed features (and known issues).

🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Thank you!

📄 License

Distributed under the MIT License. See the LICENSE file for more information.
