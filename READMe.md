# package
gpt
    __init__.py
    main.py
    train.py
    config.yml
    setup.py
    README.md


# installation
pip install setuptools twine
python setup.py dist
pip install dis/GPT4-0.0.1.tar.gz
twine upload --repository-url https://test.pypi.org/legacy/dist/GPT4-0.0.1.tar.gz