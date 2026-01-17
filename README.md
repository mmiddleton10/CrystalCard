CrystalCard Walkthrough
CrystalCard is a decentralized, offline-first digital contact card built with Next.js 15 and Tailwind CSS v4.

Features
1. Creator View (Admin)
Profile Editing: Edit name, title, bio, contacts, and social links.
Local Photo Upload: Client-side compression (max 500x500px) and Base64 conversion.
Privacy: All data is stored in localStorage. No database required.
2. Recipient View (Public)
Glassmorphism Design: Premium visual style with dynamic gradients and frosted glass effects.
Save to Contacts: One-click download of a standard vCard 4.0 (.vcf) file with embedded photo.
Web Share API: Native sharing sheet on supported mobile devices.
3. "Ask the Business" AI Assistant
Gemini Powered: Uses Google Gemini 1.5 Flash to answer questions about the business.
Guardrails: Strictly answers based on context. Refuses general queries (poems, code, etc.).

How to Run:

Navigate to the project directory:
cd CrystalCard

Start the development server:
npm run dev

Open http://localhost:3000 in any explorer/browser

Usage Notes:
API Key: For the AI Assistant to work, you must enter a valid Google Gemini API Key in the Creator View. This key is stored locally on your device.
