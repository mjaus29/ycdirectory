# YC Directory

<div align="center">
  <img src="https://www.markaustria.com/ycdirectory.png" alt="YC Directory" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)

</div>

## 🌐 Live Site

🚀 Here is a working live site: [ycdirectory.markaustria.com](https://ycdirectory.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/ycdirectory](https://www.markaustria.com/ycdirectory)

## 📝 Description

Welcome to YC Directory! A modern full-stack Next.js application designed as a pitching platform for users to share and discover startup ideas.

YC Directory allows users to create, share, and discover startup ideas with real-time updates. The application features GitHub authentication, content management via Sanity, and implements advanced rendering strategies like Partial Pre-Rendering (PPR).

This application solves the challenge of creating a responsive platform with proper authentication flow, real-time content updates, and optimized rendering strategies while maintaining excellent performance and SEO benefits.

**Technologies Used**: Next.js, React, TypeScript, Tailwind CSS, Shadcn UI, NextAuth, Sanity, Sentry, Zod

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Partial Pre-Rendering Implementation**: Combines static and dynamic rendering within the same page. Static content like startup details are cached while dynamic elements like view counters are rendered server-side in real-time.

- **Real-Time Content Updates**: Integrated Sanity's live content API to deliver real-time updates without page refreshes. When users submit new startups, they appear instantly on the homepage for all users.

- **Advanced Form Handling with React**: Leveraged React's new useActionState hook and Next.js server actions to create a robust form submission system with built-in validation using Zod.

- **GitHub Authentication**: Implemented custom callbacks in the NextAuth configuration to create or fetch Sanity author documents upon successful GitHub authentication.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)
- [Sanity CLI](https://www.sanity.io/docs/getting-started-with-sanity-cli) (optional, for content management)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/ycdirectory.git
   ```

2. Navigate into the project directory

   ```bash
   cd ycdirectory
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   - Create a .env.local file in the root directory with the following variables:

   ```
   AUTH_SECRET="your_auth_secret"
   AUTH_GITHUB_ID="your_github_oauth_id"
   AUTH_GITHUB_SECRET="your_github_oauth_secret"
   NEXT_PUBLIC_SANITY_DATASET="production"
   NEXT_PUBLIC_SANITY_PROJECT_ID="your_sanity_project_id"
   NEXT_PUBLIC_SANITY_API_VERSION="your_sanity_api_version"
   SANITY_WRITE_TOKEN="your_sanity_write_token"
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to see the project running.

7. Test the application

   Run the test suite to ensure everything is working as expected.

   ```bash
   npm test
   ```

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/ycdirectory/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/ycdirectory/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] Implement form field persistence when validation fails to improve user experience
- [ ] Add commenting and voting functionality for startup pitches
- [ ] Integrate email notifications for new startup submissions
- [ ] Implement advanced analytics to track user engagement and startup popularity

### 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)

</div>
