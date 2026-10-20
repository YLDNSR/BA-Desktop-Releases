# BA Desktop

블루 아카이브 학생이 바탕화면 위에 서서 움직이는 Windows / macOS용 데스크톱 마스코트입니다.

> 비공식 프로그램이며, 게임 에셋은 포함되어 있지 않습니다. 아래 [주의사항](#주의사항)을 확인해 주세요.

## 다운로드

[최신 릴리즈](https://github.com/YLDNSR/BA-Desktop-Releases/releases/latest)에서 운영체제에 맞는 파일 하나를 받으세요. 설치 과정 없이 바로 실행됩니다.

| 운영체제 | 받을 파일 | 실행 방법 |
|---|---|---|
| macOS 13 Ventura 이상 (Intel, Apple Silicon) | `BA-Desktop-<버전>-mac-universal.zip` | 압축을 풀고 `BA Desktop.app` 실행 |
| Windows 10 이상 (64비트) | `BA-Desktop-<버전>-win-x64.exe` | 그대로 실행 |

### 처음 실행할 때

- **macOS**: 개발자 인증을 받지 않은 앱이라 처음에는 열리지 않을 수 있습니다. Finder에서 앱을 우클릭 → **열기**를 누르거나,
  시스템 설정 → 개인정보 보호 및 보안에서 **그래도 열기**를 누르세요. 앱은 `응용 프로그램` 폴더로 옮긴 뒤 실행하는 것을 권장합니다.
- **Windows**: "Windows의 PC 보호" 창이 뜨면 **추가 정보** → **실행**을 누르세요. exe는 바탕화면이나 문서 폴더처럼
  쓰기 가능한 곳에 두고 실행하세요.
- 캐릭터를 처음 표시할 때는 모델을 내려받는 동안 진행률이 표시됩니다. 인터넷 연결이 필요하며, 한 번 받은 캐릭터는 다음부터 바로 나타납니다.

## 사용법

| 조작 | 동작 |
|---|---|
| 캐릭터 클릭 | 반응 모션 |
| 캐릭터 드래그 | 들어 올려서 옮기기 (들고 있는 동안 공중에 떠 있고, 서 있던 바닥이 은은한 선으로 표시됨) |
| 캐릭터 위에서 마우스 휠 | 확대 / 축소 |
| 캐릭터 우클릭, 또는 트레이(메뉴 막대) 아이콘 | 메뉴 열기 |

- 별도 창 없이 캐릭터만 바탕화면에 표시됩니다. 캐릭터가 없는 투명한 부분을 클릭하면 아래에 있는 창이 클릭됩니다.
- 캐릭터는 항상 정면을 바라봅니다.
- 위치와 크기는 프로그램을 다시 실행해도 그대로 유지됩니다.
- 한동안 조작하지 않으면 가끔 특별한 동작을 보여 줍니다.

### 메뉴

- **캐릭터**: 표시할 학생 고르기 (같은 학생의 의상끼리 묶여 있음)
- **무작위 캐릭터**
- **크게 / 작게 / 기본 크기 / 위치 초기화**
- **항상 위에 표시**
- **로그인 시 자동 실행**
- **업데이트 확인…**
- **모델 캐시**: 캐시 폴더 열기, 캐시 비우기 (내려받은 모델을 지우며, 다음에 표시할 때 다시 받습니다)
- **종료**

## 업데이트

프로그램을 시작할 때 새 버전이 있는지 확인합니다. 새 버전이 있으면 변경 내역을 보여 주고 업데이트할지 묻습니다.

- **업데이트**: 새 버전을 받아 스스로 교체한 뒤 다시 실행합니다.
- **나중에**: 다음 실행 때 다시 묻습니다.
- **이 버전 건너뛰기**: 그 다음 버전이 나올 때까지 묻지 않습니다.

메뉴의 **업데이트 확인…**으로 언제든 직접 확인할 수 있습니다.

새 캐릭터 추가나 캐릭터 이름 변경 같은 **캐릭터 목록의 변경은 앱 업데이트 없이** 자동으로 반영됩니다.
프로그램을 시작할 때(실행 중에는 몇 시간마다) 최신 목록을 확인하며, 인터넷에 연결되어 있지 않으면 마지막으로 받은 목록을 씁니다.

## 캐릭터 모델의 출처

캐릭터 모델과 애니메이션은 이 저장소와 릴리즈 파일에 들어 있지 않습니다.
프로그램은 사용자가 캐릭터를 처음 표시할 때, 아래 공개 저장소에서 그 캐릭터의 모델 파일을 사용자의 컴퓨터로 직접 내려받아 저장합니다.

- 모델 저장소: **[lihaohong6/BlueArchiveModels](https://github.com/lihaohong6/BlueArchiveModels)**

모델 파일의 제작과 공개는 해당 저장소의 소관입니다. BA Desktop은 그 파일을 호스팅하거나 재배포하지 않습니다.

## 주의사항

- BA Desktop은 비공식 프로그램입니다. NEXON Games, Yostar 등 블루 아카이브의 권리자와 관계가 없으며, 이들의 승인이나 후원을 받지 않았습니다.
- 블루 아카이브와 등장 캐릭터, 3D 모델, 애니메이션, 텍스처 등 관련 저작물과 상표에 대한 모든 권리는 NEXON Games Co., Ltd. 및 각 권리자에게 있습니다.
- 이 저장소와 배포 파일에는 어떠한 게임 에셋도 포함되어 있지 않습니다. 모델 파일은 실행 중에 위의 제3자 공개 저장소에서 사용자의 컴퓨터로 직접 전송되며,
  BA Desktop 개발자는 그 파일을 호스팅, 재배포, 판매하지 않습니다.
- 내려받은 모델의 이용이 권리자의 이용약관과 거주 지역의 법령에 맞는지는 사용자가 확인해야 하며, 그 이용에 따른 책임은 사용자에게 있습니다.
- 이 프로그램은 어떠한 보증도 없이 "있는 그대로" 제공되며, 사용으로 인해 생긴 문제에 대해 개발자는 책임을 지지 않습니다.
- 권리자가 요청하면 해당 기능이나 배포를 중단하겠습니다. 문의는 이 저장소의 [Issues](https://github.com/YLDNSR/BA-Desktop-Releases/issues)에 남겨 주세요.

### Legal notice

BA Desktop is an unofficial fan-made program. It is not affiliated with, endorsed or sponsored by NEXON Games, Yostar or any other
rights holder of Blue Archive. All rights to Blue Archive, its characters, 3D models, animations, textures and trademarks belong to
NEXON Games Co., Ltd. and their respective owners.

This repository and its release files contain no game assets. Character models are downloaded at runtime, directly to the user's
computer, from the third-party public repository [lihaohong6/BlueArchiveModels](https://github.com/lihaohong6/BlueArchiveModels);
the developer of BA Desktop does not host, redistribute or sell them. Users are responsible for making sure their use of those
files complies with the rights holders' terms and the laws that apply to them.

This software is provided "as is", without warranty of any kind. Rights holders may request removal through
[Issues](https://github.com/YLDNSR/BA-Desktop-Releases/issues).
