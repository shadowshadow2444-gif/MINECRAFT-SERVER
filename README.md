# Minecraft Railway Panel — 1 Server Limit

Deploy to Railway. Set:
ADMIN_USERNAME
ADMIN_PASSWORD
SESSION_SECRET
PORT=3000

This build enforces a single-server limit in the panel UI/API.
It does not bypass Railway's CPU/RAM/storage limits; the Minecraft process can use resources available to its Railway service.
