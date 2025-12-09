# HackIT: Pet Treasure Hunt

## Overview
**Pet Treasure Hunt** is a HackIt-style web project created for an IT Security course.  
The site consists of multiple “rooms,” each containing a standalone security puzzle.  
To progress, the user must **solve the challenge in each room** to obtain the URL (or clue) for the next page.



This project acts as a hands-on introduction to common security weaknesses, secure coding concepts, and beginner-friendly exploitation techniques.

---

## Structure
- `index.html` — Introduction / starting point  
- `room1.html` – `room11.html` — Individual puzzle rooms  
- `admin1.html` — An intentional misconfiguration room (e.g., IDOR/admin access)  
- `final_evolution.html` — Final page after all puzzles  
- `style.css` — Shared stylesheet  
- `res/` — Images and other static assets  

---

## How It Works
1. Open **index.html** in a browser to start.  
2. Each room contains a unique security-related challenge.  
3. Solving the challenge reveals the **URL and/or hidden parameter** needed to access the next room.  
4. Continue through all rooms until reaching the final evolution.

---

## Topics Demonstrated
Each room highlights concepts commonly discussed in IT security classes, such as:

- Hidden parameters & URL manipulation  
- Weak hashes  
- Input validation & sanitization  
- Basic XSS examples  
- Directory/parameter guessing  
- Authentication bypasses  
- IDOR (Insecure Direct Object Reference)  
- Misconfigurations  
- Client-side security flaws  
- Security through obscurity pitfalls  


---

## Usage
1. Access through: (https://jgatmait.github.io/pettreasure/)
