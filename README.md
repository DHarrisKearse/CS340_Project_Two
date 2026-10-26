# CS340 Project Two Portfolio Reflection

## How do you write programs that are maintainable, readable, and adaptable?

I write maintainable programs by using descriptive names, organizing code into focused functions and classes, and adding comments that explain the purpose of the code. In Project One, I created a CRUD Python module to handle database operations. In Project Two, I reused that module to connect the dashboard widgets to MongoDB. This separated the database logic from the dashboard interface, making the code easier to understand, troubleshoot, and update.

One advantage of this approach was that I could reuse existing database operations instead of writing the same queries in multiple places. Changes to the database connection or CRUD methods could be handled within the module. In the future, I could reuse or adapt this module for another dashboard, a web application, or an API that needs to create, read, update, and delete MongoDB records.

## How do you approach a problem as a computer scientist?

I approach a problem by identifying what the client needs, breaking those requirements into smaller tasks, and testing each part before connecting everything. For Grazioso Salvare, this meant understanding how the organization identifies potential rescue dogs and translating its requirements into database queries and dashboard filters. I also needed to consider how the data table and charts would help users understand the results.

This project required me to connect several components, including MongoDB, my CRUD module, and an interactive dashboard. Compared with assignments focused on a single function or program, I had to consider how data moved through the entire application and how user actions affected the displayed results. For future client projects, I would clarify the required data and workflows, review the quality and structure of the dataset, and test queries against expected results. I would also choose indexes based on common searches and gather feedback to confirm that the application meets the client’s needs.

## What do computer scientists do, and why does it matter?

Computer scientists analyze problems and develop solutions that help people work with information more effectively. Their work involves understanding user needs, organizing data, designing software, and testing whether a solution produces useful and reliable results.

For a company like Grazioso Salvare, a dashboard can reduce the time spent manually searching animal shelter records. Users can filter dogs based on rescue requirements and review the matching records through a table and visualizations. This helps the organization identify potential candidates for further evaluation and spend more time on its rescue and training mission. This project showed me how database and software development skills can support an organization’s everyday decisions.
