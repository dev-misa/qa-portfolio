## TC-0002: Settings modal shows sharp corner artifacts behind rounded edges when active

Preconditions: Squidd is launched and the Settings modal can be opened

Steps:
1. Launch Squidd
2. Open the Settings modal by clicking the Squidd logo in the pill
3. Keep the modal active/focused
4. Observe the rounded corners of the modal

Expected Result: The Settings modal renders with clean corners and no visible discrepancies. 

Actual Result: When the Settings modal is active, faint sharp artifacts appear behind the rounded edges, making the corners look like a square or unmasked layer is visible

Status: Fail
Severity: low