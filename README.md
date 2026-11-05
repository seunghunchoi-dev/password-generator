# 비밀번호 생성기

영문 대문자, 소문자, 숫자, 특수문자를 모두 포함한 비밀번호를 만드는 Windows 프로그램입니다.
6자리 이상으로 길이를 정할 수 있고, 만든 비밀번호는 클립보드에 자동으로 복사됩니다.

비밀번호는 Python의 암호용 난수 모듈 `secrets`로 만듭니다. 만든 비밀번호를 파일이나 네트워크로 보내지 않습니다.

## 실행

Python 3만 있으면 됩니다. 추가 패키지는 없습니다.

```
python password_generator_gui.py
```

## 실행 파일 만들기

```
pip install pyinstaller
pyinstaller password_generator_gui.spec
```

결과물은 `dist` 폴더에 생깁니다.

## 사용한 구성요소

- Python 표준 라이브러리, Tkinter

## 라이선스

[MIT](LICENSE) © 최승훈
