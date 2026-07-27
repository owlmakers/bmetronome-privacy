# Privacy Policy — Bmetronome

_Last updated: 2026-07-28_

Bmetronome ("the app") is an offline metronome and tuner built by
**Owlmakers**. This policy explains what data the app handles and
where.

---

## 한국어

### 1. 수집·처리하는 데이터

| 데이터 | 처리 방식 | 외부 전송 |
| --- | --- | --- |
| 마이크 입력 (튜너) | 음정 분석을 위해 *기기 내에서만* 처리. 오디오 자체는 저장·전송 X. | **없음** |
| 메트로놈 설정 (BPM, 박자, 분할, 테마, 언어) | `shared_preferences`로 *기기 로컬*에만 저장. | **없음** |
| 광고 식별자 (Android Advertising ID) + 기기/앱 사용 정보 | Google AdMob 광고 송출용. | **Google에 전송** |
| 앱 이용 통계 (화면 조회, 실행·세션 횟수) | Google Analytics for Firebase가 앱 인스턴스 ID와 함께 기록. 서비스 이용 현황 분석용이며 *신원과 연결되지 않습니다*. | **Google에 전송** |

본 앱은 사용자 *계정 / 이메일 / 이름 / 연락처*를 **수집하지 않습니다**.

### 2. 권한

- **마이크 (`RECORD_AUDIO`)** — 튜너 기능에서 *음정 검출* 용도로만. 사용자가
  거부해도 메트로놈 기능은 정상 사용 가능.
- **알림 (`POST_NOTIFICATIONS`)** — 백그라운드 메트로놈 재생 시 상단에
  미디어 컨트롤 알림을 띄우기 위해 필요. 거부 시 알림 없이 재생.
- **wakelock** — 메트로놈 재생 중 화면이 꺼지지 않도록.

### 3. 광고

본 앱은 **Google AdMob** 배너 광고를 사용합니다. AdMob은 사용자의
광고 식별자·기기 정보·앱 사용 정보를 수집하여 맞춤·비맞춤 광고에
사용할 수 있습니다. 자세한 내용은 [Google 광고 정책](https://policies.google.com/technologies/ads)
및 [AdMob 동작 방식](https://support.google.com/admob/answer/6128543)을
참고하세요.

### 4. 분석 (Analytics)

본 앱은 **Google Analytics for Firebase**를 사용해 앱 이용 통계를
집계합니다. 수집 항목은 *어떤 화면을 보았는지*, *앱을 언제 몇 번
실행했는지* 정도이며, Google이 자동으로 부여하는 **앱 인스턴스 ID**와
함께 기록됩니다.

- 이름·이메일·연락처 등 **신원을 식별할 수 있는 정보는 수집하지
  않으며**, 위 통계는 개인을 특정하는 데 사용되지 않습니다.
- **마이크 오디오는 분석 대상이 아닙니다** — 튜너 입력은 기기 안에서만
  처리되며 어떤 형태로도 전송되지 않습니다.
- 목적은 *어떤 기능이 실제로 쓰이는지 파악해 앱을 개선*하고, 광고 게재
  성과를 확인하는 것입니다.

자세한 내용은 [Google Analytics for Firebase 데이터 수집 안내](https://firebase.google.com/support/privacy)를
참고하세요. 위 SDK(AdMob·Analytics) 외에 외부 네트워크 통신은 없습니다.

### 5. 미성년자

본 앱은 *특별히 어린이를 대상으로 하지 않습니다*. AdMob 광고는 *비
어린이 대상*으로 설정되어 있습니다. 13세 미만 사용자의 개인정보를
의도적으로 수집하지 않습니다.

### 6. 변경 사항

본 정책이 변경되면 같은 페이지의 "Last updated" 날짜를 갱신합니다.
중대한 변경 시 앱 내 공지 또는 스토어 등록 정보를 통해 안내합니다.

### 7. 연락처

- **Owlmakers** — `support@owlmakers.com`
- 도메인: `owlmakers.com`

---

## English

### 1. Data Collected and Processed

| Data | How it's handled | Sent to third parties? |
| --- | --- | --- |
| Microphone input (tuner) | Pitch detection runs *on-device only*. Raw audio is never stored or transmitted. | **No** |
| Metronome settings (BPM, time signature, subdivision, theme, language) | Stored *locally* via `shared_preferences`. | **No** |
| Android Advertising ID + device/app usage info | Used by Google AdMob for ad delivery. | **Yes — Google** |
| App usage statistics (screen views, launches/sessions) | Recorded by Google Analytics for Firebase against an app instance ID, to understand how the app is used. *Not linked to an identity.* | **Yes — Google** |

The app does **not** collect user *accounts, emails, names, or contact
information*.

### 2. Permissions

- **Microphone (`RECORD_AUDIO`)** — used only by the tuner for pitch
  detection. Declining still allows full metronome usage.
- **Notifications (`POST_NOTIFICATIONS`)** — required to display the
  media control notification while the metronome plays in the
  background. Declining means no notification; playback still works.
- **Wakelock** — keeps the screen on while the metronome is running.

### 3. Advertising

The app uses **Google AdMob** banner ads. AdMob may collect the user's
advertising identifier, device information, and app usage information
to serve personalized or non-personalized ads. See
[Google's advertising policies](https://policies.google.com/technologies/ads)
and [How AdMob works](https://support.google.com/admob/answer/6128543).

### 4. Analytics

The app uses **Google Analytics for Firebase** to measure app usage.
What it records is limited to *which screens were viewed* and *when and
how often the app was opened*, stored against an **app instance ID**
that Google assigns automatically.

- **No identifying information** (name, email, contact details) is
  collected, and these statistics are not used to identify individuals.
- **Microphone audio is never analysed** — tuner input is processed
  on-device and is not transmitted in any form.
- The purpose is to understand which features are actually used so the
  app can be improved, and to review ad performance.

See [Google Analytics for Firebase data collection](https://firebase.google.com/support/privacy)
for details. Aside from these SDKs (AdMob and Analytics), no external
network communication occurs.

### 5. Children

The app is **not specifically directed to children**. AdMob ads are
configured as *not child-directed*. The app does not knowingly collect
personal information from users under 13.

### 6. Changes

If this policy changes, the "Last updated" date at the top of this page
will be updated. Material changes will additionally be announced via
in-app notice or the app store listing.

### 7. Contact

- **Owlmakers** — `support@owlmakers.com`
- Domain: `owlmakers.com`
