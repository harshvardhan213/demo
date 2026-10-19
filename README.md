# demo

Target repo for the Bravebird automation take-home.

The **Generate report** workflow (Actions tab → Generate report → Run workflow) renders a PDF from its inputs and uploads it as an artifact.

- `main` branch: `report_type` (invoice / statement / summary), `month`, `customer`
- `v2` branch: `report_type` (quarterly / audit / tax), `month`, `customer`, `region`

Switching the branch in the Run workflow form changes which fields and options appear — that is the dependent field the automation handles.
