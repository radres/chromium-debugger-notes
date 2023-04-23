# Launch chrome on debug mode

## MacOS
```
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --remote-debugging-port=9222 --user-data-dir=remote-profile
```

install requirements for selenium
```
pip install --upgrade --force-reinstall chromedriver-binary-auto
```

run test script to check the actual driver is the debug chrome instance:

```
python test.py
```
