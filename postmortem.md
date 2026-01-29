
Incident Summary:
Application failed after buggy code was deployed.

Root Cause:
Undefined variable added in app.py.

Impact:
Application unavailable.

Detection:
Jenkins pipeline failed during deployment.

Resolution:
Rolled back to previous stable Git commit.

Lessons Learned:
Always test before pushing.

Preventive Actions:
Add unit testing stage in Jenkins pipeline.
