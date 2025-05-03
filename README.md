**Task (GHA-S-1): Reusable Terraform Workflow**
*   **Use Case:** 
Create a reusable GitHub Actions workflow (`workflow_call`) that can execute Terraform `plan` or `apply`. The calling workflow should be able to pass the command (`plan`/`apply`), the working directory, and cloud credentials (e.g., via OIDC/WIF). Demonstrate its use in a simple caller workflow.

*   **Verification:** 
Is the workflow reusable? Are parameters passed and used correctly? Is authentication secure (WIF preferred)?
*   **Solution:** 
Place in: `/Senior/GHA-S-1/solution_reusable_workflow.yml`, `/Senior/GHA-S-1/solution_caller_workflow.yml`
