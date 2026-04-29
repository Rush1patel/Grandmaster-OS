<div align="center">

  <img src="https://images.chesscomfiles.com/chess-themes/pieces/neo/150/wq.png" alt="Queen" width="100"/>

  <h1 align="center">♟️ GrandMaster OS</h1>

  <p align="center">
    <strong>The ultimate, zero-latency browser-based engine analysis suite for elite chess players.</strong><br>
    <em>Engineered by <strong>Rushi Patel</strong> (@Rush1patel)</em>
  </p>

  <p align="center">
    <a href="https://rush1patel.github.io/Grandmaster-OS/">
      <img src="https://img.shields.io/badge/Try_It_Out-Live_Demo-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white&shadow=1" alt="Live Demo" />
    </a>
  </p>

  <p align="center">
    <a href="https://reactjs.org/">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    </a>
    <a href="https://tailwindcss.com/">
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
    </a>
    <a href="https://stockfishchess.org/">
      <img src="https://img.shields.io/badge/Stockfish-10_WASM-orange?style=for-the-badge&logo=webassembly&logoColor=white" alt="Stockfish" />
    </a>
    <a href="https://github.com/Rush1patel/Grandmaster-OS/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-AGPL_v3-blue?style=for-the-badge" alt="License: AGPL v3" />
    </a>
  </p>

  <p align="center">
    <a href="#how-it-works">
      <img src="https://img.shields.io/badge/Explore_Docs-4a5568?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Docs" />
    </a>
    <a href="https://github.com/Rush1patel/Grandmaster-OS/issues/new?labels=bug">
      <img src="https://img.shields.io/badge/Report_Bug-ca3431?style=for-the-badge&logo=github&logoColor=white" alt="Bug" />
    </a>
    <a href="https://github.com/Rush1patel/Grandmaster-OS/issues/new?labels=enhancement">
      <img src="https://img.shields.io/badge/Request_Feature-8b5cf6?style=for-the-badge&logo=github&logoColor=white" alt="Feature" />
    </a>
  </p>

</div>

<hr />

<div align="left">
  <h2>🚀 Overview</h2>
  <p><b>GrandMaster OS</b> bridges the gap between your public match history and professional-grade engine evaluation. Unlike heavy desktop software, this entire suite runs <b>locally in your browser</b> using WebAssembly. No downloads, no server processing delays, and absolute data privacy.</p>
  <p>Simply type in a Chess.com username and instantly discover brilliant moves, identify blunders, and explore alternate branches with real-time Stockfish analysis.</p>
</div>

<br />

<h2>✨ Key Highlights</h2>

<table width="100%" style="border-collapse: collapse; text-align: left;">
  <tr>
    <td width="20%" align="center" style="padding: 10px; border: 1px solid #ddd;">🚀 <b>Instant Import</b></td>
    <td width="80%" style="padding: 10px; border: 1px solid #ddd;">Connects directly to the Chess.com PubAPI to fetch your last 40 standard games in milliseconds.</td>
  </tr>
  <tr>
    <td width="20%" align="center" style="padding: 10px; border: 1px solid #ddd;">🤖 <b>Edge Analysis</b></td>
    <td width="80%" style="padding: 10px; border: 1px solid #ddd;">Powered by <b>Stockfish 10 (WASM)</b> running on a dedicated Web Worker. Zero server-side lag.</td>
  </tr>
  <tr>
    <td width="20%" align="center" style="padding: 10px; border: 1px solid #ddd;">📊 <b>Live Metrics</b></td>
    <td width="80%" style="padding: 10px; border: 1px solid #ddd;">Calculates Accuracy, Estimated Rating, and categorizes every move (Brilliant, Blunder, Book).</td>
  </tr>
  <tr>
    <td width="20%" align="center" style="padding: 10px; border: 1px solid #ddd;">🎯 <b>Smart Branches</b></td>
    <td width="80%" style="padding: 10px; border: 1px solid #ddd;">Drag and drop pieces on the board to deviate from the real game. The engine instantly evaluates your custom scenarios.</td>
  </tr>
  <tr>
    <td width="20%" align="center" style="padding: 10px; border: 1px solid #ddd;">🎨 <b>Themes</b></td>
    <td width="80%" style="padding: 10px; border: 1px solid #ddd;">Beautiful, responsive UI featuring Dark (AMOLED), Light, and an ultra-modern Neon theme.</td>
  </tr>
</table>

<br />

<h2>🛠️ Architecture</h2>
<ul>
  <li><b>Frontend Framework:</b> <code>React.js</code> (Component-driven UI)</li>
  <li><b>Styling Engine:</b> <code>Tailwind CSS</code> (Utility-first, heavily customized themes)</li>
  <li><b>Chess Logic:</b> <code>Chess.js</code> (Move validation, PGN parsing, FEN generation)</li>
  <li><b>Engine Backend:</b> <code>Stockfish.js</code> (Running via Web Workers to prevent UI freezing)</li>
  <li><b>Icons & Assets:</b> <code>Lucide React</code> & Custom Inline SVGs</li>
</ul>

<br />

<h2>💻 Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li><b>Node.js</b> (v16 or higher)</li>
  <li><b>npm</b> or <b>yarn</b></li>
</ul>

<h3>Local Installation</h3>
<ol>
  <li>
    <b>Clone the repository</b>
    <pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 10px; border-radius: 5px;"><code>git clone https://github.com/Rush1patel/Grandmaster-OS.git
cd Grandmaster-OS</code></pre>
  </li>
  <li>
    <b>Install dependencies</b>
    <pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 10px; border-radius: 5px;"><code>npm install</code></pre>
  </li>
  <li>
    <b>Launch the Dashboard</b>
    <pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 10px; border-radius: 5px;"><code>npm start</code></pre>
    <p><i>The application will automatically open in your browser at <code>http://localhost:3000</code>.</i></p>
  </li>
</ol>

<br />

<h2 id="how-it-works">📖 How It Works</h2>
<ol>
  <li><b>Search:</b> Enter any valid Chess.com username (e.g., <code>Hikaru</code>, <code>GothamChess</code>) on the home screen.</li>
  <li><b>Select:</b> Browse the dynamic grid of recent matches and click on a game card.</li>
  <li><b>Analyze:</b> Use the Arrow Keys (← / →) or UI controls to navigate through the game. Stockfish works in the background to provide Depth-12 analysis.</li>
  <li><b>Explore:</b> Want to test a different line? Just make a move on the board! A custom branch will be created, and you can easily snap back using the "Return to Game" button.</li>
</ol>

<br />

<h2>🗺️ Roadmap</h2>
<ul style="list-style-type: none; padding-left: 0;">
  <li>✅ Integrate Chess.com PubAPI</li>
  <li>✅ Implement Web Worker for Stockfish WASM</li>
  <li>✅ Add Interactive Branching (What-if analysis)</li>
  <li>✅ Custom Board & App Themes (Dark/Light/Neon)</li>
  <li>⬜ <b>Multi-PV Support:</b> View the top 3 engine lines simultaneously.</li>
  <li>⬜ <b>Lichess Integration:</b> Support for importing games from Lichess.org.</li>
  <li>⬜ <b>Cloud Save:</b> Persist your favorite analyzed games locally or to a personal database.</li>
</ul>

<br />

<h2>🤝 Contributing</h2>
<p>Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are <b>greatly appreciated</b>.</p>
<ol>
  <li>Fork the Project</li>
  <li>Create your Feature Branch (<code>git checkout -b feature/AmazingFeature</code>)</li>
  <li>Commit your Changes (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
  <li>Push to the Branch (<code>git push origin feature/AmazingFeature</code>)</li>
  <li>Open a Pull Request</li>
</ol>

<br />

<h2>📄 License</h2>
<p>This project is open-source and free to use. It is licensed under the <b>GNU Affero General Public License v3.0 (AGPL-3.0)</b>. See the <a href="https://github.com/Rush1patel/Grandmaster-OS/blob/main/LICENSE"><code>LICENSE</code></a> file for more detailed information.</p>

<hr />

<div align="center">
  <i>Made with ❤️ by <a href="https://github.com/Rush1patel">Rushi Patel</a></i>
</div>
