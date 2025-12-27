# code-converter-code-to-algorithm-
it is a website which convert code into algorithm and flowchart
Algorithm to Flowchart Converter
A simple web-based tool that uses AI to transform code or logic-based text into visual flowcharts. Perfect for generating quick documentation and visual aids for technical projects.

🚀 How it Works
Input: You provide a code snippet or a step-by-step algorithm in the text area.

AI Analysis: The tool sends the text to the Gemini 2.0 Flash model with a specific prompt to identify logic structures (Start, Process, Decision, etc.).

Visual Output: The application receives structured JSON and renders it into a vertical flowchart using CSS and Tailwind.

🛠️ Features
Intelligent Parsing: Recognizes different programming logic types automatically.

Visual Standards: * Green Ovals: Start and End points.

Yellow Parallelograms: Input and Output operations.

Red Diamonds: Decision points and branching.

Blue Rectangles: General processing steps.

Clean UI: Built with Tailwind CSS for a modern, responsive look.

📦 Technical Setup
Since this is a client-side application, no heavy installation is required:

File Structure: The project is contained within a single index.html file.

API Integration: It uses the Google Generative AI API. To use it, you must insert your API key into the API_KEY constant within the script tag.

Dependencies: * Tailwind CSS (via CDN)

Inter Font (via Google Fonts)

📝 Example Input
Input:

Plaintext

1. Receive user age.
2. If age is 18 or older, allow access.
3. Otherwise, deny access.
4. End.
Result: The tool will generate a vertical flow diagram showing the input, the "Age >= 18" decision diamond, and the resulting process paths.

🏗️ Future Enhancements
Branching Logic: Currently, the flowchart renders in a linear sequence; future updates will allow for side-by-side branching for "Yes/No" paths.

Markdown Export: A one-click button to copy the flowchart logic as a Markdown-compatible image or code block.
