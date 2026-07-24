# Gobbleverse Client Updates

코블버스 서버의 클라이언트 필수 모드 배포 저장소입니다.

## 플레이어 설치

1. [GobbleverseClientUpdater.exe](https://github.com/gominsu08/gobbleverse-client-updates/releases/latest/download/GobbleverseClientUpdater.exe)를 받습니다.
2. 마인크래프트를 완전히 종료합니다.
3. EXE를 실행합니다.
4. 도구가 Modrinth의 COBBLEVERSE 인스턴스를 찾아 최신 모드만 백업 후 설치합니다.

Modrinth 기본 모드팩의 개인 설정은 변경하지 않습니다. `manifest.json`에 등록된 기준 모드 145개의 버전과 SHA-256을 검사하며, 변경된 파일만 백업 후 서버 기준으로 교체합니다.

## 저장소 직접 배포 모드

| 모드 | 버전 | 파일 |
| --- | --- | --- |
| Cobblemon Battle Positions | `1.1.2` | `cobblemon-battle-positions-1.1.3.jar` |
| Cobbleverse Claim | `0.2.1` | `cobbleverse-claim-0.2.1.jar` |
| Cobbleverse UI | `0.2.22` | `cobbleverse-ui-0.2.22.jar` |

나머지 공개 모드는 Modrinth 공식 CDN에서 검증된 정확한 파일을 내려받습니다.

## 무결성

모든 파일은 설치 전에 크기와 SHA-256을 확인합니다. 기존 파일은 인스턴스의 `gobbleverse-mod-backup/client-updater`에 보관되고 설치 실패 시 자동 복구됩니다.

