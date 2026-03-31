# NyayaSaathi - Legal Aid Platform

NyayaSaathi is an AI-powered legal aid platform for first-generation litigants in India. It aims to bridge the justice gap by providing plain language legal rights, a document checklist, procedure guides, an AI document generator, and a searchable lawyer directory.

## Technology Stack
- **Frontend**: Next.js 14, React, Tailwind CSS, Framer Motion, TypeScript.
- **Backend (API)**: Node.js, Express, MongoDB Atlas, OpenAI API.
- **i18n**: Bilingual (Hindi and English) switching using `i18next` and `react-i18next`.
- **Document Generation**: PDF generation with Hindi support via `jsPDF`.

## How It Works
1. **Legal Situation Selector**: The user can select from a predefined set of categorized life events like dealing with landlord disputes, filing an FIR, etc.
2. **Bilingual Explainer:** We display plain-language translations of their rights created via AI, side-by-side with the original law sourced from IndiaCode.
3. **Step-by-step Procedure & Checklist**: Users are given a progress-tracking checklist and detailed procedure to follow.
4. **Lawyer Directory**: An interactive directory of legal aid lawyers with various practice areas offering Pro Bono help.
5. **Document Template Generator**: Users can input personal and event details to dynamically generate PDFs (like an RTI or a Consumer Complaint), complete with legal formatting.

## Local Setup

### 1. Backend Setup
1. Navigate to the \`backend\` directory: \`cd backend\`
2. Install dependencies: \`npm install\`
3. Set your environment variables (see \`backend/.env\`):
   - \`PORT\`
   - \`MONGODB_URI\`
   - \`OPENAI_API_KEY\`
   - \`FRONTEND_URL\`
4. Run the backend server: \`npm run dev\`

### 2. Frontend Setup
1. Navigate to the \`frontend\` directory: \`cd frontend\`
2. Install dependencies: \`npm install\`
3. Set up the environment file (\`frontend/.env.local\`) containing:
   - \`NEXT_PUBLIC_BACKEND_URL=http://localhost:5000\`
   - \`NEXT_PUBLIC_APP_URL=http://localhost:3000\`
4. Run the frontend development server: \`npm run dev\`

### Open in Browser
Visit [http://localhost:3000](http://localhost:3000) to view the application.

## Acknowledgements
Designed with ❤️ as a Hackathon Project.
