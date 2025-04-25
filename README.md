# 🎬 **Movie App 프로젝트**

**Movie App**은 영화 데이터를 제공하는 API를 사용하여, 사용자가 인기 영화, 상영 중인 영화, 영화 정보 등을 조회할 수 있는 애플리케이션입니다. 이 프로젝트는 **Vue.js**를 사용하여 개발되었으며, 영화 데이터를 **The Movie Database (TMDb) API**를 통해 가져옵니다. 사용자 인터페이스(UI)는 **Vue.js**를 기반으로 구성되어 있으며, 직관적이고 빠른 사용자 경험을 제공합니다.

## 🚀 **기능 및 구현 사항**
- **영화 검색 기능**: 사용자가 원하는 영화를 검색하고 그에 대한 상세 정보를 확인할 수 있습니다.
- **상영 중인 영화 조회**: 실시간으로 상영 중인 영화를 목록으로 제공합니다.
- **영화 상세 정보**: 각 영화의 개요, 감독, 출연 배우, 평점 등의 정보를 표시합니다.
- **영화 포스터 및 배경 이미지**: 영화의 시각적인 요소를 제공하여 사용자가 쉽게 영화 정보를 인식할 수 있도록 합니다.

## 📂 **프로젝트 구조**
- `src/` 디렉토리:
  - `components/`: 영화 리스트와 상세 정보를 렌더링하는 컴포넌트
  - `views/`: 페이지 구성 요소
  - `store/`: Vuex를 사용한 상태 관리
  - `router/`: 라우터 설정
  - `assets/`: 영화 포스터 및 배경 이미지

## 🛠 **기술 스택**
- **Vue.js**: JavaScript 프레임워크
- **Vuex**: 상태 관리
- **Vue Router**: 라우팅
- **Axios**: API 호출
- **TMDb API**: 영화 정보 제공 API
- **CSS3/SCSS**: 스타일링

## 🔗 **연관 링크**
- **배포 링크**: [Movie App 배포 사이트](https://github.com/JeongHyeon96/movie_app)
- **GitHub 레포지토리**: [Movie App GitHub 레포지토리](https://github.com/JeongHyeon96/movie_app)

## 💻 **실행 방법**
```bash
# 프로젝트 클론
git clone https://github.com/JeongHyeon96/movie_app.git

# 의존성 설치
npm install

# 개발 서버 실행
npm run serve
