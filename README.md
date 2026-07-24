# Gobbleverse Client Updates

코블버스 서버의 클라이언트 필수 모드 배포 저장소입니다.

## 플레이어 설치

1. [GobbleverseClientUpdater.exe](https://github.com/gominsu08/gobbleverse-client-updates/releases/latest/download/GobbleverseClientUpdater.exe)를 받습니다.
2. 마인크래프트를 완전히 종료합니다.
3. EXE를 실행합니다.
4. 도구가 Modrinth의 COBBLEVERSE 인스턴스를 찾아 최신 모드만 백업 후 설치합니다.

Modrinth 기본 모드팩 전체를 변경하지 않습니다. 이 저장소의 `manifest.json`에 등록된 코블버스 모드와 서버 호환성이 중요한 모드만 관리합니다.

## 현재 배포

| 모드 | 버전 | 파일 |
| --- | --- | --- |
| 코블버스 UI | `0.2.22` | `cobbleverse-ui-0.2.22.jar` |
| 코블버스 건차 | `0.2.1` | `cobbleverse-claim-0.2.1.jar` |
| Let's Do: Farm & Charm | `1.1.22` | `letsdo-farm_and_charm-fabric-1.1.22.jar` |

## 무결성

모든 파일은 설치 전에 크기와 SHA-256을 확인합니다. 기존 파일은 인스턴스의 `gobbleverse-mod-backup/client-updater`에 보관되고 설치 실패 시 자동 복구됩니다.

