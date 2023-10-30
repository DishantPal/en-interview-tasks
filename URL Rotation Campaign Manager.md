**Project Description: URL Rotation Campaign Manager**

---

**Introduction:**
Welcome to the URL Rotation Campaign Manager task! In this practical exercise, you will be designing and implementing a MERN (MongoDB, Express, React, Node.js) stack application that allows users to create campaigns, add multiple offer URLs, and track statistics based on various parameters.

**Task Overview:**
Your task is to design the database structure, develop the necessary APIs for the backend, and implement secure authentication and authorization. Below are the key functionalities you'll need to implement:

1. **Campaign Creation:**
   - Users can create campaigns with a unique name.

2. **Offer Management:**
   - Within each campaign, users can add multiple offer URLs.
   
3. **URL Rotation:**
   - After creating a campaign, the app generates a unique campaign URL.
   - Upon visiting this campaign URL, the app will randomly redirect users to one of the offer URLs based on rotation percentages set for each offer.

4. **Statistics:**
   - Users should be able to view detailed statistics for a specific campaign.
   - The statistics should include:
     - Total clicks in a month, a week, and overall.
     - Clicks based on:
       - Country
       - Device
       - IP address
     - Click count for a particular date, week day, month, and year.

5. **Authentication and Authorization:**
   - Implement user authentication to secure the application.
   - Ensure proper authorization to restrict access to certain functionalities.

6. **Export Data:**
   - Users should have the option to export the statistics data in a CSV file format.

**Example Scenario:**
For instance, if a user creates a campaign "Campaign A" with three offers (X, Y, Z) and sets the rotation percentages as specified (X: 30%, Y: 50%, Z: 20%), the app will redirect users accordingly.

**Deliverables:**
1. **Database Structure:**
   - Design the MongoDB schema to store campaign, offer, and click data.

2. **API Endpoints:**
   - Implement the necessary APIs for creating campaigns, managing offers, generating campaign URLs, tracking clicks, user authentication, and authorization.

**Submission:**
Please provide the following:
- A link to your Git repository containing the code.
- A brief documentation explaining how to set up and run the application, including instructions for API usage and authentication.

**Evaluation Criteria:**
- Database schema design and data modeling.
- Functionality implementation (campaign creation, offer management, URL rotation, statistics tracking, authentication, authorization).
- Code quality, structure, and modularity.

Feel free to reach out if you have any questions. Good luck, and happy coding!