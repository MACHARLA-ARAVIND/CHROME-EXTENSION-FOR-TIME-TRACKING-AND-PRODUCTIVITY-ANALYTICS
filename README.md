# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MACHARLA ARAVIND

*INTERN ID*: CT06DF238

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

## Project Title: Chrome Extension for Time Tracking and Productivity Analytics
📝 Project Description:
This project, developed as Task 4 during my CodTech Full Stack Web Development Internship, is a Chrome Extension designed to track the amount of time users spend on various websites and present this data as productivity analytics. The extension helps users monitor their browsing behavior, identify distractions, and stay focused by categorizing sites as either productive or unproductive. It is a practical, real-world application aimed at improving digital time management and self-discipline.The core idea behind the extension is simple but powerful measure how much time users spend on different websites, then provide a daily or weekly breakdown of that time. This information is displayed through a clean popup interface and an optional dashboard for deeper analysis. Additionally, the extension can be enhanced to allow customization, such as letting users label websites according to their productivity goals.
The extension was built using standard Chrome Extension APIs and developed entirely using HTML, CSS, and JavaScript. I created the file structure according to Chrome’s manifest.json specifications and implemented scripts to track active browser tabs. The extension listens for tab changes, captures URL information, calculates time intervals, and stores this data in Chrome’s local storage. This means the extension works offline and does not require any backend database, making it lightweight and efficient for everyday use.One of the key components of the project was the background script (background.js), which runs in the background as a service worker. It detects when users switch tabs or windows and tracks how long they remain on each domain. Another component is the popup interface (popup.html, popup.js), which is displayed when the user clicks the extension icon. This interface shows a summary of time spent on each site in a readable format. There is also a dashboard page (dashboard.html), which provides a deeper overview including categorized sites, visual summaries, and a link for future enhancements like exporting reports.The design is kept intentionally simple and clean, with the goal of presenting useful information without overwhelming the user. Sites such as "leetcode.com" and "github.com" are marked as productive, while sites like "facebook.com" or "instagram.com" are considered unproductive. These categories are configurable in the code and can be adjusted to suit different work styles.This project helped me deeply understand the architecture of Chrome Extensions, how background scripts work, how to use the chrome.storage API for persistence, and how to handle browser events such as tab switches and URL changes. I also learned to manage time data efficiently, convert milliseconds to minutes, and dynamically update UI elements using plain JavaScript.One challenge I faced was ensuring accurate time tracking when switching between tabs or minimizing the browser. To address this, I implemented logic to record timestamps on onActivated and onRemoved events and calculated differences accordingly. Debugging using Chrome’s developer tools also helped fine-tune performance and stability.Overall, this project was a hands-on experience in building browser-based tools with real-world utility. It strengthened my front-end scripting skills, introduced me to the Chrome Extension ecosystem, and gave me confidence to build productivity apps and browser utilities in the future.

# output
