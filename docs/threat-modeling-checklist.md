# Threat Modeling Quick Checklist

- [ ] Identify assets and their value
- [ ] Map data flows and trust boundaries
- [ ] Enumerate entry points (APIs, UI, auth)
- [ ] Consider STRIDE per component
- [ ] Check for default creds / hardcoded secrets
- [ ] Review authz: least privilege, IDOR
- [ ] Validate input: injection, path traversal
- [ ] Log sensitive actions, avoid PII
- [ ] Update threat model after each feature