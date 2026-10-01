# CareerHub

Apple-inspired career and certification workspace built with Next.js, TypeScript, Tailwind CSS, and Supabase-ready authentication.

## Run locally

1. Install Node.js 20+.
2. Copy `.env.example` to `.env.local`.
3. Add your Supabase project URL and anon key if you want real cloud authentication.
4. Run `npm install` then `npm run dev`.

Without Supabase variables, the app automatically runs in local demo mode using browser storage, which is useful for UI testing.

## Deploy to Vercel

Push this folder to GitHub, import the repository into Vercel, add the two `NEXT_PUBLIC_SUPABASE_*` environment variables, and deploy.

## Supabase next steps

Enable Email auth in Supabase. For production data persistence, create tables for profiles, certifications, applications, resumes, skills, goals, and documents, with Row Level Security policies tied to `auth.uid()`. Configure Supabase Storage for certificate/document uploads.
