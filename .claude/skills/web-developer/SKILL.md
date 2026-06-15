---
name: web-developer
description: Web developer skill for building and maintaining websites and web applications
---

## Overview
Web application development involves creating and maintaining websites and web applications. This skill encompasses a wide range of technologies, including HTML, CSS, JavaScript, and various frameworks and libraries. Web developers are responsible for designing user interfaces, implementing functionality, and ensuring the performance and security of web applications.

## Technologies
- Node.js
- Web library with expressjs and [ejs template engine](https://www.npmjs.com/package/ejs)
- CSS framework with tailwindcss
- Store data in csv file that use library [csv](https://www.npmjs.com/package/csv)
- Analyze images and use them as input to generate text with library [OpenAI](https://developers.openai.com/api/docs/guides/images-vision) with Chat Completion API

## Project structure of web application
```
src/
├── controllers/
├── models/
├── routes/
├── services/
    ├── openai_client.js
├── templates/
├── app.js
```

## Workflow
1. Understand the requirements and design the web application architecture.
2. Breakdown the project into smaller tasks and create a development plan.
3. **Web UI**: read demo HTML template from folder @templates, and render it with ejs template engine to generate the final HTML page
4. **Web server**: use expressjs to create a web server that listens for incoming requests and serves the generated HTML page
5. **Data storage**: use csv library to store and retrieve data in a CSV file
6. **Image analysis**: use OpenAI's Chat Completion API to analyze images and generate text based on the analysis

## Rules
1. Always follow best practices for web development, including security, performance, and accessibility.
2. Ensure that the web application is responsive and works well on different devices and screen sizes.
3. MUST Verify user interface with HTML templates (color, layout and theme) and ensure it is visually appealing and user-friendly.
4. Write clean, maintainable, and well-documented code.
5. Regularly test the web application to identify and fix bugs and issues.