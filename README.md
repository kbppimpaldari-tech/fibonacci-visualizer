Fibonacci Sequence & Golden Spiral Visualizer

An interactive, educational web application designed to visualize the Fibonacci sequence through a geometrically accurate proportional spiral. This tool is built specifically for students and educators to explore the relationship between the Fibonacci numbers and the growth of the Golden Spiral.

🚀 Live Demo

https://mangesh-nikam.github.io/fibonacci-visualizer/

📖 About the Project

This visualizer generates the Fibonacci sequence ($1, 1, 2, 3, 5, 8, \dots$) and draws squares whose side lengths correspond exactly to these numbers.

Key Features:

Proportional Accuracy: Unlike simple sketches, this app uses strict geometric logic to ensure every square is in proportion to the Fibonacci sequence.

Outward Spiral: The curves are drawn using the outer pivot points of each square to demonstrate the expansion of the spiral.

Data Export: Students can export the generated sequence data as a CSV file for analysis in Excel or Google Sheets.

Responsive Design: Works on desktops, tablets, and mobile devices.

📐 How it Works

The Sequence: Each number is the sum of the two preceding ones ($F_n = F_{n-1} + F_{n-2}$).

The Geometry:

The first square has a side of 1 unit.

The second square has a side of 1 unit.

The third square has a side of 2 units ($1+1$).

The fourth square has a side of 3 units ($2+1$), and so on.

The Layout: Squares are attached in a clockwise rotation (Right, Bottom, Left, Top) to create a perfect bounding rectangle.

🛠️ Built With

HTML5 Canvas: For high-performance geometric rendering.

Tailwind CSS: For a modern, clean user interface.

JavaScript (ES6): For the sequence logic and dynamic scaling.

⚖️ Licensing

This project is dual-licensed to support both open-source development and educational reuse:

Software License: MIT License – The code is open-source and free to use or modify.

Content License: Creative Commons Attribution 4.0 International (CC BY 4.0) – Visual designs and educational data require attribution.

Created by Mangesh Nikam 📧 nik.mangesh@gmail.com
