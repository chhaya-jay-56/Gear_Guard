GEARGUARD MYSQL – FIXED VERSION

1. Import schema:
mysql -u root -p gear_guard_db < backend/database/schema.sql

2. Install deps:
npm install express mysql2 cors

3. Run:
node backend/server.js
