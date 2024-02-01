# Project Overview

## Overview

Welcome to this project showcasing the development of a streamlined web application utilizing Apache Tomcat. The core functionality revolves around a servlet crafting personalized greetings and an HTML page providing easy access to this servlet. With Java 17 at its core, the entire project is seamlessly deployed on the Apache Tomcat server.

## Implementation Steps

### Step 1: Download and Install Apache Tomcat

Begin by downloading and installing Apache Tomcat, a widely embraced open-source servlet container, on your local machine.

### Step 2: Develop the Servlet

Create a servlet named Servlet designed to craft personalized greetings. Configured to respond to HTTP GET requests, this servlet generates HTML content containing the personalized greeting.

### Step 3: Compile the Servlet

Utilize Java 17 to compile the `Servlet.java` file, generating the corresponding `Servlet.class` file.

### Step 4: Deploy the Servlet to Apache Tomcat

Place the compiled servlet (`Servlet.class`) in the appropriate directory within the Apache Tomcat `webapps` folder. Specifically, position the servlet class in the `WEB-INF/classes` directory of the web application.

### Step 5: Generate HTML Page with Link to Servlet

Develop an HTML page named `index.html` featuring a link to the servlet. Apache Tomcat serves this HTML page, incorporating an anchor element (`<a>`) linking directly to the servlet URL.

### Step 6: Validate Interaction

Confirm the seamless interaction between the HTML page and servlet by accessing the HTML page through a web browser. Clicking the link within the HTML page should invoke the servlet, leading to the display of the personalized greeting.

**Please Note:** Refer to the submitted report on Moodle for additional visuals and comprehensive details.

---

