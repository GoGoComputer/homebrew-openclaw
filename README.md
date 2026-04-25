# homebrew-openclaw

Homebrew tap for [openclaw-workspace](https://github.com/GoGoComputer/openclaw-workspace).

## 사용법 / Usage

```bash
brew tap gogocomputer/openclaw   # tap 등록 (한 번만)
brew install openclaw-workspace   # 설치
openclaw                          # 실행 (대화형 메뉴, KO/EN 자동)
```

> macOS 만 지원. Docker Desktop / Ollama 는 `openclaw install` 이 자동 설치합니다.

## 업데이트 / Update

```bash
brew update && brew upgrade openclaw-workspace
```

## 제거 / Uninstall

```bash
openclaw uninstall          # OpenClaw 컨테이너 제거 (Docker 는 보존)
brew uninstall openclaw-workspace
brew untap gogocomputer/openclaw
```

자세한 문서는 [메인 저장소 README](https://github.com/GoGoComputer/openclaw-workspace) 를 보세요.

## License

MIT — see [main repo](https://github.com/GoGoComputer/openclaw-workspace/blob/main/LICENSE).
