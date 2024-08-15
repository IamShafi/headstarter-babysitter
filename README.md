
# headstarter-babysitter 🤖

**The ultimate companion to hold the hand of novice Headstarter AI fellows!**

Welcome to **headstarter-babysitter**, a powerful RAG (Retrieval-Augmented Generation) LangChain chatbot designed to help new fellows learn about the Headstarter AI company. 
Built with cutting-edge technologies, this chatbot provides an interactive, engaging, and informative experience, making it easier for newcomers to get up to speed.

## Features 🚀

- **Interactive Chatbot:** Get real-time answers to questions about Headstarter AI.
- **RAG LangChain Integration:** Combines retrieval and generation to provide accurate and relevant information.
- **Modern Frontend:** Built using Next.js, TailwindCSS, and shadcn for a sleek and responsive UI.
- **Seamless Backend:** Powered by Drizzle ORM and PostgreSQL for robust data handling.
- **Enhanced User Experience:** Leveraging Framer Motion for animations and React Hook Form with Zod for form validations.
- **Authentication:** Managed by Clerk for secure and easy user authentication.
- **Deployed on Vercel:** Ensuring fast and reliable hosting with Vercel AI SDK integration.
- **Pinecone Integration:** Efficiently handles vector embeddings for better search and retrieval.
- **OpenAI API & Mistral:** Supports advanced AI responses and interactions.

## Tech Stack 🛠️

- **Frontend:** [Next.js](https://nextjs.org/), [TailwindCSS](https://tailwindcss.com/), [shadcn](https://shadcn.dev/), [Framer Motion](https://www.framer.com/motion/), [React Hook Form](https://react-hook-form.com/), [Zod](https://zod.dev/)
- **Backend:** [Drizzle ORM](https://drizzle-orm.dev/), [PostgreSQL](https://www.postgresql.org/), [Vercel AI SDK](https://vercel.com/docs/ai/vercel-ai-sdk)
- **AI & NLP:** [OpenAI API](https://openai.com/), [Pinecone](https://www.pinecone.io/), `"@ai-sdk/mistral"`
- **Authentication:** [Clerk](https://clerk.dev/)

## Getting Started 🏁

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/headstarter-babysitter.git
   cd headstarter-babysitter
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root directory and add your environment variables:

   ```env
   NEXT_PUBLIC_OPENAI_API_KEY=your-openai-api-key
   DATABASE_URL=your-database-url
   CLERK_API_KEY=your-clerk-api-key
   PINECONE_API_KEY=your-pinecone-api-key
   ```

4. **Run database migrations:**

   ```bash
   npx drizzle migrate
   ```

5. **Start the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Your application should now be running on [http://localhost:3000](http://localhost:3000).

## Usage 📖

Simply navigate to the running application and interact with the chatbot to learn about Headstarter AI. The bot uses a combination of retrieval-based information and AI-generated responses to provide accurate and relevant answers.

## Contributing 🤝

Contributions are welcome! Please open an issue or submit a pull request if you'd like to contribute.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- **Headstarter AI:** For providing an inspiring environment for AI learning and development.
- **OpenAI:** For the powerful language models that power this chatbot.
- **The Open Source Community:** For the amazing tools and frameworks that made this project possible.

---
