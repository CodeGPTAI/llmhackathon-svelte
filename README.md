# Create an App with the Mistral API and Code GPT

### This project implements a chat application using the Mistral API and CodeGPT, developed with Svelte.
Developed by [@GustavoEspindola – CodeGPT](https://www.linkedin.com/in/gustavoespindola/)

<!-- add an image -->
<img src="https://raw.githubusercontent.com/gustavoespindola/llmhackathon/refs/heads/master/static/hackathon.gif" alt="llmhackathon" width="100%">

## Prerequisites

To use this application you will need:

### Project Introduction
- Request the [Mistral API KEY](https://console.mistral.ai/api-keys/)
- Test: Request the models with an API call using a .http file in [Mistral Endpoints](https://docs.mistral.ai/api/#tag/models)
- Create an interaction with the model using the chat application in Svelte
### Advanced Agents
- Create an AI Agent with CodeGPT
- Load the information to the agent
- Get the agent ID
- Get the CodeGPT API key
- Create an interaction with the agent using the chat application in Svelte

### Useful Links

- [🎯 LLMHackathon](https://llmhackathon.dev/)
- [🔑 Mistral API Documentation](https://console.mistral.ai/api-keys/)
- [🎯 Mistral Endpoints](https://docs.mistral.ai/api/#tag/models)
- [📚 Vercel AI SDK](https://sdk.vercel.ai/)
- [🚀 CodeGPT Registration](app.codegpt.co/r/gustavo)
- [📖 CodeGPT Documentation](https://app.codegpt.co/en/apikeys)
- [📖 CodeGPT Documentation](https://developers.codegpt.co/reference/completion-beta)
- [🌐 Vercel Platform](https://vercel.com/)
- [🔐 OpenAI API](https://platform.openai.com/api-keys)

---

## Installation and Configuration

**Clone the repository**

`git clone https://github.com/gustavoespindola/llmhackathon`

**Enter the project folder**

`cd llmhackathon`

**Install dependencies**
Everything you need to create a Svelte project, with the technology of [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).
Once you have created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`)

`npm install`

**Start the development server**

```bash
npm run dev

# or to open automatically in the browser:
npm run dev -- --open
```

```bash
  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```

The application will be available at `http://localhost:5173/`

## Production Deployment

Build Preparation

**Create production version**
```bash
npm run build
npm run preview
``

For deployment, you may need to install an adapter for the specific environment.

**Deployment on Vercel**

Create an account on Vercel
Create a new project
Link with the repository
Configure environment variables
Execute the deployment

**Mas información sobre Vercel**
[Deploy Tutorial](https://vercel.com/docs/deployments/overview)
