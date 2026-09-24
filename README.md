# CodeGuard AI – Firebase Integration

This directory contains Firebase configuration, security rules, and Firestore index specifications.

## Planned Structure & Usage
- **Firestore Collections**:
  - `reviews`: Stores structured review reports, PR metadata, risk scores, score breakdowns, findings, and email dispatch status.
- **Security Rules (`firestore.rules`)**: Enforces secure read/write rules ensuring PR audit data integrity.
- **Service Account Credentials**:
  - Placeholder for optional `serviceAccountKey.json` for elevated server-side Firestore operations.
- **Local Fallback**:
  - CodeGuard AI supports a seamless local JSON storage fallback when Firebase credentials are not yet provisioned.
