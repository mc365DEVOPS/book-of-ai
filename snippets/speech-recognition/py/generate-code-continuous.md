Generate a Python sample that continuously recognizes speech from the microphone.

```bash
ai dev new speech-to-text-continuous-reco --python
cd speech-to-text-continuous-reco-py
```

??? example "See the code; learn how it works..."

    [:material-file-code: main.py](https://raw.githubusercontent.com/robch/book-of-ai/main/docs/samples/speech-to-text-continuous-reco-py/main.py)

    [:material-file-document-outline: Deep dive on how it works](/speech/speech-to-text-continuous-reco-py/sample-overview.md)  

=== "Windows"

    ```bash title="Create virtual environment"
    python -m venv env
    env/Scripts/activate
    ```

    ```bash title="Install requirements"
    pip install -r requirements.txt
    ```

    ```bash title="Run the sample"
    ai dev shell
    python main.py
    ```

=== "macOS"

    ```bash title="Create virtual environment"
    python3 -m venv env
    source env/bin/activate
    ```

    ```bash title="Install requirements"
    pip install -r requirements.txt
    ```

    ```bash title="Run the sample"
    ai dev shell
    python3 main.py
    ```

=== "Linux"

    ```bash title="Create virtual environment"
    python3 -m venv env
    source env/bin/activate
    ```

    ```bash title="Install requirements"
    pip install -r requirements.txt
    ```

    ```bash title="Run the sample"
    ai dev shell
    python3 main.py
    ```