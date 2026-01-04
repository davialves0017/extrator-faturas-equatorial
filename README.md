# Extrator de Faturas Equatorial

Este projeto contém um script Python para extrair dados detalhados de faturas de energia da Equatorial em formato PDF e consolidá-los em um único arquivo Excel formatado.

---

### ⚠️ Aviso Importante: Compatibilidade

O script foi desenvolvido e testado **exclusivamente para o layout das faturas de energia da Equatorial**. Ele não funcionará com faturas de outras concessionárias ou com layouts diferentes.

---

### Passo 1: Instalação das Bibliotecas (Pré-requisitos)

Antes de usar o script, você precisa instalar as bibliotecas necessárias. Este comando funciona tanto no Windows quanto no Linux/macOS.

1.  Abra o seu terminal (Prompt de Comando, PowerShell, etc.).
2.  Execute o seguinte comando:
```bash
    pip install pandas pdfplumber xlsxwriter