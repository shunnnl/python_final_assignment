 # 할매입맛 테스트
이 프로젝트는 사용자에게 다양한 음식에 대한 선호도를 묻고, 사용자의 '할매입맛' 수준을 평가합니다. 테스트 결과에 따라 추천 음식점도 제공됩니다.

## 설치 방법
프로젝트를 실행하기 전에 다음 두 가지 패키지를 반드시 설치해야 합니다:

```sh
pip install Pillow
pip install folium
```

## 가상 환경 설정 (선택 사항)
독립적인 Python 환경을 설정하기 위해 가상 환경을 사용하는 것이 좋습니다. 아래의 명령어로 가상 환경을 설정하고 활성화할 수 있습니다.

```sh
# 가상 환경 생성
python3 -m venv venv

# 가상 환경 활성화 (MacOS/Linux)
source venv/bin/activate

# 가상 환경 활성화 (Windows)
venv\Scripts\activate
```

## 실행 방법
프로젝트를 실행하려면 다음 단계를 따르세요:

1. 이 저장소를 클론하거나 다운로드합니다.
2. 터미널에서 프로젝트 디렉토리로 이동합니다.
3. 필요한 패키지를 설치합니다.
4. final.py 파일을 실행합니다.

```sh
# 저장소 클론
git clone <repository-url>
cd python_final_assignment-main

# 필요한 패키지 설치
pip install Pillow
pip install folium

# 프로젝트 실행
python final.py
```

## restrant.csv 파일 설명
restrant.csv 파일에는 할매입맛 레벨별로 추천하는 음식점의 정보가 포함되어 있습니다. 파일의 각 행은 다음과 같은 필드를 포함합니다:

name: 음식점 이름
latitude: 음식점의 위도
longitude: 음식점의 경도
menu: 추천 메뉴
level: 할매입맛 레벨 (1, 2, 3)
