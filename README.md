# pyCertificate

## Descrição

`pyCertificate` é uma aplicação Python que automatiza a geração de certificados a partir de uma planilha do Excel. Com uma interface gráfica simples, o usuário pode selecionar o arquivo de planilha, a aba desejada e a pasta de destino para salvar os certificados gerados.


## Funcionalidades

- 📂 Selecionar um arquivo Excel (`.xlsx`) contendo os dados dos participantes.
- 📑 Escolher a aba da planilha que contém os dados.
- 📁 Definir uma pasta de destino para salvar os certificados gerados.
- 🖼️ Gerar certificados automaticamente a partir de um modelo de imagem.


## Requisitos

Para executar o `pyCertificate`, certifique-se de ter os seguintes pacotes instalados:

```bash
pip install openpyxl pillow tkinter
```

## Como Usar

1. Execute o script Python:

```bash
python pyCertificate.py
```
2. Na interface:

```
   - Clique em **"Buscar"** para selecionar a planilha Excel.
   - Escolha a aba desejada no menu suspenso.
   - Selecione a pasta onde os certificados serão salvos.
   - Clique em **"Gerar Certificados"** para iniciar o processo.
```

## Estrutura do Arquivo Excel

A planilha deve conter os seguintes campos:

```
| Coluna | Descrição |
|--------|------------|
| A      | Nome do Curso |
| B      | Nome do Participante |
| C      | Tipo de Participação |
| D      | Data de Início |
| E      | Data de Término |
| F      | Carga Horária |
| G      | Data de Emissão |
```

## Personalização

- A imagem do certificado padrão deve ser salva como **`certificado_padrao.jpg`** no diretório do projeto.
- As fontes utilizadas devem estar no mesmo diretório (`tahoma.ttf` e `tahomabd.ttf`).


## Contribuição

Fique à vontade para abrir **issues** e enviar **pull requests** com melhorias para o projeto! 😊


## Licença
```
Este projeto está sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.
```

