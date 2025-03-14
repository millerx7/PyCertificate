# PyCertificate - Gerador Automático de Certificados

PyCertificate é uma ferramenta poderosa e automatizada para a geração de certificados personalizados. Com integração direta a planilhas, o projeto permite criar certificados rapidamente, sobrepondo os dados individuais de cada aluno em um template predefinido.

🚀 **Este projeto foi desenvolvido como parte de um tutorial do canal Dev Aprender | Jhonatan de Souza.**

## 🚀 Funcionalidades

- 🔥 **Geração rápida e automática** de certificados a partir de planilhas.
- 📊 **Suporte a arquivos Excel** (XLSX) via `openpyxl`.
- 🖼 **Customização dinâmica** dos certificados utilizando `Pillow`.
- 📜 Suporte a **dados detalhados**, incluindo:
  - Nome do participante
  - Curso realizado
  - Tipo de participação
  - Carga horária
  - Data de início e término
  - Data de emissão
- 💾 **Exportação automática** em formato PNG e PDF.
- ⚡ **Fácil integração** com outros sistemas.

## 📥 Instalação

Certifique-se de ter o Python 3 instalado. Em seguida, clone o repositório e instale as dependências:

```sh
# Clone o repositório
git clone https://github.com/seu-usuario/PyCertificate.git
cd PyCertificate

# Instale as dependências
pip install -r requirements.txt
```

## 🛠 Como Usar

1. Prepare uma planilha Excel (`dados.xlsx`) com as colunas:
   ```
   Nome | Curso | Participação | Carga Horária | Data Início | Data Término | Data Emissão
   ```
2. Execute o script principal:
   ```sh
   python pycertificate.py
   ```
3. Os certificados gerados serão salvos automaticamente na pasta `output/`.

## 🎨 Customização do Certificado

O layout do certificado pode ser personalizado editando o arquivo de template na pasta `templates/`. Você pode alterar a posição dos textos e fontes dentro do código.

## 📌 Exemplo de Saída

Aqui está um exemplo de certificado gerado pelo PyCertificate:

<img src="https://github.com/user-attachments/assets/af333db2-35c2-4b83-808b-3c897c3abd3d" alt="Exemplo de Certificado" width="500"/>

## &#x20;Contribuição

Contribuições são bem-vindas! Siga os passos:

1. Faça um fork do repositório.
2. Crie uma branch (`feature-nova-funcionalidade`).
3. Commit suas mudanças.
4. Abra um Pull Request.

## 📝 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

🔥 PyCertificate – Transformando dados em certificados de forma inteligente e eficiente!

