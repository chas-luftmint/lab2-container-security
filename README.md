# lab2-container-security
Lab 2 Container Security

Vad jag har gjort:
Installerat Trivy och skapat en sårbar och en hardened Dockerfile för en enkel flask.py app. 
Kört trivy scans på sårbara docker imagen och den som var säkrare.
Genererat SBOM
Använt Gatekeeper med kubernetes, och skrivit yaml filer för policies i repot.

Trivy before hardening;
[!(screenshots/trivy-before.png)]

Trivy after hardening;
[!(screenshots/trivy-after.png)]

Gatekeeper Deny
[!(gatekeeper-deny.png)]

Gatekeepr Pass
[!(gatekeeper-pass.png)]

