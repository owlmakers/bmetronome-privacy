# Privacy Policy — Dual Metronome

_Last updated: 2026-09-15 (own usage statistics added)_

Dual Metronome (formerly Bmetronome; "the app") is an offline metronome and tuner built by
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
| 자체 사용 통계 (국가·지역 포함) | 개발자 자체 서버(`api.owlmakers.com`)가 앱이 정상적으로 쓰이는지 확인하기 위해 기록. 앱 이름·버전·표시 언어, 화면 이동·탭 종류, 실행 중이라는 신호, *실행마다 새로 만들어지는 무작위 값*(저장 안 함, 식별 불가). | **개발자 자체 서버로 전송(HTTPS)** |

본 앱은 사용자 *계정 / 이메일 / 이름 / 연락처*를 **수집하지 않습니다**. 개발자가 운영하는 서버로 나가는 것은
위 표의 **자체 사용 통계**뿐이며, 아래 4-2항에 자세히 적습니다.

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
참고하세요.

### 4-2. 자체 사용 통계 (Owlmakers)

개발자는 앱이 정상적으로 쓰이고 있는지 확인하기 위해 **자체 서버로 익명 사용 통계(국가·지역 포함)**를
전송합니다(`api.owlmakers.com`, HTTPS).

- 전송되는 것: 앱 이름·버전·표시 언어, 화면 이동과 버튼 탭 종류(위 4항과 같은 값), 광고를 눌렀는지 여부(광고
  형식), 앱을 쓰는 중이라는 신호(메트로놈 재생 중 포함), 그리고 **앱을 실행할 때마다 새로 만들어지는 무작위
  값**(저장하지 않으므로 이용자나 기기를 식별하지 않습니다).
- 서버는 접속 경로에서 **국가와 시·도**만 기록합니다. **IP 주소는 저장하지 않으며**, 좌표 같은 정밀 위치는
  받지 않습니다.
- **마이크 오디오는 여기로도 전송되지 않습니다.**
- 보관 기간은 1년이며, 제3자에게 제공하지 않습니다.

위 SDK·서버(AdMob·Analytics·자체 사용 통계) 외에 외부 네트워크 통신은 없습니다.

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
| Our own usage statistics (including country and region) | Recorded by our own server (`api.owlmakers.com`) to confirm the app is working in real use. App name, version, display language, screen views/tap types, an "in use" signal, and a *random value created fresh on every launch* (never stored, not identifying). | **Yes — our own server (HTTPS)** |

The app does **not** collect user *accounts, emails, names, or contact
information*. The only thing sent to a server the developer operates is the **usage statistics row above**,
described in more detail in section 4b.

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
for details.

### 4b. Our own usage statistics (Owlmakers)

To check that the app is working in real use, the developer sends **anonymous usage statistics
(including country and region)** to its own server (`api.owlmakers.com`, over HTTPS).

- What is sent: app name, version and display language; screen views and button tap types (the same
  values as section 4); whether an ad was tapped (ad format); an "in use" signal (including while the
  metronome is playing); and a **random value created fresh on every launch** (never stored, so it
  identifies neither you nor your device).
- The server records only the **country and region** of the connection. **IP addresses are not
  stored**, and no precise location is received.
- **Microphone audio is not sent here either.**
- Data is kept for one year and is not shared with third parties.

Aside from these SDKs/servers (AdMob, Analytics, our own usage statistics), no external
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
