This is a small translation app with Azure Cognitive Services based on the Microsoft documentation.

After adding your translator key run the following command 
```python
python translator-app.py
```

This should be an output example
```python
[
    {
        "translations": [
            {
                "text": "Gostaria de dirigir o seu carro pelo quarteirão algumas vezes! Vamos visitar o Porto",
                "to": "pt-PT"
            },
            {
                "text": "Очень хотелось бы несколько раз проехать на своей машине по кварталу! Давайте посетим Порту",  
                "to": "ru"
            }
        ]
    }
]