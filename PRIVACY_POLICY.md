# Privacy Policy for KarmaQuest (v2026.4)

Effective Date: April 1, 2026

## 1. Introduction
KarmaQuest ("we," "us," or "our") is committed to protecting your privacy. This Privacy Policy explains how we handle your data within the KarmaQuest wellness application, specifically regarding our NPU-first architecture and biometric verification systems.

## 2. On-Device AI & NPU Processing
**KarmaQuest utilizes 100% on-device Artificial Intelligence.** 
- All "Vibe Checks," image labeling, and habit verification are performed locally on your device's Neural Processing Unit (NPU).
- **Zero Data Transmission:** No images, videos, or raw health data are ever transmitted to external AI providers or cloud servers for analysis.
- This architectural choice ensures that your most sensitive wellness media remains within your device's secure enclave.

## 3. Human Binding (KYA) & Biometrics
To maintain the integrity of the Universal Commerce Protocol (UCP), we utilize a framework called **Know Your Agent (KYA)**.
- KYA cryptographically binds your device's 3D biometric identifier to your quest completions.
- We utilize standard system APIs (FaceID/TouchID) to perform this binding.
- **We do not store or access your raw biometric data.** We only receive a cryptographic confirmation from the secure enclave that the "Human Participant" is verified.

## 4. Health Data Synchronization
KarmaQuest requests access to your device's health data (e.g., Apple HealthKit) to synchronize movement quests (steps, activity).
- This data is read locally to verify quest completion. 
- Aggregated health metrics are used solely to visualize your "Aura" and are never sold to third parties.

## 5. Third-Party Services
While our AI is local, we participate in the **Universal Commerce Protocol (UCP)** for reward redemption.
- When you negotiate a reward with a merchant, your Karma balance and a "Human-Bound Signature" are shared with the merchant to authorize the transaction.
- Each merchant has their own privacy policy; please review the metadata at their `/.well-known/ucp` domain.

## 6. Data Deletion
You can reset all app data and delete your local streak history at any time via the "Aura Settings" in the app. This will immediately purge all local records and cached quest completions.

## 7. Contact Us
For questions regarding our 2026 Privacy Framework, please contact the KarmaQuest team at privacy@karmaquest.example.
