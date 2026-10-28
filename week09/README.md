# week09

## 무엇을 하는 코드인가
영화진흥위원회(KOBIS) 오픈 API로 특정 날짜의 일별 박스오피스 1위 영화 제목을 가져와 출력합니다.

## 설치
```
pip install -r requirements.txt
```
KOBIS 오픈 API 키를 발급받아 `week09/secret.py` 파일을 만들고 아래처럼 적어 주세요.
```python
API_KEY = "발급받은_키"
```

## 실행
```
cd week09
python main.py
```
조회할 날짜는 `main.py`의 `"20260824"`(8자리)를 바꾸면 됩니다.
