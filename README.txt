ATAUR RAHMAN AKASH - ARCHITECTURAL PORTFOLIO
=============================================
Included Files in this Folder:
1. index.html   - Main Landing / Home Page
2. style.css    - Complete Stylesheet (Navbar, Cloud BG, 3D Orbit, Accordion, Animations)
3. script.js    - Complete JavaScript (Continuous Audio, Day/Night Toggler, Canvases, Routing)
4. 3Dvis.html   - 3D Visualization Page (Exterior & Interior)
5. AW.html      - Animation Walkthrough Page (Exterior & Interior)
6. exp.html     - Experiences Page (National & International)
7. studio.html  - Architectural Studio Page
8. model.html   - Miniature Model Making Page
9. audio.mp3    - Pre-included ambient background track (you can replace this with your own audio.mp3)
10. resume.pdf  - Pre-included CV PDF (you can replace this with your original Akash-CV.pdf renamed to resume.pdf)

How to Run Locally:
- Simply extract this ZIP folder and double-click "index.html" to open it in any browser, OR open the folder with VS Code Live Server.

SHARED COMPONENTS (UPDATED)
--------------------------
- nav.html is the single shared navigation component.
- footer.html is the single shared footer component (including Resume and Contact quick links).
- All six pages load these files through script.js into #nav-placeholder and #footer-placeholder.
- Edit nav.html or footer.html once; the change will appear on all six pages after refresh.
- The Direct Contact Card modal and its styling/content were intentionally left unchanged.

IMPORTANT: RUN THROUGH A LOCAL WEB SERVER
-----------------------------------------
Because nav.html and footer.html are loaded with JavaScript fetch(), browsers block
those requests when an HTML page is opened directly with file:// (double-click).
Open the extracted folder in VS Code and choose "Open with Live Server", or run
a local server from this folder with:
    python -m http.server 8000
Then visit:
    http://localhost:8000/index.html

Do not move nav.html, footer.html, script.js, style.css, or the image assets into
different folders unless you also update their paths.
