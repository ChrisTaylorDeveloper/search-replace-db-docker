# Search Replace DB Docker

See <https://github.com/interconnectit/Search-Replace-DB>

---

Example of using interconnectit Search-Replace-DB utility to a Docker Compose project.

1. Download / extract the Search-Replace-DB project.
1. Add the `sr` service in `compose.yaml` to your Compose project.
1. Run Search-Replace-DB in a browser: `http://localhost:<port for sr service>`
1. Run Search-Replace-DB from the command line `docker compose exec sr php srdb.cli.php --help`
