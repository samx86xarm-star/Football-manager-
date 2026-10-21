# Football Manager Android project

This is an early offline Android game prototype.

## Build without owning a PC (using your Android phone)
You can use GitHub's cloud build through the phone browser:
1. Sign in or create an account at https://github.com.
2. Create a new repository named `football-manager` and set it to Private or Public.
3. Upload the contents of this project ZIP to the repository (extract the ZIP first if your phone's file manager supports it; the `.github/workflows/build-apk.yml` file must be included at the repository root).
4. Open the repository's **Actions** tab and enable Actions if asked.
5. Choose **Build Football Manager APK** and tap **Run workflow** (or push to `main`).
6. When the workflow finishes successfully, open that run, scroll to **Artifacts**, and download `football-manager-apk`.
7. Extract the downloaded artifact ZIP to get `app-debug.apk`, then tap the APK to install. Android may ask you to allow installs from your browser or file manager.

## Prototype features
- Club dashboard and next fixture
- Simulated match results and club budget
- Squad roster with ratings
- Formation selection (4-3-3, 4-4-2, 3-5-2, 4-2-3-1)
- Training sessions that affect morale/player ratings
- Dark green, neon gaming-inspired interface

## Important
- This is not a full 3D football simulator.
- Matches are simulated and the prototype has no licensed real clubs/players or online features.
- Package ID: `com.example.footballmanager`
