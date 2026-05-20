# Privacy Policy — Bmetronome

_Last updated: 2026-05-21_

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

### 4. 추적 / 분석

본 앱은 *Google Analytics / Firebase Analytics / 제 3자 추적 SDK를
포함하지 않습니다*. 광고 SDK 외에 외부 네트워크 통신이 없습니다.

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

### 4. Tracking / Analytics

The app does **not** include Google Analytics, Firebase Analytics, or
any third-party tracking SDK. Aside from the AdMob SDK, no external
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
