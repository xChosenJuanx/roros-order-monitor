# Roro's Order Monitor
Lightweight Android monitor for the existing Roro's Cravings Firebase backend.

- Read-only Pending Orders display
- Real-time Firestore updates
- Loud in-app alert + vibration for new Pending orders
- Screen stays awake while app is open
- Same admin email/password as the main Roro's Cravings app
- Separate package: com.roroscravings.ordermonitor

## Build
Push this source to a GitHub repository. Open Actions > Build Roro's Order Monitor APK > Run workflow. Download the Roros-Order-Monitor-APK artifact.

Note: The workflow creates an unsigned release APK. For direct installation, add signing or build a debug APK. If reusing the existing Roro's Cravings repository secrets, copy the signing step from the main app workflow and use a distinct output filename.
