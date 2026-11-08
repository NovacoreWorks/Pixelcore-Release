# Pixelcore

Windows용 무료 이미지 편집기입니다. (Windows 10/11, 64비트)

- 레이어·마스크·조정 레이어·레이어 스타일을 쓰는 비파괴 편집
- PSD를 레이어째 열고 저장, PNG·JPG·WebP·AVIF·GIF·TIFF·SVG와 카메라 RAW 열기
- 필터 50종 이상, 룩 프리셋, 액션 기록과 폴더 단위 일괄 처리
- 익숙한 편집기 단축키와 메뉴 구성, 한국어/English, 다크/라이트 테마
- 인터넷 연결 없이 이 컴퓨터 안에서만 편집

이 저장소는 **공식 배포처**입니다. 프로그램 파일만 올리며, 소스 코드는 공개하지 않습니다.

## 받기
[Releases](https://github.com/NovacoreWorks/Pixelcore-Release/releases)에서 `Pixelcore-버전.zip`을 받아 원하는 곳에 압축을 풀고 `Pixelcore\Pixelcore.exe`를 실행하세요.
설치 과정은 없습니다. 폴더 안의 다른 파일(DLL, `resources` 폴더 등)은 함께 두어야 합니다.

## 정품 확인 (SHA-256)
받은 zip 파일의 해시값이 각 Release에 적힌 값과 같은지 확인하세요. PowerShell에서:

```
Get-FileHash .\Pixelcore-버전.zip -Algorithm SHA256
```

**이곳이 아닌 곳에서 받은 파일은 누군가 고쳤을 수 있으니 쓰지 마세요.**

## 사용 조건
- 무료 프로그램입니다. 개인·가정·회사 어디서든 쓸 수 있고, 받은 그대로라면 나눠 줘도 됩니다.
- 판매, 끼워 팔기, 고쳐서 배포, 만든이 표시 삭제는 금지합니다.
- 프로그램은 있는 그대로 제공되며, 사용 중 생긴 손해에 대해 만든이는 책임지지 않습니다. 중요한 원본은 미리 백업하세요.
- 자세한 내용은 zip 안의 `사용조건.txt`, 함께 들어 있는 오픈소스(Electron, React 등)의 라이선스는 `오픈소스 고지.txt`를 보세요. 프로그램 안에서는 도움말 → Pixelcore 정보에서도 볼 수 있습니다.
- 인터넷으로 아무 정보도 보내지 않습니다.
- Adobe와 Photoshop은 Adobe Inc.의 상표입니다. Pixelcore는 Adobe와 관련이 없으며, PSD는 파일 형식의 이름으로만 씁니다.

## 만든이
NovacoreWorks(LJY) · novacoreworks@gmail.com

© 2026 NovacoreWorks(LJY)
