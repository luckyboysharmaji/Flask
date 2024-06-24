# Flask
POC
# Description
Stored Cross-Site Scripting (XSS) is a security vulnerability where malicious scripts are injected and permanently stored on a target server (e.g., in a database). These scripts are then served to users whenever they access the compromised content, allowing attackers to steal data, hijack sessions, or deface websites. Unlike reflected XSS, the malicious payload is persistent and affects multiple users.

 # Proof of Concept

Step 1. Host the server on Kali Linux.
Step 2. Create a Flask web application with "Hello, World!"
Step 3. Replace the "Hello, World!" with our script: <script>alert("hacked_dark_devil")</script>
Step 4. We noticed that the application executed the malicious script as shown in the screenshots below.

I am sharing a Google Drive link proof of concept with you. Please find the attachment.

https://drive.google.com/file/d/1BZH3sUOCHBW1SFJWW5W2weZlz6ZmKHvl/view?usp=sharing
