---
layout: default
title: Planpal Privacy Policy
---

# Planpal 개인정보처리방침

**시행일자: 2026년 2월 22일**

김도현(이하 "개발자")은 「개인정보 보호법」 제30조에 따라 정보주체의 개인정보를 보호하고 이와 관련한 고충을 신속하고 원활하게 처리할 수 있도록 하기 위하여 다음과 같이 개인정보 처리방침을 수립·공개합니다.

---

## 제1조 (개인정보의 처리 목적)

Planpal(이하 "앱")은 다음의 목적을 위하여 개인정보를 처리합니다.

1. **일정 및 할 일 관리 서비스 제공** - 사용자가 입력한 일정, 할 일, 메모 등의 데이터를 저장하고 관리합니다.
2. **AI 기반 일정 분석 기능 제공** - 사용자가 입력한 텍스트 또는 선택한 이미지를 분석하여 일정과 할 일을 자동으로 추출합니다. AI 기능은 사용자가 직접 발급한 Google Gemini API 키를 사용하며, 개발자는 해당 키에 접근할 수 없습니다.
3. **기기 간 데이터 동기화** - 사용자의 iCloud 계정을 통해 여러 기기 간 데이터를 동기화합니다.
4. **외부 캘린더 및 미리 알림 연동** - Apple 캘린더 및 미리 알림 앱과의 데이터 연동 기능을 제공합니다.

---

## 제2조 (처리하는 개인정보의 항목)

### 필수 항목
| 항목 | 설명 |
|------|------|
| 일정 정보 | 일정 제목, 시작/종료 시간, 메모, 알림 설정 |
| 할 일 정보 | 할 일 제목, 마감일, 메모, 우선순위, 완료 여부 |
| 태그 정보 | 사용자가 생성한 태그 이름 및 색상 |

### 선택 항목 (사용자 동의 시)
| 항목 | 설명 | 수집 목적 | 저장 위치 |
|------|------|----------|----------|
| Gemini API 키 | 사용자가 직접 발급한 Google Gemini API 키 | AI 기능 사용 | 기기 키체인 (iCloud 백업 제외) |
| 사진/이미지 | 사용자가 AI 분석을 위해 선택한 이미지 | AI 기반 일정 추출 | 분석 후 즉시 삭제 |
| Apple 캘린더 데이터 | 연동 시 캘린더 일정 정보 | 외부 캘린더 연동 | 기기 내 저장 |
| Apple 미리 알림 데이터 | 연동 시 미리 알림 정보 | 미리 알림 동기화 | 기기 내 저장 |

### 자동 수집 항목
- 앱은 사용자 행동 분석, 광고, 추적 목적의 데이터를 수집하지 않습니다.
- 분석 도구(Analytics) 및 광고 SDK를 사용하지 않습니다.

---

## 제3조 (개인정보의 처리 및 보유 기간)

1. **기기 내 저장 데이터** - 보유 기간: 사용자가 앱을 삭제하거나 데이터를 직접 삭제할 때까지
2. **iCloud 동기화 데이터** - 보유 기간: 사용자가 iCloud에서 데이터를 삭제하거나 iCloud 동기화를 해제할 때까지
3. **AI 분석용 전송 데이터** - 사용자가 입력한 텍스트 및 이미지는 분석 목적으로 Google Gemini API에 전송됩니다. 전송 시 사용자 본인이 발급한 API 키가 사용되며, 전송된 데이터는 앱에 저장되지 않습니다. Google의 데이터 보존 정책에 따라 처리됩니다.
4. **Gemini API 키** - 사용자 기기의 키체인(Keychain)에 저장되며, iCloud 백업에 포함되지 않습니다(`kSecAttrAccessibleWhenUnlockedThisDeviceOnly`). 앱 삭제 또는 사용자가 직접 삭제 시 즉시 파기됩니다.

---

## 제4조 (개인정보의 제3자 제공)

앱은 다음과 같이 개인정보를 제3자에게 제공합니다.

| 제공받는 자 | 제공 목적 | 제공 항목 | 보유 기간 |
|------------|----------|----------|----------|
| Google LLC (Gemini AI) | AI 기반 텍스트/이미지 분석 | 사용자가 입력한 텍스트, 선택한 이미지 | Google 정책에 따름 |
| Apple Inc. (iCloud) | 기기 간 데이터 동기화 | 일정, 할 일, 태그 데이터 | 사용자 삭제 시까지 |

※ Google Gemini AI 전송은 **사용자 본인이 발급한 API 키**를 통해 이루어집니다. 개발자는 사용자의 API 키 또는 전송 데이터에 접근할 수 없습니다.

※ 위 제3자 제공은 해당 기능 사용 시에만 이루어지며, 사용자가 해당 기능을 사용하지 않으면 데이터가 전송되지 않습니다.

---

## 제5조 (개인정보처리의 위탁)

앱은 개인정보 처리업무를 별도로 위탁하지 않습니다.

---

## 제6조 (정보주체의 권리·의무 및 행사방법)

정보주체는 다음과 같은 권리를 행사할 수 있습니다.

1. **개인정보 열람 요구**
2. **오류 등이 있을 경우 정정 요구**
3. **삭제 요구**
4. **처리정지 요구**

### 권리 행사 방법
- **앱 내 삭제**: 일정, 할 일, 태그 등 모든 데이터는 앱 내에서 직접 삭제할 수 있습니다.
- **AI 키 삭제**: 설정 > AI 설정에서 Gemini API 키를 삭제할 수 있습니다.
- **앱 삭제**: 앱을 삭제하면 기기에 저장된 모든 데이터 및 API 키가 삭제됩니다.
- **iCloud 데이터 삭제**: 설정 > Apple ID > iCloud > 저장 공간 관리에서 Planpal 데이터를 삭제할 수 있습니다.
- **문의**: 아래 연락처로 개인정보 관련 요청을 하실 수 있습니다.

---

## 제7조 (개인정보의 파기)

1. **파기 절차** - 사용자가 앱을 삭제하거나 데이터 삭제를 요청하면 해당 개인정보는 즉시 파기됩니다.
2. **파기 방법** - 전자적 파일: 복구 불가능한 방법으로 영구 삭제 / 기기 내 데이터: iOS 운영체제의 앱 삭제 기능을 통해 완전 삭제

---

## 제8조 (개인정보의 안전성 확보조치)

1. **데이터 암호화** - 모든 데이터는 iOS의 샌드박스 환경에서 암호화되어 저장됩니다. iCloud 동기화 시 Apple의 종단간 암호화가 적용됩니다.
2. **API 키 보안 저장** - Gemini API 키는 iOS 키체인(Keychain)에 `kSecAttrAccessibleWhenUnlockedThisDeviceOnly` 속성으로 저장되어 iCloud 백업에서 제외되며, 기기 잠금 해제 상태에서만 접근 가능합니다.
3. **보안 통신** - 외부 서버(Google AI)와의 통신은 HTTPS(TLS) 암호화를 통해 이루어집니다.
4. **접근 제한** - 앱 데이터 및 API 키는 사용자의 기기에만 저장되며, 개발자는 접근할 수 없습니다.

---

## 제9조 (개인정보 자동 수집 장치의 설치·운영 및 거부)

앱은 쿠키, 웹 비콘 등 자동 수집 장치를 사용하지 않습니다.

---

## 제10조 (행태정보의 수집·이용·제공 및 거부)

앱은 온라인 맞춤형 광고 등을 위한 행태정보를 수집·이용·제공하지 않습니다.

---

## 제13조 (개인정보 보호책임자)

| 항목 | 내용 |
|------|------|
| 성명 | 김도현 |
| 직책 | 개인 개발자 |
| 연락처 | planpal114@gmail.com |

---

## 제15조 (정보주체의 권익침해 구제방법)

| 기관 | 연락처 | 홈페이지 |
|------|--------|----------|
| 개인정보분쟁조정위원회 | 1833-6972 | [www.kopico.go.kr](https://www.kopico.go.kr) |
| 개인정보침해신고센터 | 118 | [privacy.kisa.or.kr](https://privacy.kisa.or.kr) |
| 대검찰청 사이버수사과 | 1301 | [www.spo.go.kr](https://www.spo.go.kr) |
| 경찰청 사이버수사국 | 182 | [ecrm.cyber.go.kr](https://ecrm.cyber.go.kr) |

---

## 제17조 (개인정보 처리방침의 변경)

이 개인정보처리방침은 2026년 2월 22일부터 적용됩니다.

개인정보처리방침 내용 추가, 삭제 및 수정이 있을 경우에는 시행일 최소 7일 전에 앱 내 공지사항 또는 이메일을 통해 알려드리겠습니다.

---

# Planpal Privacy Policy (English)

**Effective Date: February 22, 2026**

## 1. Introduction

Kim Dohyun ("Developer") operates the Planpal application ("App"). This Privacy Policy explains how we collect, use, and protect your personal information.

## 2. Information We Collect

### Data You Provide
- **Schedule Information**: Event titles, dates, times, notes, and notification settings
- **Task Information**: Task titles, due dates, notes, priorities, and completion status
- **Tags**: Custom tag names and colors

### Optional Data (with your consent)
| Item | Purpose | Storage |
|------|---------|---------|
| Gemini API Key | Enables AI features (issued by you directly) | Device Keychain only (excluded from iCloud backup) |
| Photos/Images | AI-based schedule extraction | Sent to Gemini API, not stored in app |
| Apple Calendar data | Calendar sync | Stored on device |
| Apple Reminders data | Reminder sync | Stored on device |

### Data We Do NOT Collect
- Personal identifiers (name, email, phone number)
- Analytics or tracking data
- Advertising data

## 3. How We Use Your Information

- To provide schedule and task management services
- To analyze text and images for automatic event extraction (AI feature, using **your own** Gemini API key)
- To sync data across your devices via iCloud
- To integrate with Apple Calendar and Reminders

## 4. Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Google Gemini AI | Text/image analysis | Text input, selected images |
| Apple iCloud | Data synchronization | Events, tasks, tags |

> **Important:** AI analysis uses **your own Google Gemini API key**, which is stored only in your device's Keychain. The Developer cannot access your API key or the data sent to Google.

## 5. Data Storage and Security

- All data is stored locally on your device in iOS's encrypted sandbox
- Your Gemini API key is stored in the iOS Keychain with `kSecAttrAccessibleWhenUnlockedThisDeviceOnly` — it is **excluded from iCloud backup** and accessible only when your device is unlocked
- iCloud sync uses Apple's end-to-end encryption
- All communications with Google AI use HTTPS/TLS encryption
- The Developer has no access to your data or API key

## 6. Your Rights

You can:
- View, edit, or delete your data within the app
- Delete your Gemini API key via Settings > AI Settings
- Delete all data by uninstalling the app
- Manage iCloud data through iOS Settings > Apple ID > iCloud

## 7. Children's Privacy

This App is not intended for children under 14 years of age.

## 8. Changes to This Policy

We will notify users of any changes at least 7 days before they take effect.

## 9. Contact Us

**Email:** planpal114@gmail.com

---

*Last Updated: February 22, 2026*
