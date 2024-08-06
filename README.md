# Persion AI Docent(Upstage X Seoul National University Mini Project)

## 1.Overview
Upsatge API를 활용하여 미술 작품에 대해 궁금한 점을 질의 응답할 수 있는 대화형 AI 구현

### Usage
.env 파일을 생성하여 UPSTAGE_API_KEY의 환경변수에 API키를 설정합니다.
```
UPSTAGE_API_KEY=up_71ks...
```

python 환경을 구축하고 필요한 패키지를 다운받습니다.
```
pip install -r requirements.txt
```

run.py 파이썬 파일을 실행해 gradio demo 챗봇을 실행할 수 있습니다.
```
python run.py
```

http://127.0.0.1:7870 로컬 서버에 접속하여 작품에 대한 QA를 진행할 수 있습니다.
![image](https://github.com/user-attachments/assets/ae52b753-37f4-4845-8a15-651f131b1ca3)


### 데모 시연
https://youtu.be/tEPAbOXvj0w

### etc
미술작품 데이터
- [국립현대미술관](https://www.mmca.go.kr/)의 130개의 미술작품 데이터를 수집
