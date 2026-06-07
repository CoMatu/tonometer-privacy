### Privacy Policy for the Comatu Mahjong App

**Last updated:** May 16, 2026

**Comatu Mahjong** (the “App”) is a mobile Mahjong solitaire game. The developer respects your privacy. This policy describes what data is processed in the App, where it is stored, and which third-party services are used.

#### 1. Developer

The App is distributed by **Vyacheslav Matusevich** (Android package: `ru.matusevichvv.comatu_mahjong`). For privacy-related questions: **matu1@mail.ru**.

#### 2. What Data the Developer Collects

The developer **does not maintain user accounts**, **does not request** your name, email address, phone number, or other personal data, and **does not send** information about you to its own servers.

The App **does not include** built-in developer analytics (Google Analytics, Firebase Analytics, etc.).

#### 3. Data Stored Only on Your Device

To run the game, the App saves **game and settings data** on your device that is not intended to identify you personally:

| Data | Purpose | Storage |
|------|---------|---------|
| Game progress (difficulty, stage, score, time, board layout) | Resuming an unfinished game | Local SQLite database |
| Total accumulated score | Displaying results | Local SQLite database |
| Number of hints | Game mechanics | Local SQLite database |
| Sound on/off | Settings | Local storage (SharedPreferences) |
| App version and build number | Display in settings | Read from the device (not sent to the developer) |

This data **is not synced** to the developer’s cloud. If you uninstall the App or reset your device data, it may be **permanently lost**. The developer is not responsible for such loss.

#### 4. Advertising (Third-Party Service)

When ads are enabled, the App uses **Yandex Mobile Ads** (SDK `yandex_mobileads`):

- **banner** ads during gameplay;
- **rewarded** ads — at your choice, to receive hints or shuffle the board.

To display and measure ads, the SDK connects to **Yandex LLC** servers and may process, among other things: device and advertising identifiers, technical device and OS parameters, and data about ad impressions and interactions. The scope and purposes of processing are defined by Yandex policies, not by the App developer.

Current Yandex documents:

- [Yandex Privacy Policy](https://yandex.ru/legal/confidential/)
- [Yandex Mobile Ads SDK Terms of Use](https://yandex.ru/legal/mobileads_sdk_agreement/)

**Debug** builds may show **demo** Yandex ads.

Ads can be disabled only in special builds where the `ADS_ENABLED=false` parameter is set at build time (for example, internal dev builds); in the regular user version, ads are enabled.

#### 5. Network and Permissions

- **Internet** access is required to load ads and run the ad SDK (on Android, the `INTERNET` permission may be added together with SDK dependencies).
- The App **does not request** access to the camera, microphone, contacts, calendar, user files, **geolocation**, or other sensitive permissions for its game logic.

#### 6. Children

The App is not intended to knowingly collect personal data from children. Parents and guardians are advised to supervise children’s use of the App, including viewing ads.

#### 7. Security

Game data remains on your device. The developer does not have remote access to it. Data sharing with third parties by the developer is limited to the cases described in the advertising section (processing by Yandex when ads are shown).

#### 8. Changes to This Policy

The developer may update this policy. The current version is published in the repository/app store together with updates. The date of the last change is shown at the top of this document.

#### 9. Contact

For privacy-related questions: **matu1@mail.ru**.

**Thank you for playing Comatu Mahjong!**
