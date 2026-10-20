# Second Bloom
Run: `npm install && ADMIN_PASSWORD=yourpass PORT=3000 node server.js` → http://localhost:3000 (admin at /admin; set ADMIN_PASSWORD env var).
Data: data/shop.db (SQLite via sql.js). Uploads: public/uploads. Delete data/shop.db to reset to sample data.
Stripe: see `// STRIPE:` comments in server.js (/checkout route).
