# 🎁 Lista de Presentes da Micy (com persistência)

Versão com **TinyDB persistente**, que mantém os presentes marcados mesmo após reiniciar o servidor Render.

## 🚀 Como publicar no Render

1️⃣ Crie um repositório no GitHub e envie esta pasta (`lista_presentes_micy_persistente`).  
2️⃣ Vá até [https://render.com](https://render.com) → **New Web Service**.  
3️⃣ Conecte seu GitHub e selecione este repositório.  
4️⃣ Configure:

- **Environment:** Python 3  
- **Build Command:**  
  ```bash
  pip install -r requirements.txt
  ```
- **Start Command:**  
  ```bash
  python app.py
  ```

5️⃣ Clique em **Create Web Service**.  
Em poucos minutos, seu link estará no ar (ex: `https://lista-presentes-micy.onrender.com`).

---

Feito com ❤️ para ajudar os convidados da Micy a escolherem presentes facilmente.
