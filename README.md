Extrator de Faturas Equatorial
Este projeto contém um script Python para extrair dados detalhados de faturas de energia da Equatorial em formato PDF e consolidá-los em um único arquivo Excel formatado.

⚠️ Aviso Importante: Compatibilidade
O script foi desenvolvido e testado exclusivamente para o layout das faturas de energia da Equatorial. Ele não funcionará com faturas de outras concessionárias ou com layouts diferentes.

Passo 1: Instalação das Bibliotecas (Pré-requisitos)
Antes de usar o script, você precisa instalar as bibliotecas necessárias. Este comando funciona tanto no Windows quanto no Linux/macOS.

Abra o seu terminal (Prompt de Comando, PowerShell, etc.).
Execute o seguinte comando:
    pip install pandas pdfplumber xlsxwriter

  pip install pandas pdfplumber xlsxwriter

Crie uma pasta no seu computador e coloque todos os seus arquivos PDF da Equatorial dentro dela.

Abra o arquivo de script (ex: extrator_detetive.py) com um editor de texto.

Localize a linha que define a variável pdf_directory.

Substitua o caminho existente pelo caminho completo da pasta onde você salvou seus PDFs.

Salve as alterações no arquivo de script.

Abra o seu terminal.

Navegue até a pasta onde seu script Python está salvo usando o comando cd.

Execute o script com o comando: python extrator_detetive.py