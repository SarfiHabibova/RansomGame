# RansomGame
RansomGame is an interactive and amusing game designed to simulate real-world ransomware scenarios while making learning cybersecurity practices engaging and enjoyable. The game is structured as follows:

- Levels and Gameplay
  - The game consists of four levels, each with progressively challenging questions. Level 1 contains simpler questions, while Level 4 features complex, scenario-based questions that test critical thinking.
  - At each level, users face a set of five questions. Mistakes are penalized, with increasing severity as the levels progress. For example, making three mistakes in Level 1 encrypts the user’s pictures, while two mistakes in Level 4 encrypts desktop files.

- Pointing System
  - The scoring mechanism is time-sensitive, similar to Kahoot’s pointing system. Faster responses yield higher points. For instance, answering a question with 30 seconds left on the timer earns more points than answering with only 10 seconds remaining.

- Mini-Games
  - Each level concludes with a mini-game designed in Python, offering users an opportunity to earn bonus points while enjoying additional interactive activities. These mini games range from solving puzzles to quick reflex challenges.

- File Encryption Simulation
  - To simulate the real impact of ransomware, the game temporarily encrypts specific folders (e.g., pictures, downloads, documents, or desktop files) upon repeated mistakes. However, users can redeem their accumulated points to decrypt these files at the end of the game.

- Decryption Mechanism
  - In RansomGame, encrypted files are not automatically decrypted within the game. To restore your files, you’ll need to visit bambooc.org. On the website, you can download a file containing the decryption key. Once you use this key, all your encrypted files will be unlocked. This approach enhances the game’s realism while ensuring your files remain safe and fully recoverable.
