## 가상 환경 설정

가상 환경 생성:
```bash
# 프로젝트 루트 디렉토리에서 실행
python3 -m venv .venv
```

가상 환경 활성화:
```bash
source .venv/bin/activate
```

가상 환경 비활성화:
```bash
deactivate
```

## VS Code 설정

확장 프로그램 설치:
1. python
2. python indent
3. autopep8

interpreter 설정:
1. Command Palette > interpreter 검색 > Python: Select Interpreter 선택
2. 프로젝트의 루트 디렉토리에 생성한 가상 환경 선택
3. Python 관련 코드를 에디팅 할 경우, 우측 하단에 사용 중인 Python interperter가 출력됨을 확인