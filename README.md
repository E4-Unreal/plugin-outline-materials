# Plugin OutlineMaterials

- 오브젝트 외곽선 표시를 위한 포스트 프로세스 머터리얼 콘텐츠 전용 플러그인
- 포스트 프로세싱 볼륨에 머터리얼 추가 후 오브젝트 커스텀 뎁스 활성화 시 외곽선이 표시됩니다.
- 현재는 한 가지 색상만 사용이 가능하며 커스텀 깊이 스텐실 값에 따라 여러 색상으로 구분하는 것은 나중에 업데이트 할 예정입니다.

## 설치 방법

### 서브 모듈로 설치하는 방법

1. 메인 프로젝트 `git` 저장소 열기
2. 플러그인 `git` 저장소를 메인 프로젝트 `git` 저장소에 서브 모듈로서 추가
    - git 저장소의 `하위 폴더`에 언리얼 프로젝트가 생성된 경우 `지역 상대 경로`: `언리얼_프로젝트_폴더_이름/Plugins/OutlineMaterials`
    - git 저장소의 `루트 폴더`에 언리얼 프로젝트가 생성된 경우 `지역 상대 경로`: `Plugins/OutlineMaterials`

### zip 파일로 사용하는 방법

1. `zip` 파일 다운로드
2. 압축 해제 후 루트 폴더 이름을 `OutlineMaterials`으로 수정
3. 언리얼 프로젝트 `Plugins` 폴더로 `OutlineMaterials` 붙여넣기