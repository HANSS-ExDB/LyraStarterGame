# Lyra Starter Game

Unreal Engine 5 기반의 Lyra Sample Game 프로젝트입니다.

## 저장소 정보

- **GitHub**: https://github.com/HANSS-ExDB/LyraStarterGame
- **엔진**: Unreal Engine 5
- **언어**: C++, Blueprint

## 시작하기

### 요구사항

- Unreal Engine 5 (Epic Games Launcher를 통해 설치)
- Visual Studio 2022

### 설치 방법

1. 저장소 클론
   ```bash
   git clone https://github.com/HANSS-ExDB/LyraStarterGame.git
   cd LyraStarterGame
   git lfs pull
   ```

2. `LyraStarterGame.uproject` 파일을 우클릭 → **Generate Visual Studio project files** 실행

3. 생성된 `.sln` 파일을 Visual Studio로 열고 빌드

## 프로젝트 구조

```
LyraStarterGame/
├── Config/       # 엔진 및 게임 설정
├── Content/      # 게임 에셋 (Git LFS로 관리)
├── Plugins/      # 플러그인 (Git LFS로 관리)
├── Source/       # C++ 소스 코드
└── Platforms/    # 플랫폼별 설정
```

## Git LFS

`.uasset`, `.umap` 등 바이너리 에셋은 Git LFS로 관리됩니다.
클론 후 `git lfs pull`을 실행해 에셋을 내려받으세요.

## 참고 자료

- [Unreal Engine Lyra 공식 문서](https://docs.unrealengine.com/5.0/en-US/lyra-sample-game-in-unreal-engine/)