# Atividade Avaliativa: Requisições em API com Flutter

Uma aplicação em Flutter para buscar informações de usuários na API pública [ReqRes](https://reqres.in/). O aplicativo permite consultar dados de usuários por ID com tratamento de erros e exibição das informações.

## 📱 Funcionalidades Principais

- **Busca de Usuário por ID**  
  - Insira um ID entre 1 e 12
  - Requisição à API ao clicar em "Buscar"

- **Exibição de Informações**  
  - Nome completo do usuário
  - Endereço de e-mail
  - Avatar (foto de perfil)

- **⚠ Tratamento de Erros**  
  - Mensagens para IDs inválidos (fora do intervalo 1-12)
  - Feedback para falhas de conexão/requisição

## 💻 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| Flutter | Framework para desenvolvimento multiplataforma |
| Dart | Linguagem de programação |
| http | Pacote para requisições HTTP |
| ReqRes API | API pública para dados de teste |

## 🚀 Instalação e Execução

### Pré-requisitos
- Flutter SDK instalado
- Dispositivo/emulador configurado

### Passo a passo

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/dudaclw/https-request-flutter.git
    cd https-request-flutter
   
2. **Instalar dependências**
   ```bash
   flutter pub get

3. **Executar o aplicativo**
      ```bash
   flutter run
