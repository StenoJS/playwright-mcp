# playwright-mcp

Portainer-stack `playwright-mcp` (id 10, endpoint "primary") — Bol.com en
Amazon Playwright MCP-servers met noVNC, voor visueel inloggen zonder
wachtwoord op het LAN/Tailnet.

Gemigreerd van file-based Portainer-deployment naar Git-gebaseerde deployment
(`docker-compose.yml` in dit repo, gepushed via GitOps-redeploy in Portainer)
zodat wijzigingen voortaan traceerbaar en terug te draaien zijn. Zie de
comments bovenaan `docker-compose.yml` voor de volledige uitleg van de
werking (noVNC-poorten, profiel-persistentie, stale-lock cleanup, etc.).

Geen geheimen in deze stack.
