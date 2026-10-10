# Thread Tribe Sales

Phone-first app for Thread Tribe's sales team: leads, calls, visits and follow-ups across three
channels (toys, lighting, HoReCa & gifting), existing accounts, and the trade catalogue.

- Sign-in: email code (Supabase Auth). Only people Studio lists under Sales → Team get in.
- Data: `sales_reps`, `sales_leads`, `sales_activities`, `sales_pack` (see `sales_setup.sql`).
- Studio (TT-Master-App) manages the team and targets and publishes the sales pack.
