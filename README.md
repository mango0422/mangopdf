# 📂 PDF 리스트 뷰어

이 프로젝트는 **Tailwind CSS**와 **Vanilla JavaScript**를 사용하여 PDF 파일 목록을 표시하고, 선택한 PDF 파일을 내장된 **PDF.js 뷰어**에서 열 수 있도록 구현한 웹 애플리케이션입니다.

## 🚀 기능

- **PDF 리스트 보기**: 사전에 정의된 PDF 파일 목록을 버튼으로 제공
- **PDF 뷰어 내장**: 클릭 시 `iframe`을 사용하여 PDF.js 기반으로 파일 표시
- **다크 모드 지원**: Tailwind CSS의 `dark mode`를 활용하여 테마 전환 가능
- **반응형 디자인**: 모바일 및 데스크톱 환경에서 최적화

## 📌 사용 방법

1. **GitHub Pages 배포**  
   이 저장소를 GitHub Pages에서 실행하려면 아래 단계를 따르세요.

   ```
   Settings → Pages → Branch 선택 후 저장
   ```

   배포된 URL에서 PDF 리스트 뷰어를 사용할 수 있습니다.

2. **PDF 파일 업로드**

   - `/pdfs/` 폴더를 생성하고 원하는 PDF 파일을 추가하세요.
   - `index.html`의 `pdfFiles` 배열에 파일명을 추가하세요.

3. **다크 모드 사용**
   - 기본적으로 시스템 설정을 감지하여 다크 모드를 적용합니다.
   - 화면 오른쪽 하단 `🌙` 버튼을 클릭하여 테마를 전환할 수 있습니다.

## 📁 프로젝트 구조

```
📂 프로젝트 루트
 ├── 📂 pdfs/                  # PDF 파일 저장 폴더
 ├── 📂 pdfjs/                  # PDF.js 뷰어 라이브러리
 ├── 📄 index.html              # 메인 페이지
 ├── 📄 README.md               # 프로젝트 설명 파일
```

### 📜 라이선스

이 프로젝트는 [MIT License](LICENSE)를 따릅니다.

이 프로젝트에서 사용된 외부 라이브러리는 각각의 라이선스를 따릅니다:

- **[PDF.js](https://github.com/mozilla/pdf.js)**: MPL-2.0 (Mozilla Public License 2.0)
- **[Tailwind CSS](https://tailwindcss.com/)**: MIT License
