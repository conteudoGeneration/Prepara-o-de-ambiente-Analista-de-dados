<h1>Guia de Instalação do Python</h1>

1. Acesse o site oficial do Python:

👉 https://www.python.org/downloads/

Clique no botão para baixar a versão mais recente do **Python 3**.

<br/>

| ⚠️ | **ATENÇÃO:** Sempre utilize a versão estável mais recente. A numeração pode mudar com o tempo. |
|----|------------------------------------------------------------|

---

# 🪟 Instalação no Windows

2. Após efetuar o download, execute o instalador `.exe`.

3. Na primeira tela do instalador, **marque a opção obrigatória**:

<div align="center">
<b>Add Python to PATH</b>
</div>

4. Clique em **Install Now**.

5. Aguarde a conclusão da instalação e clique em **Close**.

---

## Verificando a instalação (Windows)

6. Pressione:
Win + R

7. Digite:
cmd

8. Execute:

```bash
python -V
```

9. Verifique o pip:

```bash
pip -V
```

---

# 🍎 Instalação no macOS

10. Acesse:
https://www.python.org/downloads/macos/

11. Baixe o arquivo `.pkg`.

12. Execute o instalador e siga:
Continue → Continue → Agree → Install

13. Informe sua senha quando solicitado.

---

## Verificando a instalação (macOS)

14. Abra o Terminal.

15. Execute:

```bash
python3 -V
```

16. Verifique o pip:

```bash
pip3 -V
```

---

## (Opcional) Criar alias

```bash
echo "alias python=python3" >> ~/.zshrc
echo "alias pip=pip3" >> ~/.zshrc
source ~/.zshrc
```

---

# Testando o Python

17. Execute:

```bash
python
```

```python
print("Hello World")
```

18. Para sair:

```bash
exit()
```

---

# Criando seu primeiro arquivo

19. Crie:
app.py

```python
print("Olá, mundo!")
```

20. Execute:

Windows:
```bash
python app.py
```

macOS:
```bash
python3 app.py
```

---

# Instalando pacotes

Windows:
```bash
pip install requests
```

macOS:
```bash
pip3 install requests
```

---

# Resumo

| Sistema | Ver versão | Executar | Instalar |
|--------|-----------|----------|-----------|
| Windows | python -V | python app.py | pip install |
| macOS | python3 -V | python3 app.py | pip3 install |

<br/>
<b>Pronto! Python instalado com sucesso 🚀</b>
