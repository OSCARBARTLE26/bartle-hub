# Bartle Home

The family hub for the kitchen iPad and Becky's phone: who's where, the family calendar, Bertie's feeds and walks, dinner, the shopping list, and Becky's own pages (fitness, trips, house jobs, recipes).

- Hosted with GitHub Pages. Data lives in Supabase, behind one family login.
- `config.js` holds the Supabase project URL and anon (publishable) key. The anon key is meant to be public; the database only lets the signed-in family login read or change anything.
- Never put the Supabase service_role / secret key in this repo.
