This is a small translation app with Azure Cognitive Services based on the Microsoft documentation.

After adding your translator key and run 
```python
python translator-app.py
```

This should be an output example
```python
[
    {
        "translations": [
            {
                "text": "Vamos visitar o Porto",
                "to": "pt-PT"
            },
            {
                "text": "Давайте посетим Порту",
                "to": "ru"
            }
        ]
    }
]
```