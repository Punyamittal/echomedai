# EchoMedAi

## Setting Up the AI Assistant

EchoMedAi includes an AI chatbot powered by Google's Gemini API. To make the AI assistant work properly, you need to obtain and configure a Gemini API key.

### Getting a Gemini API Key

1. Visit the [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy the API key

### Configuring the API Key

1. Create a `.env.local` file in the root directory of the project (if it doesn't exist already)
2. Add your Gemini API key to the file:
   ```
   NEXT_PUBLIC_GEMINI_API_KEY=YOUR_API_KEY_HERE
   ```
3. Restart your development server if it's already running

### Important Notes

- Keep your API key secure and never commit it to version control
- The free tier of Gemini API has usage limits, so be aware of potential rate limiting
- If you encounter the error "I'm sorry, I encountered an error processing your request. Please try again later." it likely means your API key is not configured correctly

## Development

To run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
‣捥潨敭慤൩�