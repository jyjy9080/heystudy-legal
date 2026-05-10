# HeyStudy Legal Documents

HeyStudy 앱의 법적 문서들 (개인정보 처리방침, 이용약관, 계정 삭제 요청).

## 파일 구성

| 파일 | 용도 |
|------|------|
| `index.html` | 개인정보 처리방침 |
| `terms.html` | 이용약관 |
| `delete.html` | 계정 삭제 요청 페이지 (Play Store 정책 필수) |
| `privacy.md` | 개인정보 처리방침 (마크다운 원본) |
| `terms.md` | 이용약관 (마크다운 원본) |

## GitHub Pages 호스팅 방법

### 1단계: GitHub 저장소 만들기

1. https://github.com/new 접속
2. Repository name: `heystudy-legal`
3. **Public** 선택 (필수 - GitHub Pages 무료는 Public만)
4. "Create repository" 클릭

### 2단계: 파일 업로드

옵션 A: 웹 인터페이스로 업로드 (가장 쉬움)
1. 새 저장소 페이지에서 "uploading an existing file" 링크 클릭
2. 본 폴더의 모든 파일 드래그 앤 드롭
3. "Commit changes" 클릭

옵션 B: Git 명령어
```bash
cd heystudy-legal
git init
git add .
git commit -m "Initial commit: legal documents"
git branch -M main
git remote add origin https://github.com/jyjy9080/heystudy-legal.git
git push -u origin main
```

### 3단계: GitHub Pages 활성화

1. 저장소 페이지 → Settings 탭
2. 좌측 메뉴 → Pages
3. Source: **Deploy from a branch**
4. Branch: **main** / **/ (root)**
5. Save 클릭
6. 1~2분 후 URL 생성됨

### 4단계: URL 확인

활성화 후 다음 URL들이 작동합니다:

```
https://jyjy9080.github.io/heystudy-legal/
   → 개인정보 처리방침

https://jyjy9080.github.io/heystudy-legal/terms.html
   → 이용약관

https://jyjy9080.github.io/heystudy-legal/delete.html
   → 계정 삭제 요청 페이지
```

## Play Console 입력값

Play Console에서 다음 필드에 입력하세요:

| Play Console 필드 | 입력 URL |
|------------------|---------|
| 개인정보처리방침 | `https://jyjy9080.github.io/heystudy-legal/` |
| 데이터 안전성 → 계정 삭제 URL | `https://jyjy9080.github.io/heystudy-legal/delete.html` |

## 수정이 필요한 경우

각 HTML 파일을 텍스트 에디터로 직접 편집한 후 GitHub에 다시 push하면 됩니다.
변경사항은 1~2분 내에 GitHub Pages에 반영됩니다.

## 본인이 직접 수정해야 할 부분

다음 정보가 본인 정보로 정확히 들어가 있는지 확인하세요:

- ✅ 이메일: `jyjy.9080@gmail.com`
- ✅ 이름: `Minjae Kim`
- ✅ 시행일자: `2026년 5월 10일`

만약 다른 정보로 변경하려면 모든 HTML 파일에서 해당 부분 찾아서 수정.

## 주의사항

- 이 문서는 일반적인 모바일 앱을 위한 템플릿입니다.
- 본인 앱의 구체적인 데이터 처리 사항이 변경되면 반드시 업데이트 필요합니다.
- 법적 분쟁 발생 시 변호사 자문 권장합니다.
