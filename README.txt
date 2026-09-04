Senthoor Murugan Finance - Vercel/PWA build

Upload all files in this folder to your GitHub repository, then import the repository into Vercel.

Important:
- With Supabase configured, login must use the Supabase Auth owner email/password. The old admin/0000 local fallback is only used when Supabase is not configured.
- Login session survives refresh/reopen through Supabase Auth.
- The last app page is restored after refresh; it does not force the dashboard.
- Supabase Realtime sync remains enabled.
