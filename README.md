# 벽돌 깨기 게임
-----
## 개요
"벽돌 깨기"는 플레이어가 패들을 조작하여 공을 튕기고 화면의 모든 벽돌을 깨는 고전 아케이드 게임입니다. 게임은 여러 단계로 진행되며 각 단계마다 벽돌의 행 수가 증가합니다. 플레이어는 패들을 사용하여 공이 화면 아래로 떨어지지 않도록 해야 합니다.

## 요구 사항
- Python 3.x
- Pygame 라이브러리

## 설치
 1. Python이 이 시스템에 설치되어 있는지 확인합니다.
 2. Pygame 라이브러리를 설치합니다. 터미널 또는 명령 프롬프트에서 다음 명령어를 실행합니다.
```bash
pip install pygame
```
## 실행 방법
 1. 소스 코드를 다운로드하거나 클론합니다.
```
git clone https://github.com/Mirina3/Team11_Project.git
cd Team11_Project
```
 2. main.py 파일을 실행합니다.
```
python Brick_Breaker.py
```
## 게임 방법
 1. 게임을 시작하면 "Brick Breaker" 타이틀 화면이 나타납니다. 아무 키나 눌러 게임을 시작할 수 있습니다.
 2. 게임 화면에서는 좌우 화살표 키를 사용하여 패들을 움직입니다.
 3. 공이 패들에 맞아 튕겨져 나가 벽돌을 맞추면 점수를 획득합니다.
 4. 모든 벽돌을 깨면 다음 스테이지로 넘어갑니다.
 5. 공이 바닥에 닿으면 목숨이 하나 줄어들고, 목숨이 모두 소진되면 게임 오버 화면이 나타납니다.
 6. 게임 도중 'P' 키를 눌러 일시정지할 수 있습니다.

## 주요 기능
 - 시작 화면: 게임 시작 전 타이틀 화면이 표시됩니다.
 - 패들 이동: 좌우 화살표 키로 패들을 좌우로 움직일 수 있습니다.
 - 공 이동: 공이 자동으로 움직이며, 벽돌이나 패들에 맞으면 방향이 반사됩니다.
 - 벽돌: 여러 색상의 벽돌이 있으며, 색상이 다른 벽돌이 공에 맞으면 사라지면서 목숨이 하나 늘어납니다.
 - 스테이지: 각 스테이지마다 다른 벽돌 배열이 나타납니다.
 - 점수: 벽돌을 맞출 때마다 점수가 증가합니다.
 - 목숨: 공이 바닥에 닿으면 목숨이 줄어들고, 목숨이 모두 소진되면 게임이 종료됩니다.
 - 일시정지: 'P' 키를 눌러 게임을 일시정지할 수 있습니다.
