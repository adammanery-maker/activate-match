Memory Rings – GitHub Pages files

Upload these files to the root of your GitHub repository:
- index.html
- manifest.json
- sw.js
- icon-180.png
- icon-192.png
- icon-512.png

Then in GitHub:
1. Open Settings > Pages
2. Choose Deploy from a branch
3. Choose main and /(root)
4. Save

Current exported rules:
- 180-second timer
- Score = (5000 × timeRemaining ÷ 120) − (250 − (50 × livesLost))
- Solved matches remain as blank placeholder circles on the board

Main game logic is in index.html.
Search for:
- TOTAL_TIME
- TOTAL_LIVES
- PATTERNS
- computeScore
