
# 파이썬으로 RAG 웹서비스 만들기 : (langchain - VectorDB (FAISS) - OpenAI)

### Sample PDF 문서 링크 : [링크바로가기](https://www.molit.go.kr/USR/policyData/m_34681/dtl.jsp?search=&srch_dept_nm=&srch_dept_id=&srch_usr_nm=&srch_usr_titl=Y&srch_usr_ctnt=&search_regdate_s=&search_regdate_e=&psize=10&s_category=&p_category=&lcmspage=1&id=4765)

## 활용 기술
![image](https://github.com/user-attachments/assets/1fd16d1a-cf58-4922-b5db-be521110d0b0)

## 예시 화면

![image](https://github.com/user-attachments/assets/a6a2f9fe-029e-4808-a153-712d528bad09)



## 사전 준비사항
### OpenAI API Key 발급
### 파이썬 가상환경

## 시작 방법  

1. 다음 명령어로 필요한 패키지 설치:
    ```bash
    pip install -r requirements.txt
    ```
2. `.env` 파일을 생성하고 OpenAI API Key 입력:
    ```
    OPENAI_API_KEY=your-openai-api-key-here
    ```
3. 다음 명령어로 웹 서비스 실행:
    ```bash
    streamlit run multiple_files.py    
    ```

## 사용법
1. 대상 파일을 Uploader에 드래그 한다
2. "PDF 업로드하기(VectorDB 생성) 버튼 클릭
3. 질문/요청을 하여 AI의 응답을 받는다
4. "관련문서" 클릭시 참고한 내용이 오른쪽에 표시 된다

## 기타
- FAISS 뷰어 (Vector Data 확인): https://faissviewer-hu2g6bbyxgcdjjumbsfysz.streamlit.app
