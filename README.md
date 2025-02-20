# Podcastr
This project aims to create a sophisticated Software-as-a-Service (SaaS) platform that
integrates AI-powered tools to enhance content creation and management. Leveraging
React js for its robust framework and Convex for real-time data management, the
application provides users with a unique experience in generating and managing
multimedia content. The key features include a text-to-multiple-voices functionality, which
enables users to convert written content into diverse voice outputs, offering a rich and
customizable audio experience. Additionally, the platform incorporates AI-generated
images, allowing users to create visually appealing content effortlessly. The app also
integrates Clerk for secure and streamlined user authentication, ensuring a seamless user
experience. With OpenAI's powerful algorithms, the platform provides advanced AI
capabilities, including intelligent podcast generation and dynamic content creation.
The project emphasizes scalability, user-friendly design, and cutting-edge AI
integrations, making it a versatile tool for content creators, podcasters, and businesses
looking to automate and elevate their multimedia production processes. The comprehensive
setup, detailed in the provided resources, ensures that users can efficiently build, manage,
and deploy their content, making this SaaS app a valuable asset in the digital content
creation landscape
## 📌 Cloning the Repository
To get started, clone this repository to your local machine:
```bash
git clone https://github.com/DNSAryan/PodcastStreamer.git

Install the required dependencies using npm:

npm install

Create a new file named .env in the root of your project and add the following content:

CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the Convex and Clerk websites.
Running the Project
To start the development server, run:
npm run dev
Open https://podcastrteam6.vercel.app/ in your browser to view the project.