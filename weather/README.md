# MiniDu — prosty MVP do nauki angielskiego

To proste demo aplikacji typu Duolingo: Flask + statyczne dane JSON.

Quick start:

1. Utwórz środowisko i aktywuj je:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Zainstaluj zależności:

```bash
pip install -r requirements.txt
```

3. Uruchom testy (smoke test):

```bash
python test_app.py
```

4. Uruchom aplikację lokalnie:

```bash
python app.py
```

Frontend: odwiedź http://127.0.0.1:5000

Co możesz dodać dalej:
- kolejne lekcje i pytania w `lessons.json`
- logowanie użytkowników i śledzenie postępów
- poziomy trudności i mechanizmy powtórek
