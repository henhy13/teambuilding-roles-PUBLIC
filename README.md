# Team Role Assignment System

Made for teambuilding.tw, for use during minigames.
This application is a web-based system for assigning roles to team members based on their skills, experience, and personality traits. It uses AI-powered assignment for optimal team composition.
  
## INSTRUCTIONS 

### As an Admin
1. **Login**:
   - From the header or /admin page
   - Enter the admin password set in .env

2. **Manage Sessions**:
   - Create new sessions
   - Generate session codes
   - Monitor applicants

3. **Manage Teams**:
   - Create teams within sessions
   - Role assignment automatically triggered
   - View detailed results
  
### As a User
1. **Join a Session**:
   - Visit the home page
   - Enter the 6-character session code provided by the admin
   - Click "Join Meeting"

2. **Join a Team**:
   - Once in the session, you'll see available teams
   - Select a team and click "Join"
   - Fill in your details:
     - Name
     - Occupation
     - Years/Months of experience
     - Up to 5 skills (each <=30 characters)
     - Up to 5 personality traits (each <=40 characters)
   - Submit to apply

3. **View Results**:
   - When the team is full and assignment is complete
   - Go to Results page
   - View assigned roles, justifications, and scores

**Privacy Policy**

This project does not collect, store, or share any personal data.

- We do not track users.
- We do not sell or share data with third parties.

All user interactions remain local or session-based, and no personal information is stored beyond what is strictly necessary for the functionality of the app (e.g., session or team data in memory).

This software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement.

By using this project, you acknowledge and agree that:

No personally identifiable information (PII) is collected.

You are responsible for ensuring your own compliance with local data protection laws if you deploy or modify this project for use in a broader context (e.g., production environments).

If you have any questions or concerns regarding privacy, please contact the project maintainer directly.
