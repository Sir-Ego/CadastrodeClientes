﻿# CadastrodeClientes
## Descrição do Projeto

Este é um sistema de cadastro de clientes desenvolvido em C#. O sistema permite que um usuário insira informações de um cliente, como Nome, Email, Telefone, CPF e Endereço. O endereço é buscado automaticamente por meio da API ViaCEP ao inserir o CEP, facilitando o preenchimento dos dados. Os dados cadastrados podem ser exportados em três formatos: TXT, XML e JSON.

O projeto segue os princípios SOLID, garantindo um código mais estruturado, reutilizável e de fácil manutenção.

## Estrutura do Projeto

O sistema foi organizado nas seguintes camadas:

Entities: Contém as classes que representam os modelos de dados.

Controllers: Responsáveis por gerenciar as requisições e respostas da aplicação.

Repositories: Implementação da persistência de dados.

Interfaces: Definição de contratos para a implementação dos repositórios e serviços.

Services: Contém a lógica de negócio da aplicação.

## Como Utilizar

### 1. Clonar o Repositório

Para obter o código-fonte, clone este repositório em sua máquina local utilizando o seguinte comando:

 git clone https://github.com/seu-usuario/seu-repositorio.git

### 2. Configuração do Diretório de Exportação

Os arquivos exportados serão salvos no diretório local da sua máquina. Para especificar um diretório diferente, siga os passos:

Abra o arquivo de configuração (caso haja um) ou ajuste no código diretamente.

Defina o caminho do diretório onde deseja armazenar os arquivos exportados.

Certifique-se de que o diretório tenha permissões adequadas para gravação.

Por padrão, os arquivos serão salvos no seguinte caminho:

Windows: C:\Users\SeuUsuario\Documents\ExportacaoClientes

Linux/macOS: ~/Documentos/ExportacaoClientes

### 3. Executar o Projeto

Certifique-se de ter o .NET instalado em sua máquina. Para rodar o sistema, utilize os comandos:

cd caminho-do-projeto

dotnet run

### 4. Exportação de Dados

Os dados dos clientes cadastrados podem ser exportados em três formatos:

TXT: Arquivo de texto simples.

XML: Formato estruturado para troca de dados.

JSON: Formato leve e amplamente utilizado para integrações.

Os arquivos serão gerados no diretório configurado.

### Dependências

.NET SDK

API ViaCEP para consulta de endereço via CEP

Bibliotecas Utilizadas:

Newtonsoft.Json: Utilizada para manipulação de dados JSON.

System.Net.HttpClient: Responsável por realizar chamadas HTTP para APIs externas.

## Direitos Autorais

Este projeto é de autoria de [Seu Nome] e está protegido sob as leis de direitos autorais. Qualquer redistribuição, modificação ou uso do código sem a devida autorização está estritamente proibido.

Aviso Legal: O autor não se responsabiliza por quaisquer danos ou prejuízos causados pelo uso indevido deste software.


Caso tenha dúvidas, entre em contato pelo email: ed.84.go@gmail.com ou abra uma issue no repositório.
