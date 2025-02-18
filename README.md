
# 🛠️ Deface Auto Upload  

### 📌 Descrição  
Este script em Python automatiza o upload de um arquivo `.html` para um site via método `POST`. Ele solicita a URL ao usuário e tenta enviar o arquivo automaticamente.  

### ⚠️ Aviso Legal  
**Este script é apenas para fins educacionais e de segurança.**  
O uso indevido pode violar leis e políticas. O autor não se responsabiliza pelo uso inadequado.  

---

## 🚀 Funcionalidades  
✔️ Envio automático de um arquivo `.html` para um site via `POST`.  
✔️ Input estilizado com cores RGB no terminal.  
✔️ Verificação de erros como conexão falha ou arquivo ausente.  

---

## 📌 Instalação  

1. **Clone ou baixe o repositório:**  
   ```sh
   git clone https://github.com/seu-usuario/deface-auto-upload.git
   cd deface-auto-upload
   ```

2. **Instale as dependências:**  
   ```sh
   pip install -r requirements.txt
   ```

3. **Crie um arquivo HTML para envio:**  
   Crie um arquivo chamado `pagina.html` na mesma pasta do script.

---

## ▶️ Como Usar  

1. Execute o script:  
   ```sh
   python deface.py
   ```  
2. Digite a URL de destino (exemplo: `http://site.com/upload`).  
3. O script enviará automaticamente o arquivo `pagina.html`.  
4. Verifique a resposta do servidor no terminal.  

---

## 📦 Dependências  
- `requests` → Para envio de dados HTTP.  
- `colorama` → Para cores no terminal.  
- `rich` → Para um input estilizado.  

Instale com:  
```sh
pip install requests colorama rich
```

---

## 🏴‍☠️ Exemplo de Uso  
```sh
Digite a URL do site (exemplo: http://exemplo.com/upload): http://site.com/upload
[✔] Arquivo enviado com sucesso!
```

---

## 📜 Licença  
Distribuído sob a **MIT License**. Veja `LICENSE` para mais detalhes.  

---

**Criado por Walker** 🚀
