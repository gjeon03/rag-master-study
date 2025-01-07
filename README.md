### Jupyter Notebook 사용

### **가상환경(venv) 설정**

1.  **가상환경 생성**
    터미널에서 아래 명령어를 실행하여 가상환경을 생성합니다.
    ```
    python -m venv myenv
    ```
2.  **가상환경 활성화**
    - **Windows**:
      ```
      myenv\Scripts\activate
      ```
    - **Mac/Linux**:
      ```
      source myenv/bin/activate
      ```
3.  **필요한 라이브러리 설치**
    가상환경에서 Jupyter와 필요한 라이브러리를 설치합니다.
    ```
    pip install jupyter pandas numpy matplotlib
    ```
4.  **ipykernel 설치**
    가상환경을 Jupyter 커널에 연결하기 위해 `ipykernel`을 설치합니다.
    ```
    pip install ipykernel
    ```

### **Jupyter Notebook 설정**

1.  **커널 등록**
    가상환경을 Jupyter 커널로 등록합니다.
    ```
    python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
    ```

**VS Code에서 커널 선택**

- VS Code에서 `.ipynb` 파일을 열거나 새로 생성합니다.
- 상단의 커널 선택 메뉴에서 `Python (myenv)`를 선택하세요.

## venv 사용 방법

### python 가상환경 실행

```

python -m venv myenv
source myenv/bin/activate

```

### python 가상환경 종료

```

deactivate

```

### 라이브러리 설치

```

pip install -r requirements.txt

```
