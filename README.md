# CEN3721---Final-Project
Our final project

Introduction and Motivation

A web application is an interactive computer program developed using web technologies (HTML, CSS, JS), which stores (Database, Files) and manipulates data (CRUD - create, read, update and delete). Webapps can be used by a team or single user to perform tasks over the internet.

Objective: In this assignment, you will develop a web application using the Streamlit framework that focuses on usability goals and adheres to human-computer interaction (HCI) design principles. You will use Streamlit features and API requests to fetch and display data in various forms, such as charts, plots, maps, and tables. Your web app must include interactive widgets, such as buttons, select boxes, radio buttons, text input, color input, and other features that help achieve the HCI guidelines. Your project needs to manipulate data requested through an API. The format of the documents received can be of any type, but I highly recommend JSON, XML, or CSV.
Assignment Details

    Select a theme or topic for your web application: Choose a topic that interests you and has public APIs available for data retrieval. Examples include weather forecasting, stock market analysis, social media trends, or public transportation information.

    Research and identify relevant APIs: Find one or more APIs that provide data relevant to your chosen topic. Ensure the APIs are publicly accessible and have clear documentation.

    Here is a list of possible APIs that might be of interest to you:
        https://github.com/public-apis/public-apis
        https://rapidapi.com/collection/list-of-free-apis

    Define usability goals: Based on your selected topic, define a set of usability goals for your web app. These may include effectiveness, efficiency, learnability, memorability, error prevention, and user satisfaction.

    Design the web application: Sketch out a rough layout of your application, identifying the key components and user interactions. Consider the placement of widgets, navigation elements, and data visualizations.

    Develop the web app using Streamlit: Implement your design using Streamlit, incorporating the following features:
        API requests: Fetch data from the selected APIs
        At least 1 interactive table (https://docs.streamlit.io/library/api-reference/data/st.dataframe 

Links to an external site.)
At least 2 chart elements,  such as line, area or bar charts (matplotlib is allowed). To display:

    a line chart - https://docs.streamlit.io/library/api-reference/charts/st.line_chart 

Links to an external site.
an area chart - https://docs.streamlit.io/library/api-reference/charts/st.area_chart
Links to an external site.
a bar chart - https://docs.streamlit.io/library/api-reference/charts/st.bar_chart

    Links to an external site.

At least 1 map with points marked on it (a simple map can be created using https://docs.streamlit.io/library/api-reference/charts/st.map
Links to an external site. or a more complex 3d map at https://docs.streamlit.io/library/api-reference/charts/st.pydeck_chart

    Links to an external site.)
    At least 1 button widget (https://docs.streamlit.io/library/api-reference/widgets/st.button)
    At least 1 checkbox widget (https://docs.streamlit.io/library/api-reference/widgets/st.checkbox)
    At least 2 of the essential feedback and messages boxes to the users:

        Success box - https://docs.streamlit.io/library/api-reference/status/st.success 

Links to an external site. 
Information box - https://docs.streamlit.io/library/api-reference/status/st.info
Links to an external site. 
Warning box - https://docs.streamlit.io/library/api-reference/status/st.warning
Links to an external site. 
Error box - https://docs.streamlit.io/library/api-reference/status/st.error
Links to an external site. 
Exception message (optional) - https://docs.streamlit.io/library/api-reference/status/st.exception

    Links to an external site. 

At least any 5 different widgets chosen from the following:

    Radio button - https://docs.streamlit.io/library/api-reference/widgets/st.radio 

Links to an external site. 
Selectbox - https://docs.streamlit.io/library/api-reference/widgets/st.selectbox
Links to an external site. 
Multiselect - https://docs.streamlit.io/library/api-reference/widgets/st.multiselect
Links to an external site. 
Slider - https://docs.streamlit.io/library/api-reference/widgets/st.slider
Links to an external site. 
Select-slider - https://docs.streamlit.io/library/api-reference/widgets/st.select_slider
Links to an external site. 
Text input - https://docs.streamlit.io/library/api-reference/widgets/st.text_input
Links to an external site. 
Number input - https://docs.streamlit.io/library/api-reference/widgets/st.number_input
Links to an external site. 
Text-area - https://docs.streamlit.io/library/api-reference/widgets/st.text_area
Links to an external site. 
Date input - https://docs.streamlit.io/library/api-reference/widgets/st.date_input
Links to an external site. 
Time input - https://docs.streamlit.io/library/api-reference/widgets/st.time_input
Links to an external site. 
File uploader - https://docs.streamlit.io/library/api-reference/widgets/st.file_uploader
Links to an external site. 
Color - https://docs.streamlit.io/library/api-reference/widgets/st.color_picker

            Links to an external site. 
        You may include a progress bar for certain components of your application; however, this is not mandatory
        You may include media elements such as image, audio or video, which are not a requirement but can add to the overall harmony of the web application being developed

        Streamlit allows you to display a sidebar, insert containers laid out as side-by-side columns, insert a multi-element container that can be expanded/collapsed, among many other features:

        Sidebar - https://docs.streamlit.io/library/api-reference/layout/st.sidebar
        Columns - https://docs.streamlit.io/library/api-reference/layout/st.columns 
        Expander - https://docs.streamlit.io/library/api-reference/layout/st.expander 

    Apply HCI design principles: Ensure your web app adheres to HCI design principles, such as visibility, feedback, consistency, flexibility, and error prevention. Consider the following aspects:
    a. Information architecture: Organize content and functionality to promote ease of use and understanding.
    b. Navigation: Provide clear and consistent navigation options.
    c. User feedback: Offer immediate and informative feedback to user actions.
    d. Aesthetics: Maintain a visually appealing and professional design.

    Test your web app: Conduct usability testing with a small group of users to identify any issues or areas for improvement. Make any necessary changes based on the feedback received.

    Document your work: Prepare a report that includes the following sections:
    a. Introduction: Introduce your web app and its purpose.
    b. Usability goals: Describe the usability goals you set for your web app and explain how you addressed each goal.
    c. Design process: Discuss your design process, from sketching to implementation.
    d. API integration: Explain how you utilized the APIs and discuss any challenges or limitations encountered.
    e. Interactive widgets: Describe the widgets you incorporated and their purposes.
    f. HCI design principles: Discuss how your web app adheres to HCI design principles.
    g. Testing and feedback: Summarize the results of your usability testing and any changes made in response to feedback.
    h. Conclusion: Reflect on your experience and discuss potential future improvements.

    Submission: Submit your web app's source code, along with your report and any supporting materials, such as sketches or user feedback.

Requirements

The web application needs to be developed using Python programming languages version 3.9 (or later) and the open-source framework Streamlit. Your objective is to create a web application that manipulates data and displays information to the users.

The biggest HCI challenges will be the selection of appropriate layouts and containers. For example, you will need to study your target audience and the data being manipulated to decide, for example, whether to have 3 columns or 1 single column, or even whether an input data should be entered as a radio button or a text field, or whether to display a certain data output as a line chart or a map. For each project, you should think about the following structured design process:

    User Research: Identify and interview potential users to gather requirements.
    Prototyping: Create low-fidelity prototypes (e.g., wireframes) before coding.
    Usability Testing: Conduct usability tests with real users, iterating on design based on feedback.
    Accessibility: Ensure apps are designed with accessibility in mind, using guidelines such as the Web Content Accessibility Guidelines (WCAG) 

    Links to an external site..
    Reflection: Write a reflection on the design process, user feedback, and iterations.

Initial Steps

    Choose a topic of interest to you (examples: sports, geology, music, cryptocurrency, farming, etc.)
    Search for free and public datasets or free public APIs where you can request data to be manipulated and visualized in your web application
    Start developing your web application:

        Download and install Python programming language version 3
        Download and Install PyCharm IDE Professional version by applying for a student license using your FIU email
        Create a new Python project in PyCharm IDE and:
            Install the necessary packages: pip install streamlit numpy pandas
            Import the above packages:
            import streamlit as st
            import pandas as pd
            import numpy as np
    Include the components listed in REQUIREMENTS according to the goal of your web application and to the type of data being manipulated.
    Distribute text elements in the form of title, header, subheader, caption or pre-formatted text across the web application so that the content of your web app engages readers and drives them to taken the necessary actions to fulfill your apps’s goals. Avoid dull, lifeless, and overlong prose. Try keeping text short and intriguing. This will encourage users to click through to other elements. Group content into cohesive categories by breaking it up into short paragraphs enriched with visual elements. This can help you make your web app have a light and engaging feel.
    You are ready to submit it!
