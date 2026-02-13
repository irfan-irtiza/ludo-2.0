🎲 IRFAN'S LUDO STAR SUPREME
A high-performance, web-based Ludo experience featuring real-time multiplayer, ballistic dice physics, and a futuristic dark-mode UI.

🚀 Features
P2P Multiplayer: Uses PeerJS for direct connection between players, ensuring low latency.

Private Rooms: Create a unique room code or join friends instantly.

Dynamic UI: Built with Tailwind CSS featuring a "Glass-Panel" design and mesh background gradients.

Interactive Gameplay: * Ballistic dice throwing animations.

Smooth piece movement with "jump" physics.

Automatic capture mechanics and safe zones (Stars).

Live Status: Real-time turn tracking and player connectivity indicators.

Audio Engine: Integrated Web Audio API for immersive sound effects without external assets.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS

Networking: PeerJS

Database/Backend: Firebase (Initialization & Analytics)

Fonts: Plus Jakarta Sans & Syncopate via Google Fonts

📥 Getting Started
Since this is a client-side application contained in a single file, setup is minimal:

Clone or Copy: Save the index.html file to your local machine.

Firebase Config: The app currently uses a pre-configured Firebase instance. For production, replace the firebaseConfig object in the <script> tag with your own credentials.

Run: Open index.html in any modern web browser.

Host a Room: Click "CREATE PRIVATE ROOM," share the generated code with friends, and wait for them to join the lobby.

🎮 How to Play
Identity: Enter your display name and choose your team color (Red, Green, Yellow, or Blue).

The Goal: Navigate all 4 pieces from your base to the "Kingdom" (Home) in the center of the board.

Rules:

Roll a 6 to move a piece out of the base.

Landing on an opponent's piece (outside of Star zones) captures them and sends them back to their base.

Capturing a piece or rolling a 6 grants an extra turn.

Landing on a Star icon protects your piece from being captured.

📋 Note on Connectivity
Because this uses P2P networking:

The Creator of the room acts as the host. If the host closes their browser, the session ends.

Ensure you are not behind a restrictive firewall or VPN that blocks WebRTC connections.
