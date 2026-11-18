MAKORA — EARLY ACCESS MVP

Included:
- Responsive dark/purple marketplace interface
- Supabase email/password sign-up and sign-in
- Profile create/update
- Browse/search active services
- Create a service listing
- Create and view project requests
- Basic installable PWA shell

IMPORTANT LIMITATIONS:
This is an early-access MVP, not a production-ready marketplace.
It does NOT include chat, payments, file uploads, reviews, dispute handling,
moderation, admin tools, notifications, or full order management.
Do not collect payment details or sensitive personal information through it.
Before inviting the public, arrange adult/guardian support and a security/privacy
review. Payment and business services have age and legal requirements.

SETUP:
1. In Supabase SQL Editor, run the full contents of schema.sql.
2. Confirm the project URL and publishable key in app.js are correct.
3. Upload all files in this folder to the root of a static HTTPS host.
4. In Supabase > Authentication > URL Configuration, set Site URL to the
   exact deployed website URL and add that URL to Redirect URLs.
5. In Supabase > Authentication > Providers > Email, choose whether email
   confirmation is enabled. If enabled, test the confirmation link.
6. Test sign-up, sign-in, profile save, service publish, and project request.

SECURITY:
The publishable key is intended for browser use. Never add a service_role key,
database password, or other secret to app.js or a public GitHub repository.
Keep RLS enabled. Review the policies before production use.
