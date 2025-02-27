# Jobland - Job Portal Website

Jobland is a job portal web application where users can browse available jobs and post new job opportunities. With functionalities like applying for jobs, saving jobs, and checking the hiring status, Jobland makes it easy for users to navigate the job market efficiently.

## Features

- **Browse Jobs**: Search for jobs based on various criteria like job title, company, location, etc.
- **Post Jobs**: Employers can post job opportunities with detailed descriptions.
- **Apply for Jobs**: Users can apply to listed jobs directly from the platform.
- **Save Jobs**: Option to save jobs for future reference.
- **Hiring Status**: View whether the job's hiring status is open or closed.
- **User Authentication**: Secure authentication using Clerk for both job seekers and employers.

## Tech Stack

- **Frontend**: Built with React for a dynamic and responsive user experience.
- **Styling**: Tailwind CSS for modern and customizable styles, and Shadcn for reusable UI components.
- **Backend**: Supabase for managing database operations and real-time features.
- **Authentication**: Clerk for secure and easy-to-manage user authentication.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Node.js installed (v14 or later)
- Supabase account
- Clerk account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Neeraj-Fulpatiya/jobLand.git

2. Navigate to the project directory:
   cd jobLand

3. Install the dependencies:
   ```bash
   npm install
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```bash
     REACT_APP_SUPABASE_URL=your_supabase_url
     REACT_APP_SUPABASE_KEY=your_supabase_key
     REACT_APP_CLERK_FRONTEND_API=your_clerk_frontend_api
     ```
5. Start the development server:
   ```bash
   npm run dev
## Usage

- **For Job Seekers**: Browse jobs, apply directly, and save the ones you like.
- **For Employers**: Post job listings and manage job applications.

## Contributing

We are actively seeking contributions to improve Jobland, and we welcome developers of all skill levels to help make the platform better!

### Current Issue: Onboarding Component

We have identified an issue with the onboarding process, where users are directly taken to the job posting page without properly distinguishing their role (e.g., job seeker or employer). This is a crucial step that needs fixing, and your help would be appreciated.

### What Needs to Be Done:
- The onboarding component should correctly route users based on their role type (job seeker or employer) after login/signup.
- If you can help debug and solve this issue, feel free to contribute by opening a pull request.

### How to Contribute:

1. Fork the repository and clone it to your local machine:
   ```bash
   git clone https://github.com/Neeraj-Fulpatiya/jobLand.git
2. Create a branch for your feature or bug fix:
   bash
     git checkout -b fix-onboarding-component
3. Make your changes, commit them, and push to your forked repository:
   ```bash
   git add .
   git commit -m "Fix onboarding component routing issue"
   git push origin fix-onboarding-component
4. Submit a Pull Request to the main repository, explaining your fix and how it resolves the issue.

# Guidelines

- Please ensure your code follows the existing code style.
- Test your changes thoroughly.
- Include comments where necessary to make the code understandable.
- If you're new to open-source, feel free to ask questions. We are here to help!
  
Awesome Project

## Need Help? 

If you need further clarification or encounter issues while setting up, feel free to reach out via [techpro.neeraj@gmail.com](mailto:techpro.neeraj@gmail.com).
   



