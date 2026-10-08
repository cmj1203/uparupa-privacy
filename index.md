---
title: 우파루파 키우기 개인정보 처리방침
---


시행일: 2026-10-08

우파루파 키우기(이하 '앱')는 바탕화면에서 우파루파를 키우는 Windows 앱입니다. 앱은 회원 가입이나 로그인이 없고, 개발자가 운영하는 서버로 정보를 보내지 않습니다.

## 1. 앱 밖으로 보내는 정보

| 보내는 곳 | 보내는 정보 | 쓰는 곳 |
|---|---|---|
| ipwho.is | 인터넷 주소(IP). 요청을 보내면 상대 서버가 자연히 알게 됩니다 | 대략적인 도시 위치를 알아내 날씨를 보여 줍니다 |
| Open-Meteo(api.open-meteo.com) | 위에서 얻은 대략적인 위도·경도 | 날씨와 기온을 받아 배경 연출과 펫의 말에 씁니다 |

- 날씨 조회는 앱이 켜져 있는 동안 1시간마다 합니다.
- 두 서비스가 받은 정보를 다루는 방식은 각 서비스의 방침을 따릅니다.
- 앱은 사용 통계·광고·추적 도구를 쓰지 않습니다.

## 2. 컴퓨터 안에만 저장하는 정보

- 펫 상태(배고픔·기분·코인), 꾸미기, 설정은 이 컴퓨터의 앱 데이터 폴더에만 저장합니다. 앱을 지우면 함께 지워집니다.
- 설정에서 '작업 반응'을 직접 연결한 경우에만, Claude Code 설정 파일과 PowerShell 프로필에 이 앱이 쓰는 줄을 넣습니다. 고치기 전 원본을 백업하고, '연결 끊기'로 뺄 수 있습니다. 이때 기록되는 것은 명령의 시작·끝 시각과 종료 코드뿐이며 명령 내용은 기록하지 않습니다.
- 펫이 작업 중인 창 위에 앉을 자리를 찾을 때 Windows UI Automation으로 입력칸의 위치와 크기만 읽습니다. 입력한 글자나 창 제목은 읽지 않습니다.

## 3. 아이와 개인정보

앱은 나이를 묻지 않고 개인정보를 모으지 않습니다.

## 4. 바뀔 때

이 방침이 바뀌면 이 페이지와 시행일을 고칩니다.

## 5. 문의

konoha09@naver.com

---

# Uparupa Privacy Policy

Effective: 2026-10-08

Uparupa ("the app") is a Windows desktop pet. It has no accounts and sends nothing to servers run by the developer.

**Data sent outside the app**
- ipwho.is receives your IP address so the app can find your approximate city for weather.
- Open-Meteo (api.open-meteo.com) receives that approximate latitude/longitude and returns weather and temperature. Weather is checked hourly while the app runs.
- No analytics, advertising, or tracking.

**Data kept on your PC only**
- Pet state, customizations, and settings are stored in the app's local data folder and are removed with the app.
- Only if you connect "work reactions" in settings, the app adds its own lines to your Claude Code settings file and PowerShell profile (backed up first, removable with "disconnect"). It records only command start/end times and exit codes, never command text.
- To seat the pet above the window you're working in, it reads only the position and size of the input field through Windows UI Automation — never the text you type or window titles.

**Children** — The app does not ask for age or collect personal information.

**Changes** — This page and its date will be updated if the policy changes.

**Contact** — konoha09@naver.com
